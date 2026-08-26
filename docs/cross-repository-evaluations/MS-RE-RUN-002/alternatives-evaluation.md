# Alternatives evaluation — MS-RE-RUN-002

**Evaluation identity:** `ME-MS-RE-RUN-002-ALT-EVAL-001`
**Rule:** Alternatives are evaluated as separate propositions. None modifies `CA-001` in place [E-010, E-018].

## ALT-001 — Narrow lecture-local descriptive relation

**Proposition:** The transcript represents selected pairwise conflicts as a graph; maps conflict-free assignments to proper colorings; distinguishes a proper greedy output from the chromatic optimum; and states that for every finite graph and vertex ordering, maximum degree at most `d` implies greedy uses at most `d + 1` colors.

**Finding:** `SUPPORTED_WITH_SOURCE_LIMITATIONS`.

Each clause is orally stated in the immutable transcript [E-013–E-016]. The result is limited to fidelity to the reported lecture account; unavailable visuals, inaudible words, and absence of independent proof audit prevent treating it as external validation [E-006, E-012, E-017, E-020]. This is the strongest supported alternative because it avoids the ambiguous “made tractable” synthesis and preserves the exact guarantee [E-010, E-016].

## ALT-002 — Topic-specific teaching progression only

**Proposition:** The selected sequence is lecture organization for introducing graph coloring and does not establish a coherent transferable reasoning abstraction.

**Finding:** `PLAUSIBLE_AND_UNRESOLVED`.

The passages are dependent parts of one lesson, and the upstream patterns themselves identify lecture organization as an alternative [E-011, E-012]. The transcript deliberately progresses from representation to coloring to greedy bounds, which supports coherence inside the lesson [E-013–E-016], but no comparison cases discriminate a reusable method from pedagogical sequence [E-020]. Thus “only” is not established, while the challenge to transfer is strong.

## ALT-003 — The max-degree result is an absolute feasibility ceiling, not an optimality guarantee

**Proposition:** The stated `d + 1` guarantee bounds greedy output under a maximum-degree premise; it does not guarantee the optimum, closeness to the optimum, or computational tractability of optimal coloring.

**Finding:** `SUPPORTED_WITHIN_THE_TRANSCRIPT_ACCOUNT`.

The lecture says greedy is not necessarily optimal, describes optimal coloring as computationally hard, and calls the `d + 1` theorem a measure of quality while noting the example's optimum uses fewer colors than the ceiling [E-015, E-016]. No relative approximation claim is stated. This alternative exposes why the generic phrase “quality guarantee” requires qualification in a successor candidate [E-010].

## ALT-004 — Representation itself makes the represented problem tractable

**Proposition:** Once pairwise conflicts are represented as a graph, the represented-world problem becomes computationally tractable.

**Finding:** `NOT_SUPPORTED`.

The transcript says exact targeted or optimal graph coloring is computationally hard and notes that actual registrar scheduling may be a different, conflict-minimization problem [E-014, E-015]. Graph representation enables mathematical description and some bounded reasoning [E-013, E-016]; it does not establish computational tractability or real-world adequacy. This is a plausible reading of the ambiguous `CA-001` wording, which is why the candidate requires revision rather than favorable disambiguation [E-010].

## ALT-005 — `CA-001` loses the representation / represented-world distinction entirely

**Proposition:** The candidate collapses its graph representation into the real scheduling world.

**Finding:** `NOT_SUPPORTED_AS_A_DESCRIPTION_OF_THE_FULL_CANDIDATE_RECORD`.

`CA-001` explicitly preserves representation versus represented world, limits scope to lecture material, excludes real scheduling outcomes, and provides pairwise-representation failure conditions [E-010]. The transcript still supplies important limiting cases—the fake approximation and real conflict-minimization task—which must remain attached to use [E-014]. The distinction is preserved even though “tractable” remains ambiguous.

## Comparative result

ALT-001 and ALT-003 are better supported than the exact candidate synthesis; ALT-002 remains a live competing explanation; ALT-004 is contrary to the transcript if “tractable” is computational; ALT-005 does not fairly describe the full candidate artifact [E-010, E-013–E-016, E-020]. These results support `CANDIDATE_REQUIRES_REVISION`, not replacement or silent rewriting of `CA-001`.
