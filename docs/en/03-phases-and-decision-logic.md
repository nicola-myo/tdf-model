# Phases and Decision Logic

This document defines how **feasibility phases** and **decision logic** operate within the
Top-Down Feasibility Decomposition Model (TDF Model).

The purpose of this section is to formalize:
- the role of phases;
- the reason for phase separation;
- the logic governing feasibility outcomes;
- the rules by which decisions propagate across phases.

---

## Feasibility Phases

A **feasibility phase** represents a distinct level of analysis applied to a defined set of functions.

Each phase:
- operates on a specific level of functional granularity;
- evaluates feasibility using the information available at that level;
- produces explicit and recorded outcomes;
- may trigger further decomposition or decision-making.

Phases are **sequential**, but their outcomes are **cumulative**.

---

## Rationale for Multiple Phases

The TDF Model deliberately uses **multiple feasibility phases** rather than a single consolidated feasibility outcome.

The reason is structural:

> Feasibility conclusions reached at different levels of abstraction are not equivalent.

A feasibility assessment performed at a high functional level answers a different question than one performed at a detailed level.  
Collapsing these assessments into a single outcome would eliminate critical contextual information.

Each phase therefore captures a **decision made with a specific level of knowledge**, preserving its validity and limitations.

---

## Phase Separation and Traceability

In the TDF Model, feasibility outcomes are **not overwritten**.

Instead:
- each phase adds a new layer of evaluation;
- previous outcomes remain visible and valid within their original context;
- later phases refine, but do not negate, earlier decisions.

This approach ensures **decision traceability**, allowing observers to reconstruct:
- when a decision was made;
- at which level of detail;
- based on which assumptions.

---

## Typical Phase Progression

While the number of phases is not fixed, a typical progression includes:

### Phase 1 – High-Level Feasibility
- Functions are defined at a coarse, functional level.
- The goal is to determine whether the project is conceptually viable.
- Outcomes often include *to be decomposed* decisions.

### Phase 2 – Intermediate Feasibility
- Functions are evaluated at a more detailed level.
- Structural and organizational constraints become clearer.
- Non-feasible indispensable functions may emerge.

### Phase 3 – Detailed Feasibility
- Analysis focuses on fine-grained sub-functions.
- Remaining feasibility uncertainty is resolved.
- The project either stabilizes or reaches a definitive stopping point.

Additional phases may be introduced if justified by complexity or risk.

---

## Feasibility Outcomes per Phase

At each phase, every function receives a feasibility outcome.

The outcome set is intentionally limited to ensure clarity.

### Core Outcomes

- **Feasible**  
  The function is considered feasible at the current phase.

- **To Be Decomposed**  
  The function cannot be reliably assessed at the current level and requires further decomposition.

- **Not Feasible**  
  The function cannot be realized under the given constraints.

---

## Indispensability and Blocking Conditions

Feasibility outcomes are interpreted in conjunction with **function importance**.

If a function classified as **indispensable** is assessed as **not feasible**, the TDF Model defines this as a **blocking condition**.

Blocking conditions:
- take precedence over all other outcomes;
- trigger mandatory reconsideration of the project;
- may lead to restructuring or termination.

This rule is intentionally strict and non-negotiable.

---

## Decision Propagation Rules

The TDF Model applies explicit rules to propagate decisions across phases:

1. A function marked as **feasible** in a given phase does not require further decomposition unless new uncertainty emerges.
2. A function marked as **to be decomposed** must appear in the next phase at a finer level of granularity.
3. A **not feasible** outcome for a non-indispensable function does not block the project but must be explicitly addressed.
4. A **not feasible** outcome for an indispensable function constitutes a blocking condition.

These rules ensure consistent and predictable decision behavior.

---

## Phase Columns and Analytical Structure

In practical applications, feasibility phases are often represented as **separate columns** within an analysis table.

Each column corresponds to:
- one feasibility phase;
- one decision context;
- one level of functional detail.

This structure prevents later assessments from obscuring earlier conclusions and reinforces decision traceability.

---

## Termination Logic

The TDF Model explicitly allows feasibility analysis to terminate before all functions are decomposed.

Termination may occur when:
- all indispensable functions are feasible;
- remaining uncertainty is acceptable;
- or a blocking condition is encountered.

Termination is considered a **valid analytical outcome**, not a failure.

---

## Summary

The phase-based decision logic of the TDF Model ensures that:

- feasibility is assessed progressively and transparently;
- decisions are tied to specific levels of knowledge;
- critical constraints are identified early;
- the rationale behind outcomes remains visible and defensible.

By separating phases and preserving their outcomes, the TDF Model transforms feasibility analysis from a single judgment into a structured decision process.
