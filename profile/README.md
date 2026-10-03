# Perfect Foundations

**High-assurance foundational Rust infrastructure for deterministic, exact, reproducible, and verifiable computing.**

Perfect Foundations is a family of focused, independently versioned Rust libraries. Each crate owns one clearly defined foundational domain and depends only on lower layers that materially improve its correctness or capability.

## Engineering principles

- Pure Rust by default; foreign-language runtimes only when explicitly optional and justified.
- Deterministic behavior wherever the domain permits it.
- Explicit rounding, precision, loss, resource, and error semantics.
- Panic-free production paths as a design goal.
- `no_std` support wherever practical.
- Minimal dependencies and no artificial cross-crate coupling.
- Independent reference verification, fuzzing, mutation testing, and reproducibility checks where useful.
- Specialist crates own their domain; aggregator crates do not silently duplicate specialist implementations.

## Family

The authoritative family map, architecture, scope boundaries, and build order live in [perfect-family](https://github.com/Perfect-Foundations/perfect-family).

Cross-crate compatibility and qualification work lives in [perfect-qualification](https://github.com/Perfect-Foundations/perfect-qualification).

Perfectπ is the first existing member of the family and remains at [DrTomLLC/perfect-pi](https://github.com/DrTomLLC/perfect-pi) until it is complete and in service. It will be transferred only after that milestone.
