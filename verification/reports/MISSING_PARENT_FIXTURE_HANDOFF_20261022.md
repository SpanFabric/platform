# Fresh BREAKER handoff — missing-parent fixture

Repository: SpanFabric/platform
Base: 459cc37e358cd68887491e6fcb58a0b98e01678f
Material: afabb588eebeba81f61c259c8b55783e9f8558f4
Digest: 6ea1cfe40e38ff88e86988a3e4125e1eea9e9a659a9744f15b4c2eccd7924ab4
Changed material: tests/verification/test_lifecycle_history.py
Builder ceiling: INDEPENDENT_REVIEW_PENDING

Reconstruct independently; Builder claims and CI are untrusted until checked.
Attack loose/GC/repack storage, GC commit-graph exit0 with incomplete traversal, paired valid/corrupt tips, exact absent 40-hex nonzero grandparent, successful base guard, strict direct+immutable runner history rejection, and positive restoration with malformed objects still present but unreachable.
Reproduce historical setup failure after GC without rerunning/deleting historical Actions run39800181504. Confirm validator/policy/runner/workflows unchanged, full authority/shallow/root/history regressions, old Owner/Breaker evidence inactive, material digest exact, and exact new PR-head verification-gate/bootstrap-integrity/windows prerequisite success.
Do not remediate, merge, accept as Owner, touch UP-003 or persistence PRs, or start MIG-001.
