# 1D — Actual Practice Summary

**Status:** Discovery synthesis  
**Scope:** Customer Accounts + Information Management  
**Evidence maturity:** Mixed. Customer Accounts has stronger operational detail; Information Management is less fully validated but the systemic patterns are sufficiently clear to support 2D framing.

## Why this summary exists

Early discovery created detailed SOP, role, system, control, pain-point and governance files for separate Customer Accounts and Information Management functions.

Those files were useful for learning, but the detail obscured the main current-state story.

This summary keeps the essentials needed to understand the problem and carry it into design.

---

## 1. Current operating pattern

Across both domains, reliable customer service depends on staff reconstructing context from multiple records, systems, content sources and people.

A recurring pattern is:

```text
information exists in different places
        ↓
staff interpret / reconcile it
        ↓
judgement or informal coordination fills gaps
        ↓
a correction, response or update is made
        ↓
the underlying fragmentation often remains
```

The work is therefore often **corrective and interpretive**, rather than supported by a clearly connected business-context model.

---

## 2. Customer Accounts — actual-practice essentials

Current discovery points to a practical workload around:

- identifying potential duplicate customer records;
- comparing records before deciding whether they may represent the same customer;
- cleansing or correcting customer information;
- manually resolving some duplicate or inconsistent records;
- supporting CRM data-maintenance requests;
- escalating cases where identity, authority, sensitivity or system constraints make a change unsafe;
- tracking unresolved or completed remediation work.

### What makes the work difficult

The main issues are not simply poor-quality fields.

They include:

- a CRM account is not always equivalent to one unique customer;
- legitimate statutory, non-statutory, organisation and relationship distinctions need to be preserved;
- matching email, mobile or name is a **signal**, not proof of identity;
- records can contain missing or conflicting information;
- duplicate review and correction depend on human judgement;
- some work depends on local knowledge or manual trackers;
- system and permission constraints can create workarounds;
- upstream processes can continue creating the problems being remediated.

### Controls that matter

The detailed discovery consistently points to the need for:

- record comparison;
- sufficient evidence before correction;
- privacy/sensitivity checks;
- permission and authority checks;
- escalation thresholds;
- traceability of changes;
- clear distinction between a potential duplicate, confirmed duplicate and safe merge candidate.

### Current-state implication

The organisation can clean records, but cleaning alone does not establish a sustainable understanding of **who the customer is, what relationships matter, what can be trusted, and who can decide**.

---

## 3. Information Management — actual-practice essentials

The current Information Management model has been shaped heavily around supporting Contact Centre staff.

Typical work includes:

- maintaining Service Directory or customer-service information;
- refining service information into staff guidance;
- supporting Salesforce/CRM information needs;
- coordinating urgent or hot-topic responses;
- communicating changes to frontline staff;
- supporting editors and content maintainers;
- improving information used for first-contact resolution.

### The operating-model constraint

Much of the knowledge model answers:

> **What should the Contact Centre agent do?**

rather than first modelling:

> **What is true about this service, rule, requirement, customer situation or operational event?**

Salesforce Knowledge reflects this internally focused model. Useful information exists, but it is often manually refined, procedural and weakly connected to the underlying service and operational context.

### Information outside CRM

A large amount of customer-relevant context originates outside Salesforce and outside CX.

It may live in:

- service-area systems;
- operational processes;
- local service knowledge;
- temporary service status or disruptions;
- policy/process changes;
- communications between teams.

CX can therefore depend on another area:

1. recognising that something has changed;
2. recognising that it matters to customers;
3. manually telling CX or the Contact Centre;
4. allowing CX to interpret and republish that information.

This creates an **awareness and observability gap**, not merely a content-maintenance problem.

### Service ↔ Knowledge relationships

Discovery also shows that service and knowledge relationships are uneven:

- one knowledge item may support several services;
- one service may rely on several knowledge items;
- some services may have dedicated knowledge;
- some may have no explicit knowledge link.

The relationship exists operationally, but it is not consistently treated as a governed business relationship with clear ownership, source and lifecycle.

### Current-state implication

The organisation can maintain knowledge articles and service information, but that does not by itself establish **what service context is authoritative, what changed, who owns the meaning, and where that context should be reused**.

---

## 4. Systems are carrying fragments of the context

Discovery references a mix of systems and tools including:

- Salesforce;
- Service Directory / customer-service knowledge tools;
- Pathway and other operational systems;
- web/intranet content;
- email and Teams;
- shared mailboxes;
- spreadsheets and local trackers.

The issue is not that these systems exist.

The issue is that **business meaning and relationships are distributed across them**, while staff often provide the integration through interpretation and manual coordination.

---

## 5. Shared patterns across Accounts and Information

The two domains are different, but they expose the same structural conditions.

| Shared condition | Customer Accounts expression | Information Management expression |
|---|---|---|
| Fragmented context | Multiple/inconsistent customer records | Service information spread across tools and teams |
| Human interpretation | Determine whether records relate to the same customer | Determine which guidance/source is current and relevant |
| Unclear ownership | Who can correct, merge or verify? | Who owns, approves, updates or retires information? |
| Weak lifecycle | Remediation after defects appear | Content can become stale or temporary information can persist |
| Local workarounds | Manual review, tracking and reconciliation | Email, Teams and manual republishing |
| Reactive model | Clean/correct after problems occur | Update guidance after someone reports a change |
| Trust problem | Can this customer/account context be relied on? | Can this service/operational information be relied on? |

### Key shared dependency

Customer-facing staff need confidence in both:

1. **customer context** — who they are dealing with and what relationship applies;
2. **service context** — what is true, what applies and what has changed.

If either is weak, staff compensate through search, interpretation, escalation and local knowledge.

---

## 6. Governance and stewardship signals

The detailed discovery repeatedly points to questions about:

- ownership;
- decision rights;
- approval;
- standards;
- escalation;
- review cycles;
- expiry/retirement;
- traceability;
- feedback from repeated issues into upstream prevention.

These are not evidence that one new team or governance body is required.

They are evidence that **business context needs explicit stewardship** rather than relying primarily on system ownership or individual experience.

---

## 7. What is supported versus still uncertain

### Sufficiently supported for problem framing

- customer/account context can be fragmented and require manual reconciliation;
- duplicate and correction work contains identity and risk decisions, not just data cleansing;
- service information is shaped by an internally focused Contact Centre model;
- service and knowledge relationships are not consistently explicit or governed;
- significant customer-relevant context exists outside CRM;
- CX can depend on manual communication when operational reality changes;
- both domains rely heavily on human judgement, ownership and trust;
- current systems hold parts of the context rather than one coherent business view.

### Still incomplete

- organisation-wide scale and frequency;
- quantified staff effort;
- full validation of every Information Management process;
- complete ownership maps;
- complete source-of-truth mapping;
- control effectiveness;
- financial value or investment case.

These gaps do **not** need to block 3D.

Further evidence should be gathered only where a real design/test decision requires it.

---

## 8. 1D conclusion

The current-state problem is bigger than:

- duplicate records;
- data cleansing;
- knowledge articles;
- content maintenance;
- system integration.

The stronger shared finding is:

> **Customer and service context is fragmented across records, systems, content and organisational boundaries, and staff currently do significant interpretive work to reconstruct enough context to serve the customer.**

That is the evidence base for 2D.
