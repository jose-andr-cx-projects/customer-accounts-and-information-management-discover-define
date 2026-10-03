# CX Current-State SOP Mapping

This repository captures the current-state standard operating procedures for two Customer Experience functions:

1. Customer Data and Systems Support
2. Customer Focus Information Support

The purpose is to document how work is actually performed today, identify pain points and exceptions, and understand what each function reveals about future omnichannel service delivery, information reuse, customer data quality and operating model design.

This is a discovery and concept-development repository. It is not an approved operational policy repository.

---

## Why this repository exists

Customer Experience work relies on two important operational foundations:

* reliable customer data and account context
* reliable service delivery information and staff guidance

These foundations are increasingly important as service delivery moves toward more connected, omnichannel experiences.

Before designing a future operating model, this repository maps the current state of two related but separate functions.

The immediate goal is to understand:

* what work is performed today
* how requests and tasks are triggered
* what systems and tools are used
* what decisions are made
* where exceptions and workarounds occur
* where knowledge is undocumented
* where customer data or service information quality creates friction
* what could be improved, reused or automated in future

---

## Current-state principle

This repository maps actual practice, not aspirational position descriptions.

Position descriptions are used as reference material, but SOPs are only created for work that is actually performed today.

If a responsibility appears in a position description but is not performed in practice, it should be captured as a role-gap or future capability signal rather than documented as a current SOP.

This is important because the repository is intended to create an honest operational baseline.

---

## Functions in scope

## 1. Customer Data and Systems Support

This function focuses on customer data quality, customer record maintenance, duplicate management, corrective actions and basic CRM or system-related support.

The current-state focus includes:

* identifying duplicate customer records
* cleansing and simplifying customer records
* manually de-duplicating customer records
* monitoring customer record quality
* correcting customer data quality issues
* recording progress of data cleansing work
* escalating data quality or system issues
* supporting basic CRM data maintenance requests

The current mapping intentionally omits broader CX measurement, reporting and analysis accountabilities where those responsibilities have not been operationalised in practice.

## 2. Customer Focus Information Support

This function focuses on accurate, up-to-date and usable information for direct customer service delivery.

The current-state focus includes:

* updating Service Directory content
* maintaining customer service tools
* supporting CRM user issues and requests
* maintaining telephone messages on hold
* coordinating hot topic customer responses
* communicating urgent updates to branch staff
* supporting Service Directory editors
* improving first contact resolution content

---

## Repository structure

```text
cx-current-state-sop-mapping/
  README.md

  00-project-control/
    purpose-and-scope.md
    working-principles.md
    co-design-session-guide.md
    assumptions-log.md
    glossary.md
    role-intent-vs-actual-practice.md

  01-customer-data-and-systems-support/
    README.md
    role-context.md
    actual-practice-summary.md
    pd-intent-vs-current-reality.md
    sop-inventory.md
    current-state-process-map.md
    work-types.md
    systems-and-tools.md
    decision-points.md
    exception-pathways.md
    data-quality-controls.md
    pain-points-and-risks.md
    omnichannel-implications.md

    sops/
      CDSS-SOP-001-identify-duplicate-customer-records.md
      CDSS-SOP-002-cleanse-and-simplify-customer-records.md
      CDSS-SOP-003-manually-deduplicate-customer-records.md
      CDSS-SOP-004-monitor-customer-record-quality.md
      CDSS-SOP-005-correct-customer-data-quality-issues.md
      CDSS-SOP-006-record-progress-of-data-cleansing-work.md
      CDSS-SOP-007-escalate-data-quality-or-system-issues.md
      CDSS-SOP-008-support-basic-crm-data-maintenance-requests.md

  02-customer-focus-information-support/
    README.md
    role-context.md
    actual-practice-summary.md
    sop-inventory.md
    current-state-process-map.md
    knowledge-and-work-types.md
    systems-and-tools.md
    decision-points.md
    exception-pathways.md
    content-quality-controls.md
    pain-points-and-risks.md
    omnichannel-implications.md

    sops/
      CFIS-SOP-001-update-service-directory-content.md
      CFIS-SOP-002-maintain-customer-service-tools.md
      CFIS-SOP-003-support-crm-user-issues-and-requests.md
      CFIS-SOP-004-maintain-telephone-messages-on-hold.md
      CFIS-SOP-005-coordinate-hot-topic-customer-responses.md
      CFIS-SOP-006-communicate-urgent-updates-to-branch-staff.md
      CFIS-SOP-007-support-service-directory-editors.md
      CFIS-SOP-008-improve-first-contact-resolution-content.md

  03-cross-function-learning/
    common-patterns.md
    shared-systems.md
    shared-governance-gaps.md
    shared-data-and-knowledge-dependencies.md
    role-gap-and-capability-signals.md
    automation-candidates.md
    future-operating-model-signals.md

  04-templates/
    sop-discovery-template.md
    current-state-sop-template.md
    interview-guide-template.md
    process-observation-template.md
    decision-table-template.md
    exception-log-template.md
    pain-point-log-template.md
    omnichannel-implication-template.md

  05-decisions/
    ADR-001-map-actual-practice-not-aspirational-pd.md
    ADR-002-keep-functions-separated-during-current-state-discovery.md
    ADR-003-use-github-for-sop-discovery.md
    ADR-004-design-for-future-enterprise-migration.md
```

---

## How to use this repository

### Step 1: Map work as it happens today

Start with officer-led discovery.

Ask:

* What work lands on your desk in a normal week?
* What work is recurring?
* What work is ad hoc?
* What work is urgent?
* What work is undocumented?
* What work depends on your personal knowledge?
* What work appears in the PD but does not happen in practice?

### Step 2: Build the SOP inventory

For each function, create a list of current activities that may need SOPs.

Each inventory item should capture:

* activity name
* trigger
* frequency
* systems used
* owner
* risk level
* documentation status
* known pain points

### Step 3: Draft current-state SOPs

Use the shared SOP template to map:

* purpose
* trigger
* inputs
* process steps
* decision points
* systems and tools
* handoffs
* exceptions
* workarounds
* controls
* pain points
* omnichannel implications

### Step 4: Validate with the officer

Each SOP should be reviewed with the officer who performs the work.

Validation should check:

* is this how the work actually happens?
* what is missing?
* what is informal?
* what varies case by case?
* what is unclear?
* what should not be standardised yet?

### Step 5: Capture cross-function learning

Do not merge the two functions during current-state discovery.

Instead, capture shared patterns in `03-cross-function-learning/`.

Look for:

* shared systems
* duplicated information
* unclear ownership
* manual workarounds
* governance gaps
* data quality risks
* content quality risks
* automation candidates
* omnichannel readiness gaps

---

## GitHub working practices

Use GitHub as a structured working space for discovery, not as a final enterprise operating platform.

Recommended practices:

* use small, clear commits
* keep draft files marked as draft
* use GitHub issues to track open questions
* use decision records for important choices
* avoid sensitive or personal information
* use fictional or anonymised examples only
* design the structure so it can migrate into an enterprise-owned GitHub environment later

Example commit messages:

* `Add initial repo structure`
* `Add current-state mapping principles`
* `Add Customer Data and Systems Support SOP inventory`
* `Draft CFIS Service Directory update SOP`
* `Add role intent vs actual practice note`

---

## Labels

Suggested GitHub issue labels:

* `current-state`
* `sop`
* `data-quality`
* `service-knowledge`
* `systems`
* `decision-point`
* `exception`
* `pain-point`
* `risk`
* `omnichannel`
* `automation-candidate`
* `role-gap`
* `enterprise-migration`

---

## What this repository is not

This repository is not:

* an approved operational policy library
* a customer data store
* a place to store personally identifiable information
* a replacement for enterprise records management
* a final knowledge management platform
* a decision to merge the two functions
* a complete future operating model

---

## V0.1 definition of done

The V0.1 repository is complete when:

* the repository structure is created
* the mapping principles are documented
* both functions have separate folders
* each function has a draft SOP inventory
* at least two current-state SOPs are drafted for each function
* role intent vs actual practice is documented
* cross-function learning files are created
* enterprise migration considerations are documented
* no sensitive customer or operational data is stored in the repository

---

## V1 definition of done

The V1 repository is complete when:

* priority SOPs have been mapped with the officers who perform the work
* decision points and exceptions are documented
* pain points and risks are documented
* omnichannel implications are captured
* role gaps are identified
* automation candidates are listed
* shared governance gaps are visible
* future operating model signals are synthesised
* the repository can support a business case for a more mature CX operating capability

---

## Strategic intent

This repository is an operational evidence layer for the current **business-led Customer Data Architecture** priority.

Its role is not to design the future architecture.

Its role is to make visible how customer data, customer accounts, service information and operational knowledge are actually handled today so future decisions are grounded in real work rather than assumed process.

The current-state SOP work should therefore pay particular attention to:

- where customer information is created, changed or corrected;
- where staff have to reconstruct customer context manually;
- where duplicate or fragmented records affect service delivery;
- which decisions depend on tacit officer knowledge;
- where authorised source-system actions occur;
- where review, verification or escalation is required;
- where service information and customer information depend on each other;
- where unclear ownership creates recurring work; and
- which recurring problems indicate a stewardship or capability gap rather than a one-off process issue.

Findings from this repository should feed Customer Account Management and other portfolio work as **evidence**, not as a predetermined future operating model.

The current-state SOP work should help reveal what needs to be governed, improved, reused or automated before the organisation can scale more connected customer experiences.
