<div align="center">

# Perfect Foundations · GitHub Configuration

### The shared presentation, contribution, support, security, and collaboration layer for the Perfect Foundations organization.

![Organization](https://img.shields.io/badge/organization-Perfect%20Foundations-0891b2)
![Projects](https://img.shields.io/badge/family-41%20projects-44546a)
![Purpose](https://img.shields.io/badge/purpose-shared%20GitHub%20standards-2f855a)

</div>

---

## What this repository controls

This repository is the **organization-wide GitHub configuration layer** for Perfect Foundations.

It exists so every Perfect project starts from the same baseline for:

- organization presentation;
- contribution expectations;
- security-reporting guidance;
- support routing;
- pull-request structure;
- architecture/design proposals;
- bug reports;
- future community-health files.

It does **not** contain production algorithms.

---

## Repository map

```text
.github/
├── README.md
├── CONTRIBUTING.md
├── SECURITY.md
├── SUPPORT.md
├── PULL_REQUEST_TEMPLATE.md
├── profile/
│   └── README.md
└── .github/
    └── ISSUE_TEMPLATE/
        ├── architecture.yml
        ├── bug.yml
        └── config.yml
```

| File | Role |
|---|---|
| `profile/README.md` | Public organization landing page |
| `CONTRIBUTING.md` | Family-wide contribution guidance |
| `SECURITY.md` | Security-reporting expectations and claim boundaries |
| `SUPPORT.md` | Where family-wide vs crate-specific questions belong |
| `PULL_REQUEST_TEMPLATE.md` | Shared PR quality checklist |
| `architecture.yml` | Structured architecture/design proposal template |
| `bug.yml` | Reproducible bug-report template |
| `config.yml` | Issue-routing configuration |

---

## Presentation philosophy

Perfect Foundations repositories should be pleasant to read **without becoming marketing pages that obscure engineering reality**.

The visual style therefore favors:

- a centered project hero and concise tagline;
- restrained static badges;
- strong section hierarchy;
- compact “at a glance” tables;
- Mermaid diagrams where architecture benefits from a picture;
- concrete goals, use cases, non-goals, and design questions;
- explicit status language so planned features never look implemented;
- consistent family navigation.

The authoritative presentation standard lives in:

**[perfect-family/docs/PRESENTATION-STANDARD.md](https://github.com/Perfect-Foundations/perfect-family/blob/main/docs/PRESENTATION-STANDARD.md)**

---

## Authoritative family records

### 🗺️ Perfect Family

**[perfect-family](https://github.com/Perfect-Foundations/perfect-family)** owns:

- the 41-member canonical family catalog;
- architecture and dependency rules;
- build phases;
- engineering standards;
- FFI policy;
- reuse policy;
- scope boundaries;
- lifecycle;
- founding decisions;
- machine-readable catalog.

### ✅ Perfect Qualification

**[perfect-qualification](https://github.com/Perfect-Foundations/perfect-qualification)** owns:

- cross-crate compatibility;
- MSRV/target/feature matrices;
- determinism/reproducibility qualification;
- reference vectors;
- integration fuzzing/mutation strategy;
- release-level family qualification.

---

## Perfectπ protection rule

Perfectπ remains at **[DrTomLLC/perfect-pi](https://github.com/DrTomLLC/perfect-pi)** until it is complete and in service.

This organization infrastructure does not transfer, rewrite, or otherwise disturb Perfectπ during its active completion work.

---

<div align="center">

### Consistency here lets every individual project focus on its actual engineering problem.

</div>

## Design dossier

The README is the front door. The detailed implementation starting point is the **[Project Blueprint](docs/PROJECT-BLUEPRINT.md)**.

That blueprint records the project's expected core abstractions, functional requirements, algorithm families, semantic/error model, API principles, feature and dependency strategy, platform targets, Linux distribution/offline-build requirements, supply-chain policy, verification oracles, benchmark plan, key risks, milestones, and the evidence required before this crate can be considered **default-grade infrastructure**.

Family-wide requirements also apply:

- [Adoption Standard](https://github.com/Perfect-Foundations/perfect-family/blob/main/docs/ADOPTION-STANDARD.md)
- [Linux Distribution Readiness](https://github.com/Perfect-Foundations/perfect-family/blob/main/docs/DISTRO-READINESS.md)
- [API & Semantic Stability](https://github.com/Perfect-Foundations/perfect-family/blob/main/docs/API-STABILITY.md)
- [Release Quality Gates](https://github.com/Perfect-Foundations/perfect-family/blob/main/docs/RELEASE-QUALITY-GATES.md)
- [Supply-Chain & Build Security](https://github.com/Perfect-Foundations/perfect-family/blob/main/docs/SUPPLY-CHAIN-SECURITY.md)

> **Adoption ambition:** become a credible default foundational choice for Rust applications and Linux distribution packaging. This is a quality target to earn through evidence, not a claim of current endorsement by the Rust project or any Linux distribution.
