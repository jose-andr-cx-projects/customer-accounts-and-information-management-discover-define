# Customer Focus Information Support

**Status:** Current-state evidence retained; 2D problem framed sufficiently for progression  
**Owner:** José Andrade  
**Last updated:** 6 October 2026

## Purpose

This folder preserves current-state evidence about the Customer Focus Information Support function and the wider Information Management problem it reveals.

It remains an evidence source. It is **not** the active future-state design project.

The active design from 3D onward sits in the Business Context Architecture work carried in the `customer-account-management` repository.

## What this current-state work revealed

The original function has been strongly shaped by an internally focused Contact Centre operating model.

Much of the information-management activity is concerned with:

- refining service information into guidance for phone agents;
- maintaining Service Directory and customer-service tools;
- supporting urgent or hot-topic responses;
- communicating changes to staff;
- resolving unclear, outdated or conflicting information;
- manually coordinating across teams and systems.

Salesforce Knowledge reflects this operating model. It contains useful information, but much of it is procedural, internally focused and only partially connected to the underlying customer, service and operational context.

The problem also extends beyond CRM. Customer-relevant information is created and changed across service areas and operational systems, and CX may depend on those areas recognising that a change matters and manually communicating it.

## 2D problem frame

The working problem frame is:

`problem-framing.md`

It asks:

> **How might we connect the business context behind customers, services and operational changes so the right information can be recognised, trusted and reused wherever a customer interaction occurs?**

This problem frame is considered sufficient to enter 3D while further evidence is gathered through targeted testing.

## Relationship to Business Context Architecture

From 3D onward, Information Management is not a separate project.

It is one of two design lenses inside the same Business Context Architecture:

```text
Customer Account Management
trusted customer + relationship context
                \
                 \
                  BUSINESS CONTEXT ARCHITECTURE
                 /
                /
Information Management
trusted service + operational context
```

Information Management specifically contributes questions about:

- Service / Service Offering;
- service rules and requirements;
- knowledge and guidance;
- operational state and change;
- source versus representation;
- ownership;
- lifecycle;
- reuse;
- how CX becomes aware when customer-relevant context changes outside CRM.

## Current-state focus retained here

This folder continues to preserve evidence about:

- Service Directory content;
- customer-service tool maintenance;
- CRM user support;
- telephone messages on hold;
- hot-topic response coordination;
- urgent staff communications;
- Service Directory editor support;
- first-contact-resolution content;
- systems, tools, decision points, exceptions, risks and quality controls.

These materials should be strengthened only when they help test or refine the Business Context Architecture. There is no requirement to complete every draft SOP before 3D proceeds.

## Evidence boundary

Draft SOPs and hypotheses remain draft until validated.

Do not treat the content in this folder as:

- approved operational policy;
- a complete future operating model;
- evidence that every listed activity occurs consistently;
- a technology recommendation.

## Next use

Use this repository selectively to supply evidence for 3D and 4D tests, especially:

1. Service Offering ↔ Knowledge relationships;
2. changes originating outside CRM;
3. unclear source or ownership;
4. duplicated or differently represented business meaning;
5. manual communication dependencies;
6. gaps that create customer or staff effort.
