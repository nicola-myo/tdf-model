# Top-Down Feasibility Decomposition Model (TDF Model)

The **Top-Down Feasibility Decomposition Model (TDF Model)** is a structured method for **early feasibility analysis** of complex projects.

It is based on a **top-down, progressive functional decomposition** approach, combined with explicit feasibility checkpoints and formal decision points.  
The model is designed to support **early, rational decision-making**, including the possibility of **early project termination** when critical requirements are not feasible.

---

## Purpose of the Model

The TDF Model addresses a common problem in complex initiatives:

> Projects often fail not because they are poorly executed,  
> but because they should never have started.

The model provides a structured way to:
- assess feasibility before detailed design or planning;
- distinguish indispensable functions from optional ones;
- identify non-feasible critical requirements early;
- avoid late-stage failure and unnecessary investment.

---

## Core Principles

The TDF Model is based on the following principles:

- **Top-down analysis**  
  Feasibility is evaluated starting from high-level functions and progressively refined only where necessary.

- **Progressive decomposition**  
  Functions are decomposed into sub-functions only when required to assess feasibility.

- **Explicit decision points**  
  Each phase produces clear outcomes (feasible, to be decomposed, not feasible).

- **Early termination**  
  If an indispensable function is not feasible, the model explicitly allows the project to be reconsidered or stopped.

- **Decision traceability**  
  Feasibility outcomes are recorded per phase, preserving the decision history.

---

## What the TDF Model Is (and Is Not)

### The TDF Model **is**:
- a feasibility analysis model;
- a decision-support method;
- a pre-project or early-project evaluation tool.

### The TDF Model **is not**:
- a project management framework;
- a delivery methodology;
- a task planning or scheduling tool.

---

## Documentation

The formal definition of the TDF Model is provided in the `docs/` directory:

- [Introduction](docs/en/00-introduction.md)
- [TDF Model Definition](docs/en/01-tdf-model-definition.md)
- [Principles and Rationale](docs/en/02-principles-and-rationale.md)
- [Phases and Decision Logic](docs/en/03-phases-and-decision-logic.md)
- [Comparison with Related Methods](docs/en/04-comparison-with-related-methods.md)
- [Limitations and Scope](docs/en/05-limitations-and-scope.md)

---

## Structure of This Repository

This repository represents the **canonical source** of the TDF Model.

```
tdf-model/
│
├─ README.md # Overview and entry point
├─ LICENSE # Creative Commons Attribution 4.0
├─ CITATION.cff # Citation metadata
│
├─ docs/ # Formal definition of the model
│
├─ profiles/ # Domain-specific application profiles
│
├─ releases/ # Official PDF releases
│
└─ CHANGELOG.md # Public change history
```


---

## Application Profiles

The TDF Model is **domain-independent**.  
Specific contexts are addressed through **Application Profiles**, which apply the model to a defined domain while preserving its core principles.

Examples include:
- ERP migration feasibility
- Cybersecurity feasibility for commercial organizations
- Infrastructure modernization initiatives

Each profile is documented separately and explicitly marked as *TDF-based*.

---

## Versioning and Releases

The TDF Model follows a **conservative release policy** based on Semantic Versioning:

```MAJOR.MINOR.PATCH```


- Versions are declared only through **Git tags**
- Commits represent work-in-progress, not published versions
- Each release corresponds to a stable, citable state of the model

Details are documented in:
- `release-policy.md`

---

## Language Policy

The English version of this documentation is the authoritative source of the TDF Model.

All other language versions are provided as translations for accessibility purposes.
In case of discrepancies, the English version shall prevail.

---

## License

This work is licensed under the  
**Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to use, adapt, and redistribute the TDF Model,  
**provided that proper attribution is given**.

See the `LICENSE` file for details.

---

## How to Cite

If you use the TDF Model in documentation, research, or professional work, please cite it as specified in the `CITATION.cff` file.

GitHub and Zenodo automatically generate citation formats based on this file.

---

## Authorship

The TDF Model is authored and maintained by **myobject srls**.

This repository represents the original and authoritative source of the model.
