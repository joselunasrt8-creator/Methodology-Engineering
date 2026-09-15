# Methodology Engineering

> **Status:** Minimum Methodology-Engineering Contract v0.1

## Purpose

This repository develops principles, object models, transformation contracts, and scientific instruments for engineering reproducible methodologies.

Its central determination is:

> **A methodology is a normative object transformation system.**

A methodology defines which objects exist, how they may be transformed, what evidence and rules each transformation requires, how outputs are verified, and how provenance, uncertainty, and failure are preserved.

Research methodology is the first reference specialization developed within this repository.

This repository **defines methodologies; it does not execute them, grant authority, or make downstream decisions.**

```text
Methodology definition
        ≠
Methodology execution
        ≠
Scientific warrant
        ≠
Execution authority
```

## What is Methodology Engineering?

Methodology Engineering is the discipline of designing, validating, and evolving methodologies that systematically transform complex reality into reproducible evidence, validated understanding, and better decisions.

It provides object models, transformation contracts, scientific instruments, lifecycle rules, and verification principles without collapsing methodology definition into methodology execution.

## Governing Question

> **How should methodologies be engineered to systematically transform complex reality into reproducible evidence, validated understanding, and better decisions?**

## Canonical Methodology-Engineering Contract

The **Minimum Methodology-Engineering Contract v0.1** is maintained in [Methodology Engineering Canon](METHODOLOGY_ENGINEERING_CANON.md).

The contract describes how reusable methodologies and scientific instruments are defined, versioned, reviewed, calibrated, improved, and superseded without executing a particular study.

The **Cross-Domain Structology Transfer Audit v0.1** is a bounded reference specialization maintained in [Cross-Domain Structology Transfer Audit v0.1](CROSS_DOMAIN_STRUCTOLOGY_TRANSFER_AUDIT_V0_1.md). It defines an audit methodology; it does not execute the audit or produce empirical findings.

Residual methodology-conformance outcomes and reconciliation semantics are defined in the [Residual Conformance, Negative Capability, and Reconciliation Contract v1.0](RESIDUAL_CONFORMANCE_NEGATIVE_CAPABILITY_AND_RECONCILIATION_CONTRACT_V1_0.md). Generic evidence lifecycle semantics are defined in the [Residual Generic Evidence Lifecycle and Conformance Contract v1.0](RESIDUAL_GENERIC_EVIDENCE_LIFECYCLE_AND_CONFORMANCE_CONTRACT_V1_0.md).

Neither contract authorizes execution, repair, synchronization, or scientific claims.

## General Model

```text
Complex Reality
        ↓
Objects
        ↓
Methodology
Defines valid transformations
        ↓
Execution
Applies transformations
        ↓
Evidence
        ↓
Understanding
        ↓
Decision
```

This is a methodology model, not a claim that every real system or Continufy workflow must instantiate every stage as a separate repository or service.

## Object, Methodology, and Execution

```text
Object ≠ Execution
Methodology ≠ Execution
Transformation Contract ≠ Transformation Event
```

An object represents a bounded state or artifact. Execution is an activity or event that creates, consumes, or transforms concrete object instances. Methodology Engineering defines the transformation contract; another environment performs the transformation.

## Research Transformation Contract

Every valid research transformation should define:

```text
Research Transformation {
  source object type
  admissible source state
  required inputs
  governing rule
  operation
  target object type
  resulting state
  preserved invariants
  permitted changes
  verification
  provenance
  uncertainty
  failure modes
  responsible roles
}
```

A transformation is valid only when its required inputs exist, its governing rule applies, its provenance resolves, its uncertainty is preserved, and its output satisfies the declared contract.

## First-Class Methodology Objects

Every first-class methodology object should have a consistent shape:

```text
Methodology Object {
  identity
  type
  purpose
  inputs
  outputs
  lifecycle
  relationships
  version
  provenance
  uncertainty
  verification
  failure state
}
```

Research-specific object types may include Research Request, Investigation Protocol, Observation Record, Evidence Item, Instrument, Calibration Record, Collection Run, Transformation or Analysis Record, Decision Record, Finding, Replication Attempt, Verification Result, and Publication Record.

These are type definitions. A specific investigation produces concrete instances.

## Current Scope

- methodology object systems and lifecycle engineering;
- transformation contracts and specialization;
- scientific instrument design;
- research-object definitions;
- evidence planning and admissibility;
- observation, derivation, measurement, and analysis boundaries;
- decision-rule definitions and adjudication contracts;
- calibration, replication, verification, provenance, and traceability;
- missingness, uncertainty, failure, deviation, withdrawal, and supersession semantics.

## Non-Scope

This repository does not contain or own:

- empirical study executions;
- investigation-specific evidence;
- domain-specific execution results;
- runtime methodology compilers;
- deterministic structural-analysis engines;
- operational execution systems;
- authority to accept scientific claims;
- execution legitimacy;
- runtime object mutation; or
- modifications to another repository's canonical definitions.

Those artifacts remain with their respective producers and executions.

## Relationship to Structology and Research Execution

Structology may provide domain-neutral structural primitives that Methodology Engineering can specialize into methodology and instrument contracts. Architectural Boundary Research may execute compatible methodology definitions and produce concrete evidence.

Those are **possible producer/consumer relationships**, not mandatory runtime dependencies.

```text
Structology primitives
        ↓ optional specialization
Methodology definition
        ↓ optional adoption
Empirical execution
        ↓
Evidence
```

A methodology remains meaningful as a definition even when a particular investigation does not adopt it. Likewise, an investigation can test whether a proposed methodology actually improves reproducibility, evidence quality, or decision quality.

## Relationship to the Continufy Ecosystem

Methodology Engineering is a reusable definition layer within the broader Continufy research ecosystem. It is **not a mandatory stage in a fixed Continufy production pipeline**.

Candidate relationships with Structology, MindShift, Architectural Boundary Research, Structural Analysis Foundations, SYNAPSE, ContinuityOS, or other repositories must be justified independently.

Possible evidence-supported outcomes include:

- another repository adopts a Methodology Engineering contract directly;
- only selected object or transformation definitions are reused;
- a domain-specific methodology remains local to its execution repository;
- an existing methodology is simpler than the generic contract;
- the proposed cross-repository handoff adds no measurable value; or
- Methodology Engineering is absent from a production execution path entirely.

```text
Research relationship ≠ runtime dependency
Definition compatibility ≠ architectural necessity
Methodology conformance ≠ scientific warrant
Methodology conformance ≠ execution authority
```

ContinuityOS, where used, concerns legitimacy of mutation-capable execution. Methodology Engineering does not supply that legitimacy.

## Boundary Principles

```text
Methodology ≠ Execution
Object Type ≠ Object Instance
Analyst Activity ≠ Object Transformation
Transformation ≠ Verification
Verification ≠ Scientific Warrant
Evidence ≠ Decision
Publication ≠ Canonical Evidence
Capability ≠ Permission
```

This repository defines how reproducible methodologies may be structured. It does not conduct, formalize, implement, operationalize, or authorize domain executions itself.

## Evidence Boundary

Repository coherence and conformance can show that a methodology definition is internally specified and testable. They do not establish that the methodology:

- improves scientific outcomes;
- improves engineering decisions;
- is required by another Continufy component;
- generalizes across domains;
- reduces cost or risk;
- has external adoption value; or
- has commercial value.

Those are empirical questions.

A useful falsification question is:

> Does applying the Methodology Engineering contract produce measurably better reproducibility, evidence quality, or decision quality than a strong simpler baseline?

## Current Status

This repository defines the architectural boundary for Methodology Engineering while the discipline continues to emerge through reference specializations and active investigations.

Research methodology is the first reference specialization. Additional methodology domains should be introduced only when reusable methodology-engineering patterns are supported by repeated execution evidence.

Content should be promoted here only when it is reusable across multiple methodology or research domains and no longer belongs exclusively to `architecturalboundary-research` or another domain-specific repository.

## Historical Methodology Completeness Audit

`METHODOLOGY_COMPLETENESS_AUDIT.md` records an assessment performed on 2026-07-17 against repository baseline `f1a3b3e`. Its findings are preserved as historical audit evidence and are not the current repository completeness determination.

## Visual Overview

The diagrams under `assets/slides/` are explanatory or candidate models. In particular, any diagram depicting a Continufy research pipeline does not establish that the depicted topology is mandatory, optimal, or production-valid.

![Research Methodology](assets/slides/slide-01-research-methodology.png?raw=1)

![Methodology Lifecycle](assets/slides/slide-02-methodology-lifecycle.png?raw=1)

![Why Methodology Engineering Matters](assets/slides/slide-03-why-methodology-matters.png?raw=1)

![Candidate Continufy Research Topology](assets/slides/slide-04-research-pipeline.png?raw=1)

![Long-Term Vision](assets/slides/slide-05-long-term-vision.png?raw=1)
