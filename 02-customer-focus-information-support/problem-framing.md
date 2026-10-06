# Information Management — 2D Problem Frame

**Status:** Working problem frame — sufficient to enter 3D  
**Owner:** José Andrade  
**Last updated:** 6 October 2026  
**Evidence maturity:** Partial. Based on current-state SOP material, operational knowledge and observed examples. Further evidence should refine rather than block 3D.

## Problem

Customer information management has evolved around an internally focused Contact Centre operating model.

Historically, service information has been manually interpreted and refined into guidance that helps phone agents handle enquiries. Salesforce Knowledge was configured to support this model, so much of the information is procedural and internally focused rather than structured as reusable business context.

Rich information exists inside CRM, but relationships between customers, services, knowledge, interactions and outcomes are fragmented.

A large amount of customer-relevant information also exists outside CRM in service areas, operational systems, processes and local knowledge. CX often relies on those areas recognising that a change matters to customers and manually communicating it.

This means Customer Experience does not have a reliable business-context layer connecting:

- who the customer is;
- which service or Service Offering is involved;
- what rules, requirements or knowledge apply;
- what is happening operationally;
- what has changed;
- which interactions or channels are affected.

The result is manual interpretation, delayed awareness, inconsistent responses and weak reuse across channels, digital services and AI.

## What the problem is not

The problem is not simply:

- outdated articles;
- duplicated content;
- poor search;
- a missing knowledge platform;
- insufficient integration.

Those may be symptoms or enabling issues.

The underlying problem is that business meaning is fragmented across systems, content and organisational boundaries.

## Current-state model

```text
Something changes in the organisation
        ↓
another area recognises customer-service significance
        ↓
manual communication to CX / Contact Centre
        ↓
information is interpreted and refined
        ↓
Salesforce Knowledge / staff guidance / local communication
        ↓
agent uses the information during an interaction
```

This model depends heavily on manual awareness, interpretation and distribution.

## Three dimensions of the problem

### 1. Internally focused knowledge model

Much existing knowledge answers:

> What should the Contact Centre agent do?

The future business-context model also needs to represent:

> What is true about this service, customer situation, requirement or operational event?

That business meaning should be reusable across different representations and channels.

### 2. Fragmented context inside CRM

CRM contains potentially useful relationships between:

- Customer;
- Account;
- Service / Service Offering;
- Case;
- Interaction;
- Knowledge;
- Outcome.

These relationships are not yet treated as one coherent business-context model.

The Service Offering ↔ Knowledge example shows that one article may support multiple services, one service may rely on several articles, and some services may have no linked article. The relationship exists operationally but is not consistently governed as a business relationship.

### 3. Relevant context outside CRM

Operational reality often changes outside CX and outside CRM.

The customer-service impact may only become visible when another area tells CX.

This creates an observability and stewardship problem: CX lacks a reliable way to connect relevant operational change to the services, customers and interactions it affects.

## How Might We

> **How might we connect the business context behind customers, services and operational changes so the right information can be recognised, trusted and reused wherever a customer interaction occurs?**

## Relationship to Customer Account Management

Customer Account Management asks:

> What context do we need to understand the customer and their relationship with the City?

Information Management asks:

> What context do we need to understand the service, what is currently true, and what has changed?

From 3D onward these are not separate projects.

They are two design lenses inside the **Business Context Architecture**.

## 2D outcome

Information Management is sufficiently framed to enter 3D.

Additional discovery should now be targeted at testing the architecture rather than attempting to complete every possible SOP first.

Priority evidence should include:

- real operational changes that required manual notification to CX;
- Service Offering ↔ Knowledge relationships;
- examples where business meaning is represented differently across systems or channels;
- examples where ownership or source authority is unclear;
- examples where missing context causes customer or staff effort.
