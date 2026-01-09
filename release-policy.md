# TDF Model – Release Policy

This document defines the official **release policy** of the  
**Top-Down Feasibility Decomposition Model (TDF Model)**.

The purpose of this policy is to ensure:
- a clear separation between work-in-progress and declared versions;
- consistency across the Git repository, documentation, and official PDFs;
- long-term traceability and citability of public releases.

---

## Fundamental Distinction

Within the TDF Model, three distinct levels must be clearly separated:

- **Git commits**: represent ongoing work and intermediate changes;
- **Git tags**: declare a public release;
- **Model version**: identifies a stable, citable state of the TDF Model.

Git commits **do not** represent versions of the model.

---

## TDF Model Versioning

The TDF Model follows **Semantic Versioning**, using the format:

```MAJOR.MINOR.PATCH```


The meaning of each component is defined as follows:

### MAJOR
Incremented only when significant **conceptual changes** are introduced,
such as modifications to core principles, overall structure, or decision logic.

### MINOR
Incremented when **compatible extensions** are added, including:
- new methodological sections;
- new application profiles;
- coherent extensions of the existing model.

### PATCH
Incremented for **editorial-level changes**, such as:
- textual clarifications;
- corrections and refinements;
- adjustments that do not alter the functioning of the model.

---

## When to Create a Release

A TDF Model release is created **only** when one or more of the following applies:

- a stable state of the model is publicly declared;
- the content is intended to be citable;
- an official PDF is generated;
- the version is published with or linked to a DOI.

Releases are **not** created for:
- individual commits;
- intermediate drafts;
- internal reorganizations or work-in-progress changes.

---

## Git Tag Usage

Each official release of the TDF Model is associated with a **Git tag** using the format:

```vMAJOR.MINOR.PATCH```


Examples:
- v1.0.0
- v1.1.0
- v1.1.1
- v2.0.0

The tag identifies **exactly** the commit that represents the declared version of the model.

---

## Mandatory Alignment

At the time of creating a release, the following elements **must be aligned**:

- Git tag (e.g. `v1.0.0`);
- the `version` field in `CITATION.cff`;
- the name and content of the official PDF;
- any publication on Zenodo or similar platforms.

A version that is not fully aligned **is not considered official**.

---

## Intermediate Work

During drafting and development:

- commits may be frequent;
- the model version **must not be changed**;
- no Git tags are created.

The model version is updated **only** at release time.

---

## Example Version Evolution

- **v1.0.0**  
  First official public release of the TDF Model.

- **v1.1.0**  
  Introduction of new application profiles.

- **v1.1.1**  
  Editorial clarifications and corrections.

- **v2.0.0**  
  Conceptual revision of the model.

---

## Guiding Principle

The TDF Model adopts a **conservative release strategy**:

> *Fewer declared and solid versions  
> are preferable to many unstable or ambiguous ones.*

This policy protects:
- authorship;
- citability;
- long-term methodological clarity.
