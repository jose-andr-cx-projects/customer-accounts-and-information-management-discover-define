# Customer Accounts & Information Management — Discover + Define

**Status:** Complete enough for progression  
**4D stage:** 1D Discover + 2D Define  
**Owner:** José Andrade  
**Next stage:** Business Context Architecture — 3D Develop + 4D Deliver

## Purpose

This repository captures the **Discover and Define work for two related CX problem streams**:

1. **Customer Accounts** — how the City identifies, represents and maintains customer and account context.
2. **Information Management** — how the City creates, interprets, maintains and reuses service information and operational context.

The work began through current-state SOP and operational mapping, but this is **not primarily an SOP repository**.

The SOPs, process maps, controls and role notes are supporting evidence.

The main outcome is a practical problem frame that explains what we learned, what remains uncertain, and why both streams now progress together into the **Business Context Architecture**.

## 1D — Discover

### Customer Accounts

Discovery identified:

- duplicated and inconsistent customer/account records;
- uncertainty about whether records represent the same customer;
- legitimate statutory, non-statutory and organisation-account distinctions;
- customer relationships that are not represented consistently;
- manual investigation, reconciliation and correction;
- recurring remediation with weaker upstream prevention;
- unclear stewardship and decision rights;
- fragmented customer context across services and systems.

**Core learning:** record quality is only part of the problem. The wider question is what customer context is needed, how trustworthy it is, and who can act on it.

### Information Management

Discovery identified:

- an information model shaped heavily around the Contact Centre and phone-agent handling;
- service information manually interpreted and refined into internal guidance;
- Salesforce Knowledge reflecting this operating model;
- rich service and knowledge information inside CRM that is fragmented and weakly connected;
- customer-relevant information outside CRM in service areas and operational systems;
- dependence on other areas recognising a customer-service impact and manually informing CX;
- uneven Service Offering ↔ Knowledge relationships;
- unclear source authority, ownership and lifecycle.

**Core learning:** the problem is not simply content maintenance. The wider question is how the organisation recognises and connects what is true about a service, what has changed, and what context is relevant to an interaction.

### Shared discovery insight

```text
fragmented business context
        ↓
manual interpretation
        ↓
local workarounds / reconciliation
        ↓
uncertain ownership and trust
        ↓
inconsistent customer and staff experience
```

## 2D — Define

### Customer Accounts problem

> The City cannot reliably understand and maintain a trusted view of the customer and their account relationships because customer information is fragmented, duplicated, differently classified and constrained by current system and process models.

**Design question**

> What context do we need to understand the customer and their relationship with the City?

### Information Management problem

> Customer-relevant information is organised around internal systems and processes rather than a coherent business-context model. Inside CRM, service and knowledge context are fragmented; outside CRM, CX often depends on manual awareness and communication when operational changes affect customers.

**Design question**

> What context do we need to understand the service, what is currently true, and what has changed?

## Combined 2D conclusion

> **CX lacks a coherent way to connect trusted customer context with trusted service and operational context at the point where a customer interaction occurs.**

## How Might We

> **How might we connect the business context behind customers, services and operational changes so the right context can be recognised, trusted and used wherever a customer interaction occurs?**

This deliberately does not prescribe a new data platform, a master customer record, a knowledge platform, Salesforce redesign, enterprise integration architecture or AI.

## Handoff to 3D + 4D

The active work now lives in:

`jose-andr-cx-projects/business-context-architecture-develop-deliver`

That repo develops and tests the Business Context Architecture across:

- Customer Context;
- Service Context;
- Information Context;
- Operational Context;
- Interaction Context;
- Outcome Context.

## Repository role

This repository is now a **completed Discover + Define evidence base**.

Use it to:

- understand the current-state learning;
- trace evidence behind the problem frames;
- preserve assumptions and caveats;
- support stakeholder conversations;
- provide evidence for Business Context Architecture tests.

Do not use it to:

- continue future-state architecture design here;
- treat draft SOPs as approved policy;
- finish every process map before design proceeds;
- create a separate Information Management project.

## Navigation

### Synthesised outputs

- `01-discover/discovery-synthesis.md` — combined 1D learning.
- `02-define/combined-problem-frame.md` — two problem frames and shared HMW.
- `02-define/handoff-to-business-context-architecture.md` — explicit handoff into 3D + 4D.

### Supporting evidence

- `01-customer-data-and-systems-support/` — detailed Customer Accounts operational evidence.
- `02-customer-focus-information-support/` — detailed Information Management evidence.
- `03-cross-function-learning/` — shared patterns, governance gaps and capability signals.
- `00-project-control/` — assumptions, methods and scope history.
- `05-decisions/` — material discovery decisions.

The detailed SOP and template material is retained as evidence and working history. It no longer defines the purpose of the repository.
