# TDF Model Definition

## Definition

The **Top-Down Feasibility Decomposition Model (TDF Model)** is a formal model for feasibility analysis based on the **progressive decomposition of a project into functional units**, evaluated through successive feasibility phases.

The model applies a **top-down approach**, in which feasibility is first assessed at a high functional level and then refined through deeper levels of detail only when required.

The TDF Model defines:
- how a project is decomposed;
- how feasibility is evaluated at each level;
- how decisions are recorded and propagated across phases;
- under which conditions a project may proceed, be restructured, or be terminated.

---

## Core Concepts

The TDF Model is based on the following core concepts.

### Function

A **function** is a logical unit of capability required by the project.

A function:
- represents *what must be achieved*, not *how it is implemented*;
- is evaluable in terms of feasibility;
- may be decomposed into sub-functions if required.

Functions are **not tasks**, activities, or implementation steps.

---

### Functional Decomposition

**Functional decomposition** is the process of dividing a function into smaller, more specific sub-functions.

In the TDF Model:
- decomposition is **conditional**, not automatic;
- it is performed only when the current level of abstraction is insufficient to assess feasibility;
- it proceeds hierarchically, preserving parent–child relationships between functions.

The depth of decomposition is not predefined.

---

### Feasibility

**Feasibility** is the ability of a function to be realized within the constraints of the project context.

Feasibility may include, but is not limited to:
- technical feasibility;
- organizational feasibility;
- regulatory or structural constraints.

The TDF Model does not prescribe feasibility criteria; it provides a structure within which feasibility can be assessed.

---

### Feasibility Phase

A **feasibility phase** represents a distinct level of analysis applied to the current set of functions.

Each phase:
- evaluates feasibility based on the information available at that level;
- produces explicit outcomes for each function;
- may trigger further decomposition or decision-making.

Phases are sequential and cumulative:  
the outcome of a phase does not replace previous ones, but refines them.

---

## Feasibility Outcomes

For each function, at each feasibility phase, the TDF Model defines a limited and explicit set of outcomes.

Typical outcomes include:

- **Feasible**  
  The function is considered feasible at the current level of analysis.

- **To be decomposed**  
  The function requires further decomposition to assess feasibility adequately.

- **Not feasible**  
  The function cannot be realized under the given constraints.

Additional classifications may be applied to non-feasible functions, such as:
- substitutable;
- non-essential;
- blocking.

---

## Indispensability

Functions may be classified according to their importance to the project.

A function may be:
- **indispensable**, meaning the project cannot exist without it;
- **non-indispensable**, meaning the project may proceed without it;
- **substitutable**, meaning alternative approaches may exist.

If an **indispensable function** is assessed as **not feasible**, the TDF Model explicitly allows the project to be reconsidered or terminated.

---

## Decision Propagation

Decisions in the TDF Model propagate according to clear rules:

- feasibility outcomes at a given phase remain part of the decision record;
- further decomposition refines, but does not invalidate, previous outcomes;
- non-feasibility of an indispensable function has priority over all other considerations.

This ensures consistency and traceability across the entire analysis.

---

## Scope of the Model

The TDF Model defines:
- the structure of feasibility analysis;
- the logic of decomposition and decision-making.

It does not define:
- implementation techniques;
- project execution processes;
- governance or delivery frameworks.

These aspects are intentionally left outside the scope of the model.
