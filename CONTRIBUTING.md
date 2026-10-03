# Contributing to Perfect Foundations

Perfect Foundations is currently in early architecture and implementation planning.

## Before proposing implementation

For a new crate or major feature, establish:
- the exact problem being solved;
- scope and explicit non-goals;
- existing Rust and non-Rust implementations;
- whether reuse is better than reimplementation;
- expected correctness/determinism contract;
- likely dependencies and `no_std` implications;
- FFI/runtime requirements;
- verification strategy;
- performance/resource requirements.

## Code expectations

Where applicable:
- explicit errors instead of panic-driven control flow;
- minimal dependencies;
- documented precision/loss behavior;
- tests for boundary conditions;
- deterministic behavior where promised;
- no unrelated scope expansion.

The authoritative family rules live in https://github.com/Perfect-Foundations/perfect-family.
