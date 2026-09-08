<div align="center">

# APTlantis

### Local-first software, governed engineering systems, archival infrastructure, and operator-focused tools.

![Projects](https://img.shields.io/badge/projects-34-2aa5bc?style=for-the-badge)
![Average Completion](https://img.shields.io/badge/average_completion-75.6%25-8957e5?style=for-the-badge)
![Production](https://img.shields.io/badge/production-5-2ea043?style=for-the-badge)
![Evaluated](https://img.shields.io/badge/evaluated-2026--09--08-51678d?style=for-the-badge)

**Build useful local tools. Preserve important artifacts. Govern the work. Record the evidence.**

</div>

---

## What APTlantis Is

APTlantis is a personal software ecosystem built around practical, operator-centered computing.

It includes Windows desktop applications, native and cross-platform command tools, archival and integrity systems, structured-data pipelines, dataset foundries, workspace governance, release standards, IDE integrations, local infrastructure utilities, and public documentation surfaces.

The projects are not treated as isolated experiments. They increasingly share manifests, schemas, lifecycle records, release evidence, command contracts, integrity practices, visual conventions, and a common governance layer in **City Hall**.

> APTlantis builds tools for doing the work and systems for understanding, governing, verifying, and preserving the work.

---

## Current Portfolio Snapshot

The September 8, 2026 evaluation covers **34 projects** with an average assessed completion of **75.6%**.

| Metric | Current Evaluation |
|---|---:|
| Total projects | **34** |
| Average completion | **75.6%** |
| Production | **5** |
| In progress | **21** |
| Maintenance | **3** |
| Paused | **3** |
| Prototype | **2** |
| High complexity | **23** |
| Medium complexity | **11** |

A completion percentage is an assessment of how much of the intended project exists. It is **not** a substitute for lifecycle state, release verification, or governance conformance.

APTlantis therefore keeps four questions separate:

- **Completion:** How much of the intended system exists?
- **Lifecycle:** Is the project in progress, paused, maintained, prototyped, or production?
- **Verification:** Have build, tests, artifacts, installation behavior, hashes, and release evidence been recorded?
- **Governance:** Does the project satisfy the standards appropriate to what it produces?

---

## City Hall — Governance and Standards

[City Hall](https://github.com/APTlantis/City-Hall) is the workspace-governance system behind the portfolio. Standards are designed as bounded, usable suites rather than generic policy documents.

| Standard | Status | Completion | Purpose |
|---|---:|---:|---|
| **DRS** | Production | 98% | Windows desktop release readiness, evidence, packaging, verification, and withdrawal records |
| **SFDS** | Production | 95% | Structure, metadata, validation, adoption, versioning, and preservation of standards |
| **WGS** | In Progress | 92% | Workspace structure, entity manifests, registration, lifecycle visibility, audits, and recovery |
| **AAMHS** | In Progress | 92% | Long-term archive integrity, multi-hash evidence, detached signatures, and verification |
| **CTS** | In Progress | 92% | CLI contracts, streams, exit codes, structured output, safeguards, and automation behavior |
| **SESM** | In Progress | 92% | Semantic metadata embedded in SVG assets, safe profiles, schemas, and validation |
| **PPS** | In Progress | 90% | Project intent, scope, success/failure criteria, risk, readiness, and roadmap definition |
| **ARHS** | Production | 90% | Release-artifact hash evidence using SHA256, BLAKE3-256, and KT128 |
| **LDS** | In Progress | 88% | Library and SDK interfaces, stability, compatibility, consumers, and extension contracts |
| **WDS** | In Progress | 85% | Website manifests, deployment evidence, accessibility, metadata, routes, and rollback |
| **BlueSlate** | In Progress | 70% | Visual tokens, operational layouts, framework profiles, and adoption records |

The practical chain is simple: **PPS defines the project → WGS places and governs it → the appropriate delivery standard governs what it produces → integrity standards preserve the evidence.**

---

## Public Project Map

The GitHub organization is a public projection of a larger local-first workspace. Not every active local project is published here, and repository state should not be treated as a replacement for the evaluated project records.

### Operator and Desktop Software

| Project | Current posture | What it does |
|---|---|---|
| [Filing Cabinet](https://github.com/APTlantis/Filing-Cabinet) | Maintenance · 88% | Local-first Windows vault for technical artifacts, structured metadata, previews, integrity checks, repair, recovery, and export |
| [Structra](https://github.com/APTlantis/Structra) | Maintenance · 90% | Tauri workspace for editing, inspecting, transforming, and previewing structured data |
| [Command Wizard](https://github.com/APTlantis/Command-Wizard) | Maintenance · 90% | Schema-driven command authoring and generation from TOML, with execution kept outside the application boundary |
| [ChatArchive](https://github.com/APTlantis/ChatArchive) | In Progress · 78% | Local archive for OpenAI conversation exports with browsing, search, artifacts, export, refresh, and rollback |
| [Ops Surface Red](https://github.com/APTlantis/Ops-Surface-Red) | In Progress · 60% | Native Red/View control surface for typed operational records and relationships |
| [React Workbench](https://github.com/APTlantis/React-Workbench) | In Progress · 70% | Theme/component laboratory with TOML source records, screenshot verification, and page metadata |
| [CodeNote](https://github.com/APTlantis/CodeNote) | Prototype · 55% | Focused local Tauri editor for Markdown/text with Prism, Mermaid, tabs, and terminal support |

### Command Tools, Evaluation, and Data

| Project | Current posture | What it does |
|---|---|---|
| [Crates.io Datasets](https://github.com/APTlantis/Cratesio-Datasets) | In Progress · 93% | Rust dataset foundry producing provenance-rich JSONL and Parquet datasets from immutable crates.io captures |
| [Clone Crates.io](https://github.com/APTlantis/Clone-Cratesio) | Paused · 88% | Go/Python crates.io mirror and archival pipeline with bundles, metadata sidecars, and JSONL audit evidence |
| [Analyze Projects](https://github.com/APTlantis/Analyze-Projects) | In Progress · 75% | Portfolio evaluator that reads bounded project evidence and compiles normalized JSON/Markdown assessments |
| [Single Project Evaluator](https://github.com/APTlantis/Single-Project-Evaluator) | In Progress · 55% | Read-only evaluator for one project with bounded evidence, governance context, and preserved run provenance |
| [Archive Hasher](https://github.com/APTlantis/Archive-Hasher) | Production · 75% | Go tooling for AAMHS archive hashing and detached signing workflows |
| [Release Hasher](https://github.com/APTlantis/Release-Hasher) | In Progress · 70% | Go CLI that produces SHA256, BLAKE3-256, and KT128 release hash manifests |
| [Wayfinder](https://github.com/APTlantis/Wayfinder) | Active utility | Workspace cleanup and structural-discovery workflow used to surface drift for agent-assisted repair |

### Current Experimental Edge

Recent work is deliberately widening the language and tooling surface where the project fit is useful:

- **Red** — native Red/View operator interfaces and a JetBrains plugin around `redlangserver`
- **D** — staged JetBrains IDE integration and a planned successor to WingettingQB64
- **WSL** — native `.wsl` packaging closure work for selected Linux distributions
- **Rust / Go / Python / Tauri / WPF** — retained where they fit existing desktop, pipeline, integrity, and evaluation work

This is not language collection for its own sake. The intent is to use small, practical projects to learn what each ecosystem is actually good at while keeping the tools bounded and useful.

---

## How the Ecosystem Is Shaped

APTlantis currently spans six connected layers:

1. **Governance and standards** — project proposals, workspace governance, delivery standards, integrity standards, and visual-system governance.
2. **Operator applications** — interfaces for artifact retention, structured data, commands, archives, operations, technical editing, and system workflows.
3. **Command tools and pipelines** — bounded utilities that transform source material into reproducible outputs and evidence.
4. **Preservation and integrity** — hashes, manifests, detached signatures, provenance, release records, and archive verification.
5. **Data, research, and mirrors** — reproducible captures, dataset foundries, software mirrors, and analysis surfaces.
6. **Public explanation** — repositories, documentation, websites, schemas, examples, and visual systems that make the work inspectable.

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
