# MS-RE-RUN-002 limitations and gaps register

## Limitations

| ID | Limitation | Consequence |
| --- | --- | --- |
| `LIM-001` | Upstream content was not retrieved (`EV-001`) | Upstream uncertainties, limitations, and non-claims cannot be enumerated; they are preserved by making no replacement claims |
| `LIM-002` | Visual context was not available | Diagrams, gestures, board state, and other visual information cannot be inferred |
| `LIM-003` | Transcript content, including any `[INAUDIBLE]` segments, was not available | Missing speech cannot be located, reconstructed, or interpreted |

## Evidence gaps

| ID | Gap | Closure evidence required |
| --- | --- | --- |
| `GAP-001` | Exact paths, bytes, identities, and content of the request, handoff, cognition, and abstraction are unknown | Objects read directly from commit `b48ea9933547217357b6e22cac7d33fbc1d63711`, with paths and blob hashes |
| `GAP-002` | Transcript identity, bytes, provenance, cited passages, and relationship to commit `388c49a6d31c9f630dd1ce15cb7f752fd212cd20` are unknown | Immutable transcript source plus provenance and binding records |
| `GAP-003` | Handoff preparation and delivery states are unknown | Upstream state fields and transfer evidence from the immutable package |
| `GAP-004` | No separately admitted comparison evidence exists | Identified, provenance-bound comparison items and admission decisions |

Access restoration alone does not close a gap; the exact requested identities
must still verify without substitution.
