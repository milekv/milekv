# Miłosz Kordziński

Software engineer building data-heavy applications and developer tools with
TypeScript, SQL and PostgreSQL. My recent work combines database systems,
deterministic analysis and model-assisted workflows.

Based in Wrocław, Poland. Open to mid-level software engineering roles involving
backend systems, databases or developer tooling.

[Portfolio](https://milekv.github.io/) |
[LinkedIn](https://www.linkedin.com/in/milosz-kordzinski-a85947254) |
[Repositories](https://github.com/milekv?tab=repositories)

## Selected work

### [SQL Atlas](https://github.com/milekv/sql-atlas)

Local SQL analysis for the terminal, pull requests, VS Code and the browser.
The same deterministic analyzer powers a published npm CLI, a GitHub Action
and editor diagnostics without sending queries to a remote service.

- Rule configuration and inline ignores
- PostgreSQL parsing and EXPLAIN JSON analysis
- Text, JSON, Markdown and SARIF output
- Automated tests, CI and semantic releases

[Live app](https://milekv.github.io/sql-atlas/) |
[npm](https://www.npmjs.com/package/sql-atlas) |
[VS Code](https://marketplace.visualstudio.com/items?itemName=Milosz.sql-atlas)

### [Ask Database](https://github.com/milekv/ask-database)

A schema-aware natural-language-to-SQL workspace. The backend retrieves
relevant schema context, ranks relationship paths, requests structured output
and validates generated SQL before returning it.

- PostgreSQL persistence for schemas, glossary terms and query memory
- Fastify API with an explicit provider boundary and Zod validation
- Safe Mode limited to validated `SELECT` and `WITH` statements

[Static demo](https://milekv.github.io/ask-database/)

### [VisualDB Studio](https://github.com/milekv/visualdb-studio)

A local PostgreSQL schema designer with an interactive relationship canvas,
deterministic validation and DDL export. Projects stay in browser storage and
require no account or backend.

[Live app](https://milekv.github.io/visualdb-studio/)

### [OraBank](https://github.com/milekv/oracle-bank-system)

An Oracle SQL and PL/SQL banking system covering transactional consistency,
deterministic row locking, savepoints, indexing, privileges, auditing and
operational runbooks.

[Walkthrough](https://milekv.github.io/orabank-site/)

## Open source

- [Truta446/nplusone #13](https://github.com/Truta446/nplusone/pull/13) -
  added tested LibSQL and Turso adapter support
- [Truta446/nplusone #29](https://github.com/Truta446/nplusone/pull/29) -
  added an MSSQL adapter with query, parameter and stored procedure coverage

I also contribute fixes and tests to database and developer tooling projects
when I can reproduce a concrete problem.

## Stack

TypeScript, Node.js, React, PostgreSQL, Oracle, Fastify, Docker and GitHub
Actions.
