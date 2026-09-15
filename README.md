# Methodology Engineering

> **Status:** Minimum Methodology-Engineering Contract v0.1  
> **Validation status:** Candidate engineering discipline with bounded reference specializations; general cross-domain value not yet established

## Purpose

Methodology Engineering develops explicit, versioned definitions for methodologies: the object types, transformation contracts, evidence requirements, verification rules, provenance, uncertainty, lifecycle, and failure semantics under which a class of executions may be performed and evaluated.

Its current governing question is:

> **Can methodology definitions be engineered as explicit reusable objects in a way that improves reproducibility, traceability, controlled evolution, or evaluation compared with strong domain-native methodology practices?**

The repository proposes a formal answer. It does not yet establish that this representation is necessary, minimal, superior, or transferable across methodology domains.

```text
Methodology definition ≠ execution
Contract completeness ≠ scientific validity
Verification ≠ scientific warrant
Reusable vocabulary ≠ proven cross-domain discipline
More structure ≠ better methodology by default
```

Research methodology is the first reference specialization.

## Core candidate model

The repository's central candidate determination is:

> **A methodology can be represented as a normative object-transformation system.**

Under this model, a methodology declares which object types exist, which transformations are admissible, what inputs/evidence they require, what outputs they produce, what invariants and uncertainty must be preserved, how results are verified, and how failure/provenance are recorded.

This is a modeling and engineering proposition. Whether every useful methodology should be represented this way is an empirical question.

```text
Objects
    ↓ governed by
Methodology definition
    ↓ instantiated by
Execution
    ↓ produces
Concrete objects / evidence
    ↓ evaluated by
Declared verification
```

## Canonical contract

The **Minimum Methodology-Engineering Contract v0.1** is maintained in [METHODOLOGY_ENGINEERING_CANON.md](METHODOLOGY_ENGINEERING_CANON.md).

It defines the repository's current candidate contract for methodology identity, object definitions, transformation contracts, lifecycle, instrument lifecycle, provenance, verification, failure, versioning, and supersession.

The contract is normative within this repository version. It is not evidence that the contract is complete or optimal for external methodology domains.

## Reference specialization

Research methodology is the first bounded specialization. It may define types such as:

- Research Request;
- Investigation Protocol;
- Observation Record;
- Evidence Item;
- Instrument;
- Calibration Record;
- Collection Run;
- Analysis/Transformation Record;
- Decision Record;
- Finding;
- Replication Attempt;
- Verification Result; and
- Publication Record.

These are type definitions. A specific investigation produces concrete instances.

The repository also contains named contracts such as the **Cross-Domain Structology Transfer Audit v0.1** and residual conformance/evidence lifecycle contracts. Their presence demonstrates that the generic framework can be specialized on paper; it does not establish that those specializations are empirically valid or useful until executed and evaluated independently.

## Methodology versus execution

```text
Object Type ≠ Object Instance
Methodology ≠ Execution
Transformation Contract ≠ Transformation Event
Transformation ≠ Verification
Verification ≠ Scientific Warrant
Evidence ≠ Decision
Publication ≠ Canonical Evidence
```

Methodology Engineering owns reusable definitions. Execution repositories own concrete transformation events, observations, evidence, deviations, and outcomes.

A complete-looking methodology definition is therefore not evidence that the methodology works.

## What must be measured

Claims that Methodology Engineering improves research or other methodology domains require operational outcomes. Depending on the domain, useful measures may include:

- reproducibility or replication success;
- protocol ambiguity detected before execution;
- undocumented deviations;
- provenance completeness;
- evaluator agreement;
- missing-data handling;
- time/cost to define and execute a methodology;
- defect or amendment rate;
- ability to reproduce an analysis from frozen artifacts;
- transfer to a second independent methodology domain; and
- downstream decision quality where an appropriate ground truth exists.

No single metric establishes general methodology quality.

## Evidence currently supported

The repository currently supports bounded claims that:

- a methodology can be documented using the proposed object/transformation vocabulary;
- reusable methodology contracts can be versioned separately from executions;
- research methodology can be expressed as a reference specialization;
- named instruments/contracts can be defined without performing their executions; and
- methodology-definition artifacts can preserve explicit distinctions, provenance requirements, failure semantics, and lifecycle rules.

These are representation and engineering-mechanism claims.

## Claims not yet established

The repository does not currently establish that:

- methodology engineering is a distinct general discipline rather than a useful documentation architecture;
- the Minimum Contract contains the minimum necessary fields;
- the proposed object model is superior to preregistration templates, workflow specifications, scientific workflow systems, protocol standards, or domain-native methods;
- formalized transformation contracts increase reproducibility;
- additional structure reduces scientific error;
- the framework transfers naturally beyond research methodology;
- external researchers or engineers will adopt or retain it;
- the framework improves decision quality; or
- the complexity introduced is justified by measurable benefit.

## Relationship to Structology

Structology supplies a provisional candidate structural vocabulary. Methodology Engineering may specialize concepts from it, but Structology is itself unvalidated.

Therefore:

```text
Structology candidate concept
        ↓ specialization
Methodology Engineering concept
```

does not imply:

```text
Structology validated
or
Methodology Engineering validated
```

Methodology Engineering should remain intelligible and testable on its own. If Structology concepts are later rejected or revised, methodology-engineering evidence should remain interpretable through versioned provenance rather than being retroactively invalidated by ecosystem dependency.

## Relationship to research execution

A methodology definition specifies reusable contracts. A research execution instantiates those contracts against concrete questions, sources, observations, and evidence.

```text
Methodology definition
        ↓
Frozen investigation protocol
        ↓
Concrete execution
        ↓
Evidence / analysis / finding
```

The execution may reveal that the methodology definition was incomplete or harmful. Such a result should be recorded as evidence for revision, not silently repaired in the historical methodology version.

## Relationship to the Continufy ecosystem

The repositories have separable responsibilities. A useful current map is:

```text
MindShift              candidate cognition / research questions
Structology            candidate general structural vocabulary
Methodology Engineering reusable methodology/instrument contracts
ABR                    empirical investigation and evidence
Structural Foundations bounded formal theory
SYNAPSE                deterministic structural analysis
ContinuityOS           legitimacy / execution-boundary mechanisms
```

No arrow in the ecosystem creates scientific validity, authority, or a mandatory dependency. Each handoff must justify the semantics of the artifact being consumed.

## Evaluation program

The highest-value next work is comparative execution rather than further expansion of the generic contract.

Priority experiments are:

1. **Research-method baseline comparison** — run the same bounded investigation using the Methodology Engineering representation and a strong conventional preregistration/protocol baseline.
2. **Prospective defect detection** — measure whether explicit transformation contracts catch ambiguities, missing inputs, or invalid transitions before execution.
3. **Reproduction test** — give frozen artifacts to an independent executor and measure whether they can reproduce the declared transformation/results.
4. **Amendment discipline** — introduce an unexpected condition and compare how clearly each approach records deviations, amendments, and claim changes.
5. **Second-domain transfer** — specialize the frozen generic contract to a non-research methodology domain without changing foundational meanings after seeing the domain.
6. **Complexity accounting** — measure authoring time, execution overhead, artifact volume, and reviewer burden against any observed benefit.

Each experiment should prospectively define the comparator, outcome measures, stopping rules, evidence identities, and permitted claims.

## Falsification boundary

Methodology Engineering should be narrowed, simplified, or rejected as a general discipline if evidence shows that:

- strong existing methodology practices achieve equivalent outcomes with less complexity;
- the object/transformation representation does not improve reproducibility or traceability;
- the framework creates documentation burden without consequential benefit;
- independent executors cannot use the contracts consistently;
- foundational meanings must change materially across domains;
- research-specific concepts were incorrectly generalized as methodology primitives; or
- observed improvements are attributable only to additional documentation effort rather than the proposed architecture.

Negative results are valid methodology-engineering evidence.

## Scope

This repository owns:

- methodology object models;
- methodology lifecycle engineering;
- transformation-contract definitions;
- methodology specialization rules;
- scientific instrument definitions;
- evidence/admissibility planning abstractions;
- verification/conformance definitions;
- provenance, traceability, uncertainty, failure, deviation, withdrawal, and supersession semantics; and
- reusable contracts that remain separate from concrete executions.

## Non-scope

This repository does not:

- conduct empirical studies;
- execute methodologies;
- contain investigation-specific evidence as canonical methodology evidence;
- authorize scientific claims;
- grant execution authority;
- establish formal domain theory;
- implement deterministic structural-analysis engines;
- mutate external systems;
- prove Structology;
- prove its own generality through internal specialization; or
- treat contract conformance as proof of scientific truth.

## Current conclusion

Methodology Engineering now contains a substantial candidate architecture for treating methodology definitions as explicit, reusable, versioned transformation systems. Its strongest supported claim is that this representation can be specified coherently and specialized into research-method contracts.

The next claim to earn is consequential value: whether the architecture measurably improves reproducibility, traceability, defect detection, controlled evolution, or transfer relative to strong simpler baselines.
