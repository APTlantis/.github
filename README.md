<div align="center">

# APTlantis

### Local-first software, governed engineering systems, archival infrastructure, and operator-focused tools.

![Projects](https://img.shields.io/badge/projects-37-2aa5bc?style=for-the-badge)
![Average Completion](https://img.shields.io/badge/average_completion-73.4%25-8957e5?style=for-the-badge)
![Production](https://img.shields.io/badge/production-4-2ea043?style=for-the-badge)
![Evaluated](https://img.shields.io/badge/evaluated-2026--07--30-51678d?style=for-the-badge)

**Build useful local tools. Preserve important artifacts. Govern the work. Record the evidence.**

</div>

---

## What APTlantis Is

APTlantis is a personal software ecosystem built around practical, operator-centered computing.

It includes Windows desktop applications, command-line tools, archival and integrity systems, structured-data pipelines, project and release standards, local infrastructure utilities, research datasets, visual systems, and public documentation surfaces. The projects vary in maturity, but they share a common goal: turn complicated or fragile technical work into durable, inspectable, repeatable systems.

APTlantis is not organized as a loose collection of unrelated experiments. Projects are increasingly connected through shared governance, lifecycle records, manifests, schemas, release evidence, command contracts, integrity practices, and visual conventions.

> APTlantis builds tools for doing the work and systems for understanding, governing, verifying, and preserving the work.

---

## Current Portfolio Snapshot

The current evaluation covers **37 projects** with an average assessed completion of **73.4%**.

| Metric | Current Evaluation |
|---|---:|
| Total projects | **37** |
| Average completion | **73.4%** |
| Production | **4** |
| Active | **3** |
| Candidate active | **2** |
| In progress | **16** |
| Prototype | **4** |
| Paused | **7** |
| Draft | **1** |
| High complexity | **11** |
| Medium complexity | **24** |
| Low complexity | **2** |

The evaluation source records `Paused`/`paused`, `active`, `candidate-active`, and other lifecycle values with their project-specific capitalization. The table above normalizes equivalent labels for readability.

### How to Read These Numbers

A completion percentage is an assessment of how much of the intended project exists. It is **not** a substitute for lifecycle state or release verification.

A project may be highly complete but paused, awaiting a lifecycle decision, missing a release-evidence bundle, or blocked on packaging and verification. Likewise, an active standard may be useful and widely applied while still requiring additional validators, examples, or promotion evidence.

APTlantis therefore treats these as separate questions:

- **Completion:** How much of the intended system exists?
- **Lifecycle:** Is the project active, paused, experimental, or considered production?
- **Verification:** Have its build, tests, artifacts, installation behavior, hashes, and release evidence been recorded?
- **Governance:** Does it satisfy the standards appropriate to its project type?

---

## The Shape of the Ecosystem

APTlantis currently operates across six connected layers.

### 1. Governance and Standards

City Hall standards define how projects are proposed, placed, documented, released, operated, evaluated, and preserved.

![WGS](https://img.shields.io/badge/WGS-workspace_governance-2aa5bc?style=flat-square)
![SFDS](https://img.shields.io/badge/SFDS-standard_authoring-6f42c1?style=flat-square)
![PPS](https://img.shields.io/badge/PPS-project_proposals-8957e5?style=flat-square)
![DRS](https://img.shields.io/badge/DRS-desktop_releases-2ea043?style=flat-square)
![CTS](https://img.shields.io/badge/CTS-command_tools-dd680a?style=flat-square)
![WDS](https://img.shields.io/badge/WDS-websites-0078d4?style=flat-square)

### 2. Operator Applications

Desktop applications turn recurring local workflows into deliberate, inspectable interfaces: artifact retention, infrastructure operations, structured-data construction, command generation, archive reading, disk planning, package work, and technical writing.

### 3. Command Tools and Pipelines

Command-oriented projects transform source material into structured datasets, archives, manifests, themes, media, package references, evaluation records, and other durable outputs.

### 4. Preservation and Integrity

Archive standards and tools define how artifacts are hashed, signed, described, retained, verified, and recovered. Integrity evidence is treated as part of the artifact rather than an optional afterthought.

### 5. Data, Research, and Mirrors

Dataset foundries, software mirrors, historical collections, and analysis tools convert large technical corpora into reproducible snapshots and queryable research surfaces.

### 6. Public Explanation and Visual Systems

Websites, asset standards, component libraries, logo systems, and the Blue Slate visual language make the ecosystem legible without flattening it into generic product presentation.

---

## Flagship Systems

These projects currently provide the clearest view of what APTlantis is becoming. Their inclusion here reflects architectural importance and representative value, not only lifecycle status.

### WGS — Workspace Governance Standard

![Status](https://img.shields.io/badge/status-active-8957e5?style=flat-square)
![Completion](https://img.shields.io/badge/completion-92%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-high-b7410e?style=flat-square)

WGS is the workspace constitution. It defines entity-named manifests, workspace roots and target maps, agent read-first behavior, lifecycle classifications, required project artifacts, migration policy, audit tooling, inventory generation, health records, and recoverable workspace orientation.

Its central purpose is to ensure that a project can be understood from its governed records rather than reconstructed from memory or directory archaeology.

### DRS — Desktop Release Standard

![Status](https://img.shields.io/badge/status-production-2ea043?style=flat-square)
![Completion](https://img.shields.io/badge/completion-95%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-medium-51678d?style=flat-square)

DRS governs local-first Windows desktop releases. It provides an authoritative specification, manifest schema, PowerShell scaffolding and validation tooling, release-note templates, trust and security records, dependency and migration documentation, artifact naming requirements, SHA-256 integrity requirements, and per-release verification gates.

DRS is one of the clearest examples of the ecosystem moving from “the application builds” to “the release can be independently understood and checked.”

### AptlantisConsole

![Status](https://img.shields.io/badge/status-in_progress-db6d28?style=flat-square)
![Completion](https://img.shields.io/badge/completion-90%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-high-b7410e?style=flat-square)

AptlantisConsole is a local-first desktop operations console built from a Next.js 16 frontend, Tauri 2 Windows shell, and bundled Node runtime. It brings Docker, Git, MongoDB, DuckDB, network and system tools, terminals, SSH/FTP, command workflows, TOML runbooks, screenshot capture, and persistent operator artifacts into one working surface.

The current application is packaged as version 1.0.8. Its main remaining work is not basic capability; it is DRS release hardening: artifact hashes, verification blocks, release evidence, signing posture, and documentation delivery.

### CratesDataset

![Status](https://img.shields.io/badge/status-in_progress-db6d28?style=flat-square)
![Completion](https://img.shields.io/badge/completion-93%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-high-b7410e?style=flat-square)

CratesDataset is a Rust-based dataset foundry that transforms immutable monthly crates.io version snapshots into eight purpose-built datasets in JSONL-Zstandard and Parquet formats. It includes versioned schemas, provenance records, statistics, integrity hashes, deterministic partitioned processing, rejected-record evidence, and a Hugging Face Hub packaging adapter.

Its remaining gates are intentionally strict: redistribution approval, deterministic rebuild acceptance, and stabilization of observed Parquet encoding variance.

### FileCabinet

![Status](https://img.shields.io/badge/status-paused-6c757d?style=flat-square)
![Completion](https://img.shields.io/badge/completion-90%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-high-b7410e?style=flat-square)

FileCabinet is a VB.NET/WPF desktop vault for deliberate retention of technical artifacts. It provides deterministic copy/move intake, a local JSON catalog, multi-hash fingerprints, preview and thumbnail generation, health analysis, repair and recovery workflows, deterministic packaging, and a headless CLI.

Its paused state illustrates why lifecycle and completion are tracked separately: the application is substantial, but its current checkout still requires rebuilt installer evidence, verification records, and a release-evidence bundle.

### ArchiveHasher

![Status](https://img.shields.io/badge/status-production-2ea043?style=flat-square)
![Completion](https://img.shields.io/badge/completion-90%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-high-b7410e?style=flat-square)

ArchiveHasher is a Go command suite implementing AAMHS archive-publication workflows. `archive-hasher` computes an eight-algorithm hash suite over an archive byte stream and writes a canonical `snapshot-hashes.txt` manifest. `manifest-signer` creates detached PGP and optional post-quantum SLH-DSA signatures without changing the canonical manifest.

Its next maturity step is CTS alignment: explicit command contracts, stable exit-code documentation, machine-readable output policy, version output, destructive-operation guidance, and release verification records.

### Structra

![Status](https://img.shields.io/badge/status-in_progress-db6d28?style=flat-square)
![Completion](https://img.shields.io/badge/completion-60%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-medium-51678d?style=flat-square)

Structra is a Tauri desktop application for visually constructing structured data and schema-shaped documents. Its React/TypeScript interface and Rust backend support structured authoring workflows intended to make JSON, YAML, TOML, XML, and related formats easier to build and reason about.

The project has deliberately moved away from broad feature accumulation toward a clearer core identity: a focused graphical environment for structured construction.

### AptDiskwright

![Status](https://img.shields.io/badge/status-prototype-0078d4?style=flat-square)
![Completion](https://img.shields.io/badge/completion-65%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-high-b7410e?style=flat-square)

AptDiskwright is a Windows 11 disk-planning and GPT/UEFI migration prototype built around one operating rule: **plan first, execute second, record everything**.

It uses an unelevated WPF client for inventory, planning, validation, and review, with privileged operations crossing a versioned, length-prefixed named-pipe protocol to a demand-start C++ Windows service. Physical-disk mutation remains disabled pending disposable-VHD and bootable-VM qualification evidence.

---

## Standards and Governance Suite

APTlantis standards are not generic policy documents. Each standard defines a bounded delivery or governance problem and supplies the artifacts needed to apply it.

| Standard | Status | Completion | Governs |
|---|---:|---:|---|
| **WGS** | Active | 92% | Workspace structure, manifests, lifecycle, agent orientation, audits, and recovery |
| **SFDS** | Production | 90% | How standards themselves are authored, versioned, validated, adopted, and preserved |
| **PPS** | Active | 85% | Proposal-first definition of project intent, boundaries, success criteria, risks, and readiness |
| **DRS** | Production | 95% | Local-first Windows desktop release structure, evidence, integrity, and verification |
| **CTS** | In Progress | 85% | Stable CLI contracts, exit codes, machine output, destructive behavior, and automation compatibility |
| **WDS** | In Progress | 80% | Site manifests, deployment records, accessibility, SEO, route checks, rollback, and monitoring |
| **LDS** | Candidate Active | 75% | Public library interfaces, stability levels, compatibility, extension contracts, and consumers |
| **AAMHS** | In Progress | 85% | Preservation-oriented multi-hash manifests and detached-signature policy |
| **SESM** | In Progress | 90% | Structured provenance and semantic metadata embedded in SVG assets |
| **Blue Slate** | Candidate Active | 70% | Visual tokens, layout patterns, framework adapters, and interface validation |

### Standards Relationships

The standards form a practical chain rather than a hierarchy of paperwork:

1. **PPS** defines why a project should exist and freezes its initial boundaries.
2. **WGS** places it in the workspace and defines the records needed to keep it discoverable.
3. **SFDS** governs the construction of standards such as DRS, CTS, WDS, LDS, AAMHS, and SESM.
4. A delivery standard governs the project according to what it produces:
   - **DRS** for desktop applications
   - **CTS** for command tools
   - **WDS** for websites
   - **LDS** for libraries
5. **AAMHS** and related integrity practices preserve high-value artifacts and publication evidence.
6. **SESM** and **Blue Slate** govern semantic visual metadata and interface language where appropriate.

The goal is not maximum process. The goal is enough explicit structure that a future operator or agent can answer: what is this, why does it exist, what state is it in, how is it built, what evidence exists, and what remains unresolved?

---

## Project Catalog

### Desktop and Operator Applications

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **AptlantisConsole** | In Progress | 90% | Desktop operations dashboard for local development, infrastructure, data tools, terminals, and reusable operator workflows. |
| **FileCabinet** | Paused | 90% | Deliberate technical-artifact vault with integrity fingerprints, previews, health checks, repair, recovery, and CLI automation. |
| **CommandWizard** | Paused | 95% | Schema-driven WPF/.NET application for creating and using TOML command schemas through guided command construction. |
| **ChromeArchivalPlugin** | In Progress | 85% | Chrome MV3 extension for deterministic local capture of metadata, links, readable Markdown, full-page Markdown, screenshots, and PDFs. |
| **Chat** | Paused | 75% | ChatArchive desktop importer and reader for OpenAI/ChatGPT exports with normalized conversation trees, assets, and SQLite indexes. |
| **Tauri-IT** | In Progress | 75% | DRS-governed Tauri desktop adaptation of the IT-Tools workspace. |
| **QB-Winget** | In Progress | 70% | Local-first QB64/InForm interface around Winget search and package operations. |
| **AptDiskwright** | Prototype | 65% | Plan-first disk inventory, transaction design, conflict validation, and GPT/UEFI migration analysis. |
| **Structra** | In Progress | 60% | Visual construction environment for structured data and schema-shaped documents. |
| **CodeNote** | Prototype | 40% | Lightweight Tauri editor with Markdown preview, syntax highlighting, Mermaid, tabs, and optional native-terminal integration. |
| **WinTrim** | Prototype | 35% | Evidence-driven Windows trimming and configuration workspace based on manifests, presets, exports, and machine profiles. |
| **WingettingQB64** | Paused | 0% | Registered placeholder retained for lifecycle and historical identity; no implementation was present at evaluation time. |

### Command Tools, Generators, and Local Pipelines

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **ScriptWriters** | Production | 90% | Local pipeline that turns topic Markdown into multi-host podcast scripts and rendered audio using Ollama, TTS backends, and FFmpeg. |
| **ArchiveHasher** | Production | 90% | Go tools for eight-algorithm archive manifests and detached PGP or post-quantum signatures. |
| **ClipboardFilter** | Active | 85% | Python/TOML pipeline that extracts atomic clipboard entries, creates embeddings, and stores/searches them through DuckDB. |
| **FH-RefToolkit** | Paused | 80% | Python CLI for generating Flathub reference lists and downloading `.flatpakref` descriptors. |
| **ConversionTools** | In Progress | 70% | Local-first audio, speech, and video conversion workflows spanning Rust and supporting utilities. |
| **LangThemeGenerator** | In Progress | 70% | Palette analysis and semantic-token generator for editor, terminal, CSS, and interface theme outputs. |
| **AnalyzeProjects** | In Progress | 60% | CTS-governed portfolio analyzer that scans an explicit project index and generates structured project assessments using local or hosted models. |

### Datasets, Mirrors, and Research Systems

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **CratesDataset** | In Progress | 93% | Deterministic Rust dataset foundry producing versioned crates.io datasets with provenance, statistics, and integrity records. |
| **CloneCratesio** | Paused | 92% | High-concurrency Go mirror and archival pipeline for crates.io artifacts, bundles, JSONL audit records, metadata, and observability. |
| **WSL** | In Progress | 65% | Governed project group for building and packaging multiple WSL distributions from ISO, SquashFS, rootfs, launcher, and MSIX workflows. |
| **HolyC-Llama** | In Progress | 60% | HolyC/TempleOS dataset and model-preparation workspace with Rust and Python generation tooling. |
| **aptlantis.net** | Prototype | 58% | Append-only crates.io mirror pipeline with snapshots, AAMHS provenance, torrent packaging, datasets, analytics, and an Astro public surface. |

### Visual, Asset, and Public Explanation Systems

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **SESM** | In Progress | 90% | SVG metadata standard, schema, validators, fixtures, converters, and safe-profile guidance. |
| **AptlantisLogos** | Paused | 75% | Source logos, palettes, metadata, atlas output, and scripts for preserving and rendering Aptlantis visual assets. |
| **Blue Slate** | Candidate Active | 70% | Canonical visual tokens, patterns, starter packs, framework notes, adoption guidance, and validation checklist. |
| **Aptlantis Studio** | Draft | 60% | Evidence-first public project and teaching portfolio built with React/Vite, static project data, and a small Rust Axum service. |
| **ReactComponentLibrary** | In Progress | 40% | Private React component workspace for reusable Aptlantis Blue Slate interface patterns. |

### Governance and Standards Projects

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **DRS** | Production | 95% | Desktop release governance and verification. |
| **WGS** | Active | 92% | Workspace constitution, manifests, lifecycle, agent orientation, and audits. |
| **SFDS** | Production | 90% | Standard-authoring framework and suite contract. |
| **AAMHS** | In Progress | 85% | Archive multi-hash and detached-signature standard. |
| **CTS** | In Progress | 85% | Command-tool contracts and automation behavior. |
| **PPS** | Active | 85% | Proposal-first project definition and readiness gates. |
| **WDS** | In Progress | 80% | Website publication and deployment governance. |
| **LDS** | Candidate Active | 75% | Library interface stability and compatibility governance. |

---

## Engineering Principles

### Local First

Core functionality should remain useful without a hosted service. Network integration may extend a project, but it should not erase operator ownership of data, configuration, or essential workflows.

### Evidence First

A claim that a project builds, installs, preserves data, or publishes an artifact should be supported by a record: logs, hashes, manifests, screenshots, test results, install checks, deployment records, or release evidence.

### Manifest Driven

Important state should be machine-readable. Manifests describe project identity, lifecycle, placement, releases, artifacts, standards adoption, known gaps, and verification state.

### Operator Centered

Tools are designed around real actions performed by a real operator. The interface should expose what will happen, what happened, where outputs went, and how to recover.

### Plan Before Mutation

Potentially destructive work should support preview, validation, explicit intent, and recoverable records. AptDiskwright expresses this directly, but the principle also applies to command tools, generators, installers, migration workflows, and publishing systems.

### Integrity Is Part of the Product

Hashes, signatures, artifact names, release notes, provenance, and evidence bundles are part of the deliverable—not administrative debris produced after the “real” work.

### Human and Agent Readability

Documentation should orient both people and automated agents. Read-first files, canonical manifests, stable directory contracts, schemas, and closeout records reduce dependence on undocumented context.

### Preserve Boundaries

Projects should state what they are not trying to become. Design boundaries protect focused tools from feature accumulation and allow lifecycle decisions to remain deliberate.

### Durable Outputs Over Ephemeral Demos

APTlantis favors artifacts that can be inspected later: TOML, JSON, JSONL, Parquet, Markdown, SVG, manifests, logs, release records, signed hash files, static sites, local databases, and installable packages.

---

## Evaluation-Driven Development

The latest portfolio evaluation does more than assign percentages. Each project record captures:

- lifecycle state and completion estimate;
- project complexity;
- technology and domain tags;
- a current functional summary;
- missing pieces and unresolved blockers;
- immediate next steps;
- non-blocking potential improvements.

This changes the development model from an undifferentiated backlog into a portfolio of explicit states.

### Common Findings Across the Portfolio

Several recurring maturity gaps appear across otherwise capable projects:

1. **Release evidence needs consolidation.** Builds and installers may exist while hashes, logs, install checks, and per-version verification blocks remain incomplete.
2. **Manifest and product versions can drift.** Evaluations surface mismatches between manifests, package metadata, installers, and release notes.
3. **CLI behavior needs contracts.** CTS-governed tools often need clearer exit-code tables, `--version`, explicit machine-readable modes, structured errors, and stdout/stderr separation.
4. **Destructive behavior needs stronger previews.** Overwrite, replacement, migration, and publishing commands benefit from dry-run, confirmation, and recovery contracts.
5. **Web publication needs operational records.** WDS-governed sites need deployment records, accessibility checks, route inventories, rollback notes, monitoring expectations, and publication evidence.
6. **Standards need executable validation.** Several standards are structurally mature but would benefit from reference validators and machine-readable conformance output.
7. **Paused does not mean failed.** Several highly complete projects are paused because the workflow is currently satisfied, priorities changed, or release/governance work awaits a deliberate decision.

---

## Current Direction

APTlantis is currently emphasizing **hardening, integration, and legibility** over simply increasing the project count.

The main direction of travel is:

- reconcile lifecycle states and preserve intentional pauses;
- bring release artifacts into alignment with DRS evidence requirements;
- bring command tools into alignment with CTS contracts;
- add executable validators and structured outputs to governance standards;
- strengthen deterministic rebuild and provenance guarantees for datasets;
- qualify destructive workflows through disposable and reconstructable test environments;
- connect project manifests, evaluation output, and public portfolio data;
- document deployment, accessibility, rollback, and monitoring for public sites;
- consolidate Blue Slate, SESM, logos, and reusable components into a coherent visual implementation layer;
- use evaluations as recurring portfolio snapshots rather than one-time grading exercises.

The objective is not to make every project “Production.” The objective is to make every project's state accurate, useful, and recoverable.

---

## Technology Landscape

APTlantis uses technology according to the shape of the problem rather than enforcing one universal stack.

### Application and Systems Languages

![Rust](https://img.shields.io/badge/Rust-systems_&_desktop-b7410e?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-archives_&_pipelines-00add8?style=flat-square&logo=go&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-windows_desktop-512bd4?style=flat-square&logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-data_&_automation-3776ab?style=flat-square&logo=python&logoColor=white)

- **Rust** for Tauri backends, systems tooling, high-throughput transformations, and packaging workflows.
- **Go** for archive tooling, concurrent downloaders, deterministic command utilities, and compact deployable binaries.
- **.NET, WPF, VB.NET, C#, and C++** for Windows-native applications, privileged services, installers, and long-lived desktop interfaces.
- **Python** for data processing, evaluators, automation, model integration, metadata extraction, and reference validators.
- **QB64/InForm** where a focused desktop tool benefits from the stack's directness and continuity.

### Interfaces

![React](https://img.shields.io/badge/React-interfaces-61dafb?style=flat-square&logo=react&logoColor=black)
![Tauri](https://img.shields.io/badge/Tauri-desktop_shells-24c8db?style=flat-square&logo=tauri&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-operator_surfaces-111111?style=flat-square&logo=nextdotjs&logoColor=white)

- React and TypeScript for dense application interfaces and reusable components.
- Tauri for local-first desktop shells with native capabilities and web-based presentation layers.
- Next.js, Vite, Astro, Vue, Tailwind, and static JSON where their deployment or authoring models fit the project.
- WPF and native Windows UI frameworks for applications where desktop integration and stability matter more than web portability.

### Data and Artifact Formats

- TOML for manifests, schemas, configuration, command definitions, and operator-authored structured records.
- JSON and JSONL for interchange, audit streams, generated indexes, and machine output.
- Parquet and DuckDB for local analytical datasets and reproducible querying.
- SQLite for application-local relational storage.
- Markdown for durable human-readable documentation and generated reports.
- SVG for semantic visual assets, diagrams, logos, and embedded SESM metadata.
- ZIP, MSIX, MSI, NSIS, tar, SquashFS, and `tar.zst` for packaging and archival workflows.

### Infrastructure and Tooling

- PowerShell and Bash for orchestration and reproducible operator procedures.
- Docker for local infrastructure and service packaging.
- MongoDB and DuckDB for operational and analytical workloads.
- Ollama and local models for offline-assisted analysis and generation where appropriate.
- GitHub Actions and local verification scripts for builds, packaging, and release gates.
- SHA-256, BLAKE3, KangarooTwelve, and broader multi-hash suites for integrity and archival evidence.

---

## Repository and Release Philosophy

A repository should contain enough evidence to explain more than its source code.

Depending on project type and maturity, an APTlantis repository may include:

```text
Project-README.md
AGENTS.md
<Entity>.manifest.toml
docs/
templates/
examples/
schemas/
release-evidence/
artifacts/
CHANGELOG.md
Validation-Checklist.md
Adoption-Guide.md
Command-Contracts.md
Deployment-Record.md
```

Not every project requires every artifact. The applicable standard determines the contract.

### A Strong Release Record Answers

- What exact version was built?
- What command and environment produced it?
- Which tests ran, and what passed?
- What is the exact artifact filename and size?
- What is its SHA-256 or other declared integrity value?
- Is it signed, self-signed, or explicitly unsigned?
- Was installation, launch, upgrade, uninstall, and data preservation checked?
- Are release notes and core documentation delivered with the artifact?
- Where is the evidence preserved?

### A Strong Command Contract Answers

- What does the command do?
- Which inputs are accepted?
- What appears on stdout and stderr?
- Which exit codes are stable?
- Is machine-readable output opt-in and schema-defined?
- How are errors represented?
- What destructive behavior can occur?
- Is there a preview, dry-run, confirmation, or recovery path?

### A Strong Website Publication Record Answers

- What changed?
- What was built?
- Where was it deployed?
- Which routes were verified?
- Were accessibility and metadata checks performed?
- How can the deployment be rolled back?
- What monitoring or review cadence applies?

---

## About Project Status

APTlantis uses lifecycle labels to communicate reality rather than momentum.

| Status | Meaning |
|---|---|
| **Production** | Mature and presently treated as an authoritative or operational project, though further improvements may remain. |
| **Active** | Receiving current development or governance attention. |
| **Candidate Active** | Useful and intentionally advancing, but still collecting adoption, validation, or promotion evidence. |
| **In Progress** | Substantial work exists, but important implementation, verification, or governance requirements remain open. |
| **Prototype** | The architecture or workflow is being proved; destructive or public claims may remain intentionally constrained. |
| **Paused** | Retained and potentially useful, but not receiving current implementation priority. A high completion value may still be accurate. |
| **Draft** | The project identity and structure exist, but the public or governed form is still being assembled. |

Statuses are expected to change as evidence changes. Historical state should be preserved rather than rewritten as though the project had always been in its current form.

---

## APTlantis in One Sentence

**APTlantis is a governed ecosystem of local-first applications, standards, command tools, datasets, archival systems, and public evidence surfaces built to turn personal technical workflows into durable, verifiable software.**

---

## Evaluation Basis

This README reflects the project evaluation generated on **2026-07-30**, covering **37 projects** and recording lifecycle, completion, complexity, summaries, missing pieces, next steps, and potential improvements.

The evaluation is a portfolio snapshot, not a claim that every repository has passed fresh build, test, installation, publication, or release verification. Where those checks are missing, the evaluation records them as work rather than silently treating existing artifacts as current evidence.

---

<div align="center">

![Local First](https://img.shields.io/badge/local-first-2aa5bc?style=for-the-badge)
![Manifest Driven](https://img.shields.io/badge/manifest-driven-51678d?style=for-the-badge)
![Evidence First](https://img.shields.io/badge/evidence-first-2ea043?style=for-the-badge)
![Built for Operators](https://img.shields.io/badge/built_for-operators-8957e5?style=for-the-badge)

</div>
