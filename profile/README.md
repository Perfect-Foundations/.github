# Perfect Foundations

**High-assurance foundational Rust infrastructure for deterministic, exact, reproducible, and verifiable computing.**

Perfect Foundations is a coordinated family of focused Rust libraries intended to provide reusable infrastructure beneath scientific, engineering, financial, navigation, biomedical, quantum, evidence, and other correctness-sensitive software.

The family is deliberately **not** a monolith. Each crate owns a narrow domain, remains independently versioned, and depends only on lower layers that materially improve its correctness or capability.

## Current state

- **40 new Perfect-family crate repositories are reserved** in this organization and remain private during initial architecture work.
- **Perfectπ / `perfect-pi`** is the first existing family member. It remains at [DrTomLLC/perfect-pi](https://github.com/DrTomLLC/perfect-pi) until it is complete and in service; it will be transferred only after that milestone.
- [perfect-family](https://github.com/Perfect-Foundations/perfect-family) is the authoritative family architecture, catalog, roadmap, and policy repository.
- [perfect-qualification](https://github.com/Perfect-Foundations/perfect-qualification) owns cross-family compatibility and qualification work.

## Engineering direction

Perfect-family crates target the following principles where the domain permits them:

- Pure Rust by default.
- No mandatory C, C++, Fortran, Python, JVM, or vendor runtime dependency unless a crate explicitly documents and justifies it.
- Deterministic behavior and reproducible results where meaningful.
- Explicit rounding, precision, loss, overflow, resource, and error semantics.
- Panic-free production paths as a design objective.
- `no_std` support where practical.
- Minimal dependencies and no artificial cross-crate coupling.
- Caller-owned buffers and bounded-resource APIs where appropriate.
- Independent reference verification, fuzzing, mutation testing, cross-platform testing, and reproducibility checks where useful.
- Specialist crates own their domain; aggregators reference specialists rather than silently duplicating them.
- Mature Rust-native infrastructure is reused when it already solves a problem well. Perfect Foundations is not a rewrite-for-ownership project.

## Family domains

The planned family spans:

**numeric semantics · exact arithmetic · rational · arbitrary-precision float · decimal · algebra · number theory · mathematics · complex · interval/ball arithmetic · polynomials · special functions · calculus · differential equations · geometry · probability · statistics · information theory · classical error correction · optimization · signal processing · mechanics · estimation · control · quantum information · quantum circuits · quantum simulation · quantum compilation · quantum error correction · finance · meteorology · navigation · GNSS · biosignals · units · uncertainty · canonical wire representation · evidence/provenance · CODATA · unified constants · Perfectπ**

See the complete specification in [perfect-family](https://github.com/Perfect-Foundations/perfect-family).
