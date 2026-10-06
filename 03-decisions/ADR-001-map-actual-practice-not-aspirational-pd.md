# ADR-001: Map Actual Practice, Not Aspirational Position Description Scope

## Status

Accepted

## Date

YYYY-MM-DD

## Decision

The repository will map actual current-state practice rather than assuming that all position description accountabilities are being performed in practice.

Position descriptions may be used as context, but they are not treated as proof of current-state work.

## Context

The current-state SOP mapping work is intended to document what actually happens today across:

- Customer Data and Systems Support
- Customer Focus Information Support

Some formal role descriptions may include broader or aspirational responsibilities that are not currently performed in practice.

For this repository, current-state accuracy is more important than role-description completeness.

This is especially important where a role description suggests broader CX measurement, reporting or analysis responsibilities that were not performed in practice.

## Rationale

Mapping aspirational role scope as current practice would create misleading SOPs, risks and business case evidence.

It could cause the repository to:

- describe work that does not currently happen
- overstate current capability
- blur the difference between current state and future intent
- create incorrect assumptions about role maturity
- weaken future business case evidence
- hide actual operational gaps
- make validation harder for officers and stakeholders

## Consequences

## Positive consequences

- Current-state documentation will be more accurate.
- SOPs will be easier to validate with people doing the work.
- Future-state signals will be grounded in real evidence.
- Business case material will be more defensible.
- Aspirational capability gaps can still be captured, but clearly labelled.

## Trade-offs

- Some formal position description responsibilities may not appear in current-state SOPs.
- Additional explanation may be needed for stakeholders expecting role descriptions to define the mapping scope.
- Future capability design will require a later synthesis step rather than being assumed from PD wording.

## Working rule

When a responsibility appears in a position description but is not confirmed as actual practice:

- do not create a current-state SOP for it
- do not treat it as current-state evidence
- record it as an assumption, gap or future capability signal only if useful
- validate before including it in business case evidence

## Explicit exclusion unless validated

The following should not be mapped as current-state work unless separately validated as actual practice:

- broad CX measurement leadership
- monthly Customer Service Indicator reporting
- customer feedback and complaints reporting
- direct customer contact channel trend reporting
- organisation-wide customer experience performance analysis
- ad hoc CX reporting service
- reporting tool maintenance
- strategic CX performance recommendations

## What can still be captured

Aspirational or unperformed accountabilities may still be captured as:

- role gap signals
- future capability signals
- assumptions requiring validation
- business case questions
- future operating model hypotheses

They should not be written as current-state SOPs.

## Review trigger

Review this ADR if:

- stakeholders confirm that previously excluded work is now performed in practice
- new evidence shows that a responsibility is part of current-state work
- the repository shifts from current-state mapping to future-state operating model design
- a business case requires explicit comparison between intended role scope and actual operating reality

## Related files

- `00-project-control/role-intent-vs-actual-practice.md`
- `00-project-control/working-principles.md`
- `03-cross-function-learning/role-gap-and-capability-signals.md`
- `03-cross-function-learning/future-operating-model-signals.md`
- `04-templates/validation-checklist-template.md`

## Review notes

| Date | Update | Updated by |
|---|---|
| YYYY-MM-DD | Initial ADR created. |  |
