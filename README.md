# harmostes-template-noop

The noop **template repo** (three-tier phase 3c, ADR-0011 amendment): the
deterministic-only pipeline (no LLM agent, no validation gate) used for
probes and smoke runs. The CR plus vendored copies of the plugins its
nodes run (rig-emit, git-push, noop), drift-guarded against the kernel at
the pinned tag. No decision fields — nothing to decide.
