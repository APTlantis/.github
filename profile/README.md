<div align="center">

# APTlantis

### Local-first software, governed engineering systems, archival infrastructure, and operator-focused tools.

![Projects](https://img.shields.io/badge/projects-27-2aa5bc?style=for-the-badge)
![Average Completion](https://img.shields.io/badge/average_completion-82.9%25-8957e5?style=for-the-badge)
![Production](https://img.shields.io/badge/production-6-2ea043?style=for-the-badge)
![Evaluated](https://img.shields.io/badge/evaluated-2026--08--23-51678d?style=for-the-badge)

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

The current evaluation covers **27 projects** with an average assessed completion of **82.9%**.

| Metric | Current Evaluation |
|---|---:|
| Total projects | **27** |
| Average completion | **82.9%** |
| Production | **6** |
| In progress | **18** |
| Maintenance | **1** |
| Paused | **1** |
| Prototype | **1** |
| High complexity | **17** |
| Medium complexity | **10** |

This snapshot reflects the projects explicitly registered for the August 23 evaluation. A lower project count than the prior snapshot means the evaluated portfolio boundary changed; it does not imply that repositories were deleted.

### How to Read These Numbers

A completion percentage is an assessment of how much of the intended project exists. It is **not** a substitute for lifecycle state or release verification.

A project may be highly complete but paused, in maintenance, awaiting a lifecycle decision, missing a release-evidence bundle, or blocked on packaging and verification. Likewise, an in-progress standard may already be useful while still requiring validators, examples, adoption evidence, or promotion work.

APTlantis therefore treats these as separate questions:

- **Completion:** How much of the intended system exists?
- **Lifecycle:** Is the project in progress, paused, maintained, prototyped, or considered production?
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

These projects currently provide a representative cross-section of APTlantis: governance, datasets, desktop software, command tooling, and portfolio intelligence. Inclusion reflects architectural importance and representative value, not only lifecycle state.

### DRS — Desktop Release Standard

![Status](https://img.shields.io/badge/status-Production-2ea043?style=flat-square)
![Completion](https://img.shields.io/badge/completion-96%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-High-b7410e?style=flat-square)

DRS defines release readiness for local-first Windows desktop applications, including versioning, release notes, adopter manifests, artifact naming, hashes, signing, documentation, verification evidence, distribution posture, and release gates. It operates as a mature SFDS-governed standard suite with PowerShell and Python validation tools, templates, schemas, examples, and adoption guidance.

### WGS — Workspace Governance Standard

![Status](https://img.shields.io/badge/status-In_Progress-8957e5?style=flat-square)
![Completion](https://img.shields.io/badge/completion-92%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-High-b7410e?style=flat-square)

WGS governs Aptlantis workspace structure, entity registration, manifest conventions, lifecycle visibility, standard relationships, agent orientation, shared services, and workspace health. It uses manifests, read-first documents, templates, audit tools, inventories, and structured JSONL records to keep the local workspace discoverable and recoverable.

### CratesDataset

![Status](https://img.shields.io/badge/status-In_Progress-8957e5?style=flat-square)
![Completion](https://img.shields.io/badge/completion-93%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-High-b7410e?style=flat-square)

Rust CLI dataset foundry that converts immutable monthly crates.io JSONL snapshots into eight deterministic, provenance-rich datasets in JSONL-Zstandard and Parquet formats, with bounded partition processing, validation, integrity manifests, and a gated Hugging Face publication adapter.

### CommandWizard

![Status](https://img.shields.io/badge/status-Production-2ea043?style=flat-square)
![Completion](https://img.shields.io/badge/completion-90%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-High-b7410e?style=flat-square)

Local-first Tauri desktop application for importing, editing, organizing, and generating CLI command workflows from TOML schemas. It stores schemas, favorites, logs, managed scripts, and launcher shims locally, while keeping generated command execution outside the current safety boundary.

### Filing Cabinet

![Status](https://img.shields.io/badge/status-Maintenance-51678d?style=flat-square)
![Completion](https://img.shields.io/badge/completion-88%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-High-b7410e?style=flat-square)

A local-first Windows WPF vault that ingests selected technical artifacts, stores them with catalog metadata and hashes, generates previews and extracted text, exposes health findings, and supports operator-controlled repair, recovery, verification, search, and export.

### AnalyzeProjects

![Status](https://img.shields.io/badge/status-In_Progress-8957e5?style=flat-square)
![Completion](https://img.shields.io/badge/completion-85%25-2aa5bc?style=flat-square)
![Complexity](https://img.shields.io/badge/complexity-High-b7410e?style=flat-square)

AnalyzeProjects scans the explicitly registered Aptlantis portfolio, applies group-specific governance prompts, normalizes model responses into structured project records, and compiles JSON and Markdown dashboard outputs. It is a Python analysis utility supporting local verification with optional OpenAI-compatible model calls.

---

## Standards and Governance Suite

APTlantis standards are not generic policy documents. Each standard defines a bounded delivery or governance problem and supplies the artifacts needed to apply it.

| Standard | Status | Completion | Governs |
|---|---:|---:|---|
| **WGS** | In Progress | 92% | Workspace structure, manifests, lifecycle, agent orientation, audits, and recovery |
| **SFDS** | Production | 96% | How standards are authored, versioned, validated, adopted, and preserved |
| **PPS** | In Progress | 86% | Project intent, boundaries, success and failure criteria, risks, roadmaps, and readiness |
| **DRS** | Production | 96% | Local-first Windows desktop releases, evidence, integrity, packaging, and verification |
| **CTS** | In Progress | 91% | CLI contracts, exit codes, structured output, destructive behavior, and automation compatibility |
| **WDS** | In Progress | 84% | Web manifests, deployment evidence, accessibility, routes, rollback, and monitoring |
| **LDS** | In Progress | 85% | Library interfaces, stability, compatibility, extension contracts, and consumers |
| **AAMHS** | In Progress | 84% | Preservation-oriented hash manifests, detached signatures, validation, and integrity records |
| **SESM** | In Progress | 88% | Structured provenance and semantic metadata embedded in SVG assets |
| **BlueSlate** | In Progress | 70% | Visual tokens, layout patterns, framework profiles, starter packs, and adoption evidence |

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
6. **SESM** and **BlueSlate** govern semantic visual metadata and interface language where appropriate.

The goal is not maximum process. The goal is enough explicit structure that a future operator or agent can answer: what is this, why does it exist, what state is it in, how is it built, what evidence exists, and what remains unresolved?

---

## Project Catalog

### Governance and Standards Projects

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **DRS** | Production | 96% | DRS defines release readiness for local-first Windows desktop applications, including versioning, release notes, adopter manifests, artifact naming, hashes, signing, documentation, verification evidence, distribution posture, and release gates. It operates as a mature SFDS-governed standard suite with PowerShell and Python validation tools, templates, schemas, examples, and adoption guidance. |
| **SFDS** | Production | 96% | SFDS defines the structure, metadata, adoption process, validation boundaries, compatibility rules, and preservation practices for Aptlantis standards. It provides a suite manifest schema, templates, examples, manual guidance, and an executable structural validator. |
| **WGS** | In Progress | 92% | WGS governs Aptlantis workspace structure, entity registration, manifest conventions, lifecycle visibility, standard relationships, agent orientation, shared services, and workspace health. It uses manifests, read-first documents, templates, audit tools, inventories, and structured JSONL records to keep the local workspace discoverable and recoverable. |
| **CTS** | In Progress | 91% | CTS is a candidate Aptlantis governance standard for CLI tools and automation utilities. It defines command contracts, exit codes, stdout/stderr separation, structured output envelopes, stability rules, destructive-command safeguards, distribution posture, and release verification relationships. |
| **PPS** | In Progress | 86% | PPS defines the pre-implementation record for Aptlantis projects, covering mission, boundaries, success and failure criteria, constraints, risks, responsibility posture, roadmap, version completion shape, and handoff to WGS and delivery standards. |
| **LDS** | In Progress | 85% | LDS governs library crates, packages, and SDKs consumed by other code. It defines interface notes, stability levels, semver and breaking-change policies, extension contracts, runtime constraints, consumer tracking, adoption guidance, and lightweight validation. |
| **AAMHS** | In Progress | 84% | AAMHS governs preservation-oriented archive integrity through hash manifests, optional detached signatures, validation procedures, and integrity records. It supplies schemas, templates, examples, adoption guidance, and lightweight Python validators, while delegating release-artifact hashing to ARHS. |
| **WDS** | In Progress | 84% | WDS governs website and web-application manifests, deployment evidence, accessibility and metadata checks, route verification, rollback expectations, and monitoring records. It is an active candidate standard integrated with SFDS, WGS, and PPS. |

### Desktop and Operator Applications

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **CommandWizard** | Production | 90% | Local-first Tauri desktop application for importing, editing, organizing, and generating CLI command workflows from TOML schemas. It stores schemas, favorites, logs, managed scripts, and launcher shims locally, while keeping generated command execution outside the current safety boundary. |
| **Filing Cabinet** | Maintenance | 88% | A local-first Windows WPF vault that ingests selected technical artifacts, stores them with catalog metadata and hashes, generates previews and extracted text, exposes health findings, and supports operator-controlled repair, recovery, verification, search, and export. |
| **Structra** | Production | 86% | Structra is a local-first Windows Tauri application for visually editing structured data, inspecting its hierarchy, validating documents, transforming values or schemas, and previewing JSON, YAML, TOML, and XML output. It serves as a maintained DRS desktop workspace and locally verified release artifact. |
| **ChromeArchivalPlugin** | In Progress | 85% | A local-first Chrome/Chromium MV3 extension that captures page lists, links, metadata, Markdown, screenshots, and PDFs into browser storage and deterministic download folders for Aptlantis archival workflows. |
| **Chat** | In Progress | 85% | ChatArchive is a Tauri desktop archive that imports OpenAI conversation exports through Rust, normalizes conversations and artifacts into a filesystem-backed library, stores searchable state in SQLite, and provides browsing, search, organization, rendering, and export workflows. |
| **AptlantisConsole** | In Progress | 82% | A Tauri 2 Windows desktop console combining a Next.js operator dashboard with local command workflows, infrastructure controls, terminals, editors, database tools, intake records, embeddings, and operational logs. |
| **Ops Control Surface** | In Progress | 70% | A local-first Tauri desktop workspace for creating, editing, moving, relating, deleting, and reviewing typed Aptlantis operational objects. It uses a React interface, Rust commands, SQLite persistence, managed project artifact storage, and release-readiness receipts. |
| **Theme-Preview** | In Progress | 70% | A local-first Tauri desktop workbench that loads TOML component, theme, variant, group, source, and page metadata, renders deterministic previews, and produces screenshot and validation reports for Aptlantis UI systems. |
| **CodeNote** | Prototype | 65% | CodeNote is a local-first Tauri desktop editor for Markdown and text files. It combines CodeMirror editing, live remark/rehype preview, vendored Prism highlighting, Mermaid diagrams, tabs, and an optional native PowerShell PTY drawer in one window. It serves as a focused personal editing utility within the DRS project group. |

### Command Tools and Evaluation Pipelines

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **Archive Hasher** | Production | 90% | Two Go CLIs implement the AAMHS publication workflow: archive-hasher computes eight hashes for an archive and writes snapshot-hashes.txt, while manifest-signer creates detached PGP and optional SLH-DSA signatures without changing the manifest. |
| **Analyze-Projects** | In Progress | 85% | AnalyzeProjects scans the explicitly registered Aptlantis portfolio, applies group-specific governance prompts, normalizes model responses into structured project records, and compiles JSON and Markdown dashboard outputs. It is a Python analysis utility supporting local verification with optional OpenAI-compatible model calls. |
| **Single-Project Evaluator** | In Progress | 72% | A read-only Python CLI that inventories one target project, extracts manifest and governance context, prepares bounded reasoning inputs, and writes structured evaluation and provenance artifacts without modifying or executing the target project. |
| **ReleaseHasher** | In Progress | 70% | Go CLI that hashes one regular release artifact with SHA256, BLAKE3-256, and 128-byte KT128, then writes a TOML hash manifest and optionally returns JSON result metadata. It provides a small CTS release-hashing utility for Aptlantis publication workflows. |
| **ConversionTools** | In Progress | 65% | A local collection of interactive audio, speech-transcription, and video-to-MP4 workflows. Rust utilities invoke FFmpeg for media conversion, while a Python CPU-Whisper utility produces transcripts. It serves as a CTS-governed personal conversion toolbox within Aptlantis. |

### Datasets, Mirrors, and Research Systems

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **CloneCratesio** | Production | 94% | Go and Python command-tool pipeline that clones a local crates.io index, downloads crate archives at registry scale, optionally writes rolling tar.zst bundles, generates sidecar metadata, restores bundles, and exposes Prometheus and pprof telemetry. |
| **CratesDataset** | In Progress | 93% | Rust CLI dataset foundry that converts immutable monthly crates.io JSONL snapshots into eight deterministic, provenance-rich datasets in JSONL-Zstandard and Parquet formats, with bounded partition processing, validation, integrity manifests, and a gated Hugging Face publication adapter. |

### Visual, Asset, and Semantic Systems

| Project | Status | Completion | Description |
|---|---:|---:|---|
| **SESM** | In Progress | 88% | SESM defines embedded JSON metadata for SVG assets, covering identity, provenance, themes, UI context, archival hints, integrity claims, and non-authoritative LLM context. It provides schemas, embedding and conversion tools, safe-profile validation, fixtures, and adoption guidance for Aptlantis Studio and related indexing, archive, and pipeline workflows. |
| **AptlantisLogos** | Paused | 75% | A paused local asset-tooling project that preserves logo source material, rendered formats, palettes, themes, metadata, and generation scripts for Aptlantis and related project assets. |
| **BlueSlate** | In Progress | 70% | BlueSlate is a candidate-active visual-system standard defining semantic design tokens, layout patterns, framework profiles, starter packs, and adoption evidence for Aptlantis tools, dashboards, project pages, and Windows utilities. |

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

1. **Verification trails still need closing.** Tagged releases, installers, uninstall behavior, published archives, checksums, and current build evidence remain open for several projects.
2. **Governance records can drift from implementation.** Schemas, manifests, child registrations, guidance, examples, and promoted copies need routine reconciliation.
3. **Command contracts need consistent adoption.** CTS-governed tools still need stable exit codes, version output, structured results, stdout/stderr rules, and documented error behavior.
4. **Destructive actions need explicit safeguards.** Overwrite, replacement, migration, and publishing workflows benefit from preview, confirmation, recovery, and disposable-environment qualification.
5. **Provenance and distribution decisions must be recorded.** Dependency origins, licensing bases, redistribution authority, build inputs, and publication approvals remain material evidence.
6. **Standards benefit from executable conformance.** Machine-readable validator output, fixtures, cross-field checks, and adopter coverage turn mature documentation into repeatable verification.
7. **Lifecycle labels describe operating posture, not quality.** Production, maintenance, paused, in-progress, and prototype states answer a different question from completion.

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
| **Maintenance** | Operational and retained, with attention focused on reliability, compatibility, and selective improvements rather than expansion. |
| **In Progress** | Substantial work exists, but important implementation, verification, or governance requirements remain open. |
| **Prototype** | The architecture or workflow is being proved; destructive or public claims may remain intentionally constrained. |
| **Paused** | Retained and potentially useful, but not receiving current implementation priority. A high completion value may still be accurate. |

Statuses are expected to change as evidence changes. Historical state should be preserved rather than rewritten as though the project had always been in its current form.

---

## APTlantis in One Sentence

**APTlantis is a governed ecosystem of local-first applications, standards, command tools, datasets, archival systems, and public evidence surfaces built to turn personal technical workflows into durable, verifiable software.**

---

## Evaluation Basis

This README reflects the project evaluation generated on **2026-08-23**, covering **27 explicitly registered projects** and recording lifecycle, completion, complexity, summaries, missing pieces, next steps, and potential improvements.

The evaluation is a portfolio snapshot, not a claim that every repository has passed fresh build, test, installation, publication, or release verification. Where those checks are missing, the evaluation records them as work rather than silently treating existing artifacts as current evidence.

The evaluated set is intentionally determined by the AnalyzeProjects project index. Changes in the total project count between snapshots may therefore reflect a change in portfolio scope as well as project creation, archival, or lifecycle work.

---

<div align="center">

![Local First](https://img.shields.io/badge/local-first-2aa5bc?style=for-the-badge)
![Manifest Driven](https://img.shields.io/badge/manifest-driven-51678d?style=for-the-badge)
![Evidence First](https://img.shields.io/badge/evidence-first-2ea043?style=for-the-badge)
![Built for Operators](https://img.shields.io/badge/built_for-operators-8957e5?style=for-the-badge)

</div>
