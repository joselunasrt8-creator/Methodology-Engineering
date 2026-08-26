# Methodology findings — MS-RE-RUN-002 handoff

**Record identity:** `ME-MS-RE-RUN-002-METHODOLOGY-001`
**Scope:** Friction and method behavior exposed by the handoff. These are separate from the `CA-001` finding and do not determine graph-theory truth [E-018].

| ID | Methodology finding | Evidence | Bounded implication |
| --- | --- | --- | --- |
| MF-001 | Immutable object binding worked well. Repository, commit, path, Git blob, and SHA-256 fields allowed exact intake without substituting a newer package. | E-003–E-006 | Future handoffs should retain layered repository/content identities. Successful binding does not validate content. |
| MF-002 | A prepared-undelivered source record needs a separate receiving event; mutating the source handoff would rewrite history. | E-007, E-018, E-019 | A cross-repository contract should pair sender preparation with append-only recipient receipt/acknowledgement records. |
| MF-003 | Semantic compression lost decision-relevant theorem detail. The linked chain retained the `max degree <= d` and `d + 1` statement, but the candidate sentence reduced it to unspecified “conditions” and “a guarantee.” | E-010, E-011, E-016 | Handoff checks should test whether exact premises, quantifiers, and consequents survive into the object being evaluated, not only whether links exist. |
| MF-004 | “Tractable” is overloaded across conceptual analysis and computational complexity. | E-010, E-015, E-016 | Candidate vocabularies need interpretation rules or prohibited readings where a term can invert the evidence relation. |
| MF-005 | The request suggested comparison sources but did not specify an admission or precedence rule. | E-008, E-020 | Candidate Evaluation Requests should declare how external comparison evidence will be identified, admitted, version-bound, and weighed. |
| MF-006 | Context gaps were listed but not assigned question-specific materiality. | E-006, E-012, E-017 | Handoffs should state which conclusions each visual/inaudible gap blocks, limits, or leaves materially unaffected. |
| MF-007 | Unknown recipient fields prevented upstream delivery, even though the candidate package was otherwise complete. | E-007–E-009, E-012 | Recipient identity, custody terms, and acknowledgement mechanism should be completion gates for a delivered handoff, while prepared state remains valid separately. |
| MF-008 | The upstream source/observation/pattern/candidate distinctions made a non-validating evaluation possible. | E-006, E-009–E-012 | Preserve typed layers and confidence/limitations through transfer. Do not collapse successful traceability into evidentiary sufficiency. |
| MF-009 | The current outcome vocabulary can express a supported core with a material wording defect without declaring the candidate false. | E-001, E-010, E-013–E-016 | `CANDIDATE_REQUIRES_REVISION` is useful only if successor ownership and no-retroactive-edit rules remain explicit. |

## Failure conditions exposed

- Intake must stop if repository, commit, execution, transcript, request, handoff, cognition, or candidate identity cannot bind exactly [E-001, E-003–E-010].
- Candidate support must fail closed when a material ambiguous term needs favorable interpretation [E-010, E-015].
- Transfer claims must remain unsupported when the evidence set contains only dependent passages from one pedagogical source [E-011, E-020].
- Delivery must not be inferred from artifact existence or later evaluation [E-007, E-018, E-019].
- Methodology findings must not be converted into candidate validation, authority, legitimacy, readiness, or eligibility [E-018].

## Suggested owner boundaries

MindShift alone may decide whether to create a linked successor to `CA-001`; this package supplies a revision-required evaluation but no mutation permission [E-010, E-018]. Methodology Engineering may use MF-001–MF-009 as bounded calibration input under its own governance. Architectural Boundary Research may review the boundary and transfer mechanics if separately authorized; that review would not validate the candidate. Continufy registration is not supported by this package [E-018, E-019, E-020].
