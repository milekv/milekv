<div align="center">
  <h1>Miłosz Kordziński</h1>
  <p>Software engineer working on developer tools, backend systems and data-heavy applications.</p>
  <p>
    <a href="https://milekv.github.io/">Portfolio</a> |
    <a href="https://www.linkedin.com/in/milosz-kordzinski-a85947254">LinkedIn</a> |
    <a href="https://github.com/milekv?tab=repositories">Repositories</a>
  </p>
</div>

---

## Featured systems

### [ASK DATABASE](https://github.com/milekv/ask-database) - schema-aware NL-to-SQL

[Repository](https://github.com/milekv/ask-database) | [Static demo](https://milekv.github.io/ask-database/)

Ask a question about a database and get SQL with the reasoning context kept visible. The backend retrieves the relevant schema, glossary entries, aliases and sanitized historical queries, ranks relationship paths, generates structured SQL and validates it before returning it.

<details>
  <summary><strong>How it is built</strong></summary>
  <br />
  <ul>
    <li>Schema, Query and Correction Memory stored in PostgreSQL</li>
    <li>Deterministic schema retrieval and relationship-path ranking</li>
    <li>Backend LLM provider boundary with Structured Outputs and Zod</li>
    <li>Safe Mode restricts results to validated <code>SELECT</code> and <code>WITH</code> queries</li>
    <li>Evidence and a decision log are returned with generated SQL</li>
  </ul>
</details>

### [SQL Atlas](https://github.com/milekv/sql-atlas) - local-first SQL analysis

[Repository](https://github.com/milekv/sql-atlas) | [Live app](https://milekv.github.io/sql-atlas/) | [npm](https://www.npmjs.com/package/sql-atlas) | [VS Code](https://marketplace.visualstudio.com/items?itemName=Milosz.sql-atlas)

Deterministic SQL analysis for the browser, terminal, pull requests and VS Code. SQL Atlas detects anti-patterns, explains findings, suggests indexes from query structure and compares PostgreSQL, MySQL, Oracle, SQLite and SQL Server. Analysis runs locally without uploading queries to a service.

<details>
  <summary><strong>What is inside</strong></summary>
  <br />
  <ul>
    <li>Rule-based analyzer with severity, scoring and passed checks</li>
    <li>Index suggestions based on filters, joins, grouping and ordering</li>
    <li>PostgreSQL EXPLAIN JSON parser with metrics, execution tree and risk detection</li>
    <li>Before and after rewrites, query map and Markdown report export</li>
    <li>CLI with text, JSON, Markdown and SARIF output</li>
    <li>GitHub Action annotations and local VS Code diagnostics</li>
  </ul>
</details>

### [VisualDB Studio](https://github.com/milekv/visualdb-studio) - visual schema design

[Repository](https://github.com/milekv/visualdb-studio) | [Live app](https://milekv.github.io/visualdb-studio/)

An interactive PostgreSQL schema modeller. Tables and relationships are edited on a visual canvas. The resulting model can be validated, scored and exported as SQL without hiding the underlying database design.

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

### [OraBank](https://github.com/milekv/oracle-bank-system) - Oracle database engineering

[Repository](https://github.com/milekv/oracle-bank-system) | [Walkthrough](https://milekv.github.io/orabank-site/)

An Oracle SQL and PL/SQL project covering customers, accounts, cards, transfers, loans and audit data. The transfer package uses deterministic row locking, savepoints and paired transaction records without hiding commits from callers.

<details>
  <summary><strong>Database engineering scope</strong></summary>
  <br />
  <ul>
    <li>SQL and PL/SQL packages for accounts, balances, loans and transfers</li>
    <li>Indexing, query analysis and optional interval partitioning</li>
    <li>Roles, privileges, reporting views and audit access</li>
    <li>Scheduler jobs plus backup and recovery runbooks</li>
    <li>Validation and smoke-test scripts for an Oracle environment</li>
  </ul>
</details>

## Working stack

- Application: TypeScript, React, Node.js, Fastify
- Data: PostgreSQL, Oracle, Supabase
- Delivery: GitHub Actions, Docker, Vercel

## Currently building

**RehabOS** is software for physiotherapy practices. The work covers clinic operations, therapist workflows and the patient side of care between visits. It is still in development and is not presented here as a finished public product.

## Open source

<details>
  <summary><strong>Recent merged pull requests</strong></summary>
  <br />
  <ul>
    <li><a href="https://github.com/Truta446/nplusone/pull/13">Truta446/nplusone #13</a> - added tested LibSQL and Turso adapter support and was credited in the project changelog</li>
  </ul>
</details>
