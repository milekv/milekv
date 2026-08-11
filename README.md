<div align="center">
  <h1>Miłosz Kordziński</h1>
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=2F81F7&center=true&vCenter=true&width=760&lines=Software+%26+Data+Engineer;Automation+%26+Systems+Builder;Business+Systems+%C2%B7+Developer+Tools+%C2%B7+Data+Products"
    alt="Software & Data Engineer · Automation & Systems Builder"
  />
  <p>
    I build business systems, workflow automation, developer tools and
    data-heavy software — from the interface and backend to the database,
    integrations and deployment.
  </p>
  <p>
    <a href="https://milekv.github.io/">Portfolio</a> ·
    <a href="https://www.linkedin.com/in/milosz-kordzinski-a85947254">LinkedIn</a> ·
    <a href="https://github.com/milekv?tab=repositories">Repositories</a>
  </p>
</div>

---

## Featured systems

### [ASK DATABASE](https://github.com/milekv/ask-database) — schema-aware NL-to-SQL

[![Repository](https://img.shields.io/badge/source-GitHub-181717?style=flat-square&logo=github)](https://github.com/milekv/ask-database)
[![Static demo](https://img.shields.io/badge/demo-static-2F81F7?style=flat-square&logo=githubpages)](https://milekv.github.io/ask-database/)

Ask a question about a database and get SQL with the reasoning context kept
visible. The backend retrieves the relevant schema, glossary entries, aliases and
sanitized historical queries; ranks relationship paths; generates structured SQL;
then validates it before returning it.

<details>
  <summary><strong>How it is built</strong></summary>
  <br />
  <ul>
    <li>Schema, Query and Correction Memory stored in PostgreSQL</li>
    <li>Deterministic schema retrieval and relationship-path ranking</li>
    <li>Backend LLM provider boundary with Structured Outputs and Zod</li>
    <li>Safe Mode restricts results to validated <code>SELECT</code>/<code>WITH</code> queries</li>
    <li>Evidence and a decision log are returned with generated SQL</li>
  </ul>
</details>

### [SQL Atlas](https://github.com/milekv/sql-atlas) — local-first SQL analysis

[![Repository](https://img.shields.io/badge/source-GitHub-181717?style=flat-square&logo=github)](https://github.com/milekv/sql-atlas)
[![Live app](https://img.shields.io/badge/app-live-238636?style=flat-square&logo=githubpages)](https://milekv.github.io/sql-atlas/)

Deterministic analysis that runs entirely in the browser. SQL Atlas detects
anti-patterns, explains findings, suggests indexes from query structure, maps
clauses and compares PostgreSQL, MySQL, Oracle, SQLite and SQL Server. Queries are
not uploaded to a server.

<details>
  <summary><strong>What is inside</strong></summary>
  <br />
  <ul>
    <li>Rule-based analyzer with severity, scoring and passed checks</li>
    <li>Index suggestions based on filters, joins, grouping and ordering</li>
    <li>Before/after rewrites, query map and Markdown report export</li>
    <li>Roadmap: EXPLAIN JSON, CLI and GitHub Action checks</li>
  </ul>
</details>

### [VisualDB Studio](https://github.com/milekv/visualdb-studio) — visual schema design

[![Repository](https://img.shields.io/badge/source-GitHub-181717?style=flat-square&logo=github)](https://github.com/milekv/visualdb-studio)
[![Live app](https://img.shields.io/badge/app-live-238636?style=flat-square&logo=githubpages)](https://milekv.github.io/visualdb-studio/)

An interactive PostgreSQL schema modeller. Tables and relationships are edited on
a visual canvas; the resulting model can be validated, scored and exported as SQL
without hiding the underlying database design.

<details>
  <summary><strong>Capabilities</strong></summary>
  <br />
  <ul>
    <li>Table, column, key, constraint and relationship editing</li>
    <li>PostgreSQL DDL generation, including indexes and foreign keys</li>
    <li>Schema validation, quality scoring and index recommendations</li>
    <li>Templates and suggestions for extending an existing model</li>
  </ul>
</details>

### [OraBank](https://github.com/milekv/oracle-bank-system) — Oracle banking architecture

[![Source](https://img.shields.io/badge/source-SQL%20%2F%20PLSQL-F80000?style=flat-square&logo=oracle)](https://github.com/milekv/oracle-bank-system)
[![Walkthrough](https://img.shields.io/badge/project-walkthrough-2F81F7?style=flat-square&logo=githubpages)](https://milekv.github.io/orabank-site/)

A realistic Oracle database architecture split into core, transaction,
administration and reporting domains. It models customers, accounts, cards,
transfers, loans and audit data rather than stopping at a small demo schema.

<details>
  <summary><strong>Database engineering scope</strong></summary>
  <br />
  <ul>
    <li>SQL and PL/SQL packages for accounts, balances and transfers</li>
    <li>Indexing, query analysis and range partitioning</li>
    <li>Roles, privileges, reporting views and audit access</li>
    <li>Scheduler jobs plus backup and recovery scenarios</li>
  </ul>
</details>

## How I approach a system

```mermaid
flowchart LR
  Problem["Operational problem"] --> Process["Process and failure cases"]
  Process --> Product["Product interface"]
  Product --> API["Backend and integrations"]
  API --> Data["Data model and persistence"]
  Data --> Automation["Automation and observability"]
  Automation --> Process
```

| Area | Typical work | Main tools |
| --- | --- | --- |
| Business systems | Internal tools, SaaS workflows, process automation | TypeScript, React, Node.js, Supabase |
| Data systems | Data modelling, migrations, retrieval, performance | PostgreSQL, Oracle, SQL |
| Developer tools | Local-first analysis, generators, CI checks | TypeScript, Vite, GitHub Actions |
| Integrations | APIs, webhooks, data exchange and scheduled work | Fastify, REST, Docker, cloud services |

## Currently building

> **RehabOS** — an operating system for physiotherapy practices and clinics,
> connecting clinic operations, therapists and patients across the therapy
> process.

I am also extending the SQL tooling direction toward EXPLAIN-plan analysis, CLI
workflows and repository-level checks, while continuing to build automation around
real operational handoffs.

## Open source

<details>
  <summary><strong>Recent merged pull requests</strong></summary>
  <br />
  <ul>
    <li><a href="https://github.com/tungbq/devops-project/pull/128">tungbq/devops-project #128</a> — corrected a Terraform VPN access guideline</li>
    <li><a href="https://github.com/vitorfranklin/retrohost/pull/26">vitorfranklin/retrohost #26</a> — resolved Markdown lint issues</li>
    <li><a href="https://github.com/thomaspinder/GPJax/pull/685">thomaspinder/GPJax #685</a> — corrected GraphKernel spectral documentation</li>
    <li><a href="https://github.com/rodrigo-arenas/Sklearn-genetic-opt/pull/304">Sklearn-genetic-opt #304</a> — updated community documentation references</li>
  </ul>
</details>

---

<div align="center">
  <strong>Build the whole system. Keep the moving parts visible.</strong>
  <br /><br />
  <a href="https://github.com/milekv">GitHub</a> ·
  <a href="https://www.linkedin.com/in/milosz-kordzinski-a85947254">LinkedIn</a> ·
  <a href="https://milekv.github.io/">Portfolio</a>
</div>
