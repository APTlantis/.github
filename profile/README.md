<div align="center">

# APTlantis

### Local-first software, governed engineering systems, archival infrastructure, and operator-focused tools.

![Projects](https://img.shields.io/badge/projects-45-2aa5bc?style=for-the-badge)
![Average Completion](https://img.shields.io/badge/average_completion-81.8%25-8957e5?style=for-the-badge)
![Production](https://img.shields.io/badge/production-3-2ea043?style=for-the-badge)
![Evaluated](https://img.shields.io/badge/evaluated-2026--10--02-51678d?style=for-the-badge)

**Build useful local tools. Preserve important artifacts. Govern the work. Record the evidence.**

</div>

---

## What APTlantis Is

APTlantis is a personal software ecosystem built around practical, operator-centered computing.

It includes Windows desktop applications, native and cross-platform command tools, archival and integrity systems, structured-data pipelines, dataset and mirror tooling, workspace governance, release standards, IDE and knowledge-work integrations, local infrastructure utilities, and public documentation surfaces.

The projects are not treated as isolated experiments. They increasingly share manifests, schemas, lifecycle records, release evidence, command contracts, integrity practices, visual conventions, and a common governance layer in **City Hall**.

> APTlantis builds tools for doing the work and systems for understanding, governing, verifying, and preserving the work.

---

## Current Portfolio Snapshot

The October 2, 2026 evaluation covers **45 projects** with an average assessed completion of **81.8%**.

| Metric | Current Evaluation |
|---|---:|
| Total projects | **45** |
| Average completion | **81.8%** |
| Production | **3** |
| In progress | **33** |
| Maintenance | **4** |
| Paused | **2** |
| Planning | **1** |
| Prototype | **2** |
| High complexity | **14** |
| Medium complexity | **23** |
| Low complexity | **8** |

### Reading the complexity distribution

The raw complexity totals count every evaluated project independently, which is useful for project-level planning but can overstate how much of the portfolio is made up of unrelated small systems.

In this evaluation, **7 of the 8 Low-complexity projects are members of the SiYuan theme family**: Assembly, HolyC, Julia, QBasic, Scratch, TOML, and Zig. **BlueSlate**, another theme-family member, is assessed as Medium because it also functions as a broader design-system implementation.

| Low-complexity concentration | Projects |
|---|---:|
| SiYuan theme family | **7** |
| Other Low-complexity work | **1** |

These remain separate projects because they are independently packaged, versioned, maintained, and verified. At the portfolio level, however, they are better understood as **repeated implementations of a shared theme-production pattern** rather than seven unrelated simple projects. The low-complexity count therefore reflects both genuinely bounded work and the payoff from reusable architecture, palettes, generation tooling, and packaging conventions.

A completion percentage is an assessment of how much of the intended project exists. It is **not** a substitute for lifecycle state, release verification, or governance conformance.

APTlantis therefore keeps four questions separate:

- **Completion:** How much of the intended system exists?
- **Lifecycle:** Is the project in progress, paused, maintained, prototyped, planned, or production?
- **Verification:** Have build, tests, artifacts, installation behavior, hashes, and release evidence been recorded?
- **Governance:** Does the project satisfy the standards appropriate to what it produces?

---

## City Hall — Governance and Standards

[City Hall](https://github.com/APTlantis/City-Hall) is the workspace-governance system behind the portfolio. Standards are designed as bounded, usable suites rather than generic policy documents.

| Standard | Status | Completion | Purpose |
|---|---:|---:|---|
| **DRS** | Production | 94% | Desktop release readiness, exact-artifact evidence, packaging, verification, and release gating |
| **SFDS** | Production | 94% | Structure, versioning, validation, adoption, promotion, and preservation of governance standards |
| **SESM** | In Progress | 92% | Structured semantic metadata for SVG assets, safe profiles, schemas, fixtures, and ingestion boundaries |
| **AAS** | In Progress | 90% | Evidence requirements for analysis and evaluation, including inputs, tools, metrics, environments, and run records |
| **AAMHS** | In Progress | 89% | Archive-preservation integrity, multi-hash manifests, detached signatures, and revalidation |
| **CTS** | In Progress | 89% | CLI command contracts, output envelopes, exit codes, compatibility, and destructive-operation safety |
| **WDS** | In Progress | 89% | Website manifests, deployment evidence, accessibility, metadata, routes, rollback, and monitoring |
| **WGS** | In Progress | 88% | Workspace placement, manifest authority, registration, lifecycle visibility, shared services, and audits |
| **ARHS** | In Progress | 88% | Release-artifact integrity evidence using SHA256, BLAKE3-256, and KT128 |
| **BlueSlate** | In Progress | 88% | Visual-system tokens, generated translations, framework profiles, layouts, and adoption records |
| **LDS** | In Progress | 88% | Library, package, SDK, interface, stability, and compatibility governance |
| **NeonInk** | In Progress | 88% | Data-presentation semantics for reports, charts, datasets, diagrams, and portable artifacts |
| **DDS** | In Progress | 87% | Dataset provenance, licensing, transformations, validation, splits, integrity, and preservation |
| **SIS** | In Progress | 87% | Local service lifecycle, health, storage, resource, recovery, and agent-safety contracts |
| **ATS** | In Progress | 85% | Recoverable agent task records, validation evidence, blockers, lifecycle, and handoffs |
| **PPS** | In Progress | 85% | Project intent, scope, readiness, proposal records, and handoff into workspace and delivery governance |

The practical chain is simple: **PPS defines the project → WGS places and governs it → the appropriate delivery standard governs what it produces → integrity and evidence standards preserve what happened.**

---

## Public Project Map

The GitHub organization is a public projection of a larger local-first workspace. Not every active local project is published here, and repository state should not be treated as a replacement for the evaluated project records.

### Operator and Desktop Software

| Project | Current posture | What it does |
|---|---|---|
| [Filing Cabinet](https://github.com/APTlantis/Filing-Cabinet) | Maintenance · 94% | Windows VB.NET/WPF vault for technical artifacts with deterministic ingest, previews, related-artifact views, hashing, health analysis, repair, recovery, and export |
| [Structra](https://github.com/APTlantis/Structra) | Maintenance · 92% | Local-first Windows Tauri workspace for structured JSON, YAML, TOML, XML, and schema-oriented editing and preview |
| [Command Wizard](https://github.com/APTlantis/Command-Wizard) | Maintenance · 92% | TOML schema-driven CLI authoring, reviewed help imports, saved commands, managed launchers, and validated command generation |
| [ChatArchive](https://github.com/APTlantis/ChatArchive) | In Progress · 84% | Windows-first archive for OpenAI conversation exports with filesystem-backed storage, SQLite state, search, artifacts, Markdown export, refresh, and rollback |
| [Aptlantis Console](https://github.com/APTlantis/Aptlantis-Console) | In Progress · 78% | Local-first operations console spanning commands, Docker, repositories, databases, terminals, editing, intake, and operational memory |
| [Hubris](https://github.com/APTlantis/Hubris) | Prototype · 65% | Windows DNS observation and policy cockpit with explicit intake, provenance-bearing query records, and a DuckDB-backed local timeline |

### Command Tools, Evaluation, and Data

| Project | Current posture | What it does |
|---|---|---|
| [Clone Crates.io](https://github.com/APTlantis/Clone-Cratesio) | Paused · 92% | Go/Python crates.io mirror with concurrent downloads, incremental updates, tar.zst bundles, sidecars, extraction, and telemetry |
| [Analyze Projects](https://github.com/APTlantis/Analyze-Projects) | In Progress · 83% | Portfolio evaluator that normalizes bounded project evidence into per-project JSON, aggregate summaries, and a local dashboard |
| [Single Project Evaluator](https://github.com/APTlantis/Single-Project-Evaluator) | Planning · 55% | Read-only one-project evaluator built around bounded evidence, authority records, governance context, preserved runs, and optional model analysis |
| [Archive Hasher](https://github.com/APTlantis/Archive-Hasher) | Production · 80% | Go tooling for AAMHS archive hashing and detached-signature workflows |
| [Release Hasher](https://github.com/APTlantis/Release-Hasher) | In Progress · 70% | Go CLI for SHA256, BLAKE3-256, and KT128 release hash manifests with human and JSON output |
| [Wayfinder](https://github.com/APTlantis/Wayfinder) | Public utility · not in current evaluation | Workspace cleanup and structural-discovery workflow used to surface drift for agent-assisted repair |
| [Crates.io Datasets](https://github.com/APTlantis/Cratesio-Datasets) | Public repository · not in current evaluation | Dataset and transformation work built around captured crates.io material |

### Themes, Knowledge Tools, and Public Surfaces

The current evaluation includes a substantial **SiYuan theme family** alongside plugins, knowledge-work utilities, the public City Hall website, and supporting design standards.

The theme repositories are intentionally evaluated separately because each is a real maintained artifact with its own package, compatibility surface, palette, generated assets, and runtime-verification needs. They also share enough architecture that they should be read as a **project family** rather than as eight unrelated applications.

| SiYuan theme family | Current posture | Portfolio role |
|---|---|---|
| **Aptlantis QBasic** | In Progress · 90% · Low | Family member |
| **Aptlantis Assembly** | In Progress · 80% · Low | Family member |
| **Aptlantis HolyC** | In Progress · 80% · Low | Family member |
| **Aptlantis Julia** | In Progress · 80% · Low | Family member |
| **Aptlantis Scratch** | In Progress · 80% · Low | Family member |
| **Aptlantis TOML** | In Progress · 80% · Low | Family member |
| **Aptlantis Zig** | In Progress · 80% · Low | Family member |
| **Aptlantis BlueSlate** | In Progress · 80% · Medium | Theme implementation + broader design-system work |

That distinction matters: repeated low-complexity descendants are partly evidence that the harder architectural work has already been captured upstream. Shared palette generation, semantic-role mapping, packaging conventions, and SiYuan integration make additional themes smaller without making them trivial or disposable.

Other evaluated work in this layer includes:

- **Code Artifact Intake** — In Progress · 90%
- **Windows Terminal for SiYuan** — In Progress · 85%
- **APTlantis City Hall website** — In Progress · 85%
- **Aptlantis Logos** — Paused · 90%

Repositories that are public but absent from the current evaluation are intentionally left without inherited completion scores.

---

## How the Ecosystem Is Shaped

APTlantis currently spans six connected layers:

1. **Governance and standards** — project proposals, workspace governance, delivery standards, evidence standards, integrity standards, and visual-system governance.
2. **Operator applications** — interfaces for artifact retention, structured data, commands, archives, operations, technical editing, and system workflows.
3. **Command tools and pipelines** — bounded utilities that transform source material into reproducible outputs and evidence.
4. **Preservation and integrity** — hashes, manifests, detached signatures, provenance, release records, and archive verification.
5. **Data, research, mirrors, and knowledge systems** — reproducible captures, software mirrors, datasets, local analysis, and SiYuan-based exploration.
6. **Public explanation** — repositories, documentation, websites, schemas, examples, visual systems, and reviewed snapshots that make the work inspectable.

---

## Operating Principles

- **Local first.** Useful capability should not require a hosted service unless the project explicitly calls for one.
- **Operator visible.** Important actions, state, provenance, and failure conditions should be inspectable.
- **Evidence before claims.** Build, test, package, install, hash, and release claims should follow recorded verification.
- **Structured where it matters.** TOML, JSON, JSONL, schemas, manifests, and explicit records are preferred over hidden state.
- **Plan first, execute second.** Risky or destructive operations should expose intent and boundaries before mutation.
- **Preserve the artifact and the context.** A file without provenance, integrity evidence, or lifecycle context is less useful over time.
- **Standards serve the work.** Governance exists to make projects easier to understand, recover, hand off, and verify — not to maximize paperwork.

---

<div align="center">

### Build the tool. Record the state. Preserve the evidence.

[Browse APTlantis repositories](https://github.com/orgs/APTlantis/repositories) · [City Hall](https://github.com/APTlantis/City-Hall)

</div>
