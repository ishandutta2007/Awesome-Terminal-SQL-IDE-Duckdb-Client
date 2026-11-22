# Awesome-Terminal-SQL-IDE-Duckdb-Client
# Awesome-Terminal-SQL-IDE-Duckdb-Client

## Top Terminal SQL IDE & DuckDB Client Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  

*Focused on Terminal SQL IDEs, DuckDB Clients, Local Analytics & Data Exploration*  

**Last updated: November 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Terminal SQL IDEs & DuckDB Clients**. These tools enable developers, data engineers, and analysts to query, explore, visualize, and manage local files (Parquet, CSV, JSON) and databases (DuckDB, PostgreSQL, SQLite, Snowflake, BigQuery) directly from the terminal or lightweight clients.



**Examples** include tconbeer/harlequin, DuckDB CLI, VisiData, Gobang, Rainfrog, SQLit, Beekeeper Studio, DBeaver Community, Metabase, Evidence, MotherDuck, DataGrip, TablePlus, Hex, Deepnote, Observable, and Supabase Studio.



**Open-source emphasis**: This list heavily expands on active open-source terminal SQL IDEs, TUI database clients, DuckDB-native interfaces, and self-hosted SQL notebooks/BI tools — ideal for data engineers, analytics engineers, and developers building fast local-first data workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[MotherDuck](https://motherduck.com)**  

  Cloud analytics platform powered by DuckDB that seamlessly combines local DuckDB execution with serverless cloud storage and collaboration.



- **[DBeaver Cloud](https://dbeaver.com)**  

  Cloud-based collaborative database management and SQL IDE platform from the creators of DBeaver with team workspaces and shared connections.



- **[JetBrains DataGrip](https://jetbrains.com)**  

  Commercial cross-platform database IDE offering intelligent SQL completion, schema navigation, query refactoring, and DuckDB support.



- **[TablePlus](https://tableplus.com)**  

  Native, lightweight commercial GUI client for relational and embedded databases including DuckDB, PostgreSQL, MySQL, and SQLite.



- **[Hex](https://hex.tech)**  

  Collaborative cloud data workspace combining SQL, Python, DuckDB cells, and interactive data apps for analytics teams.



- **[Deepnote](https://deepnote.com)**  

  Cloud-based collaborative data science notebook with native SQL blocks, DuckDB integration, and real-time team editing.



- **[Observable](https://observablehq.com)**  

  Web-based platform for collaborative data analysis, reactive SQL/JavaScript notebooks, and interactive dashboards with built-in DuckDB-Wasm support.





## Open-Source GitHub Projects



- **[Harlequin (tconbeer/harlequin)](https://github.com)**  

  Feature-rich, cross-platform terminal SQL IDE built with Textual, featuring a DuckDB default adapter, data catalog browser, syntax-highlighted editor, and interactive results viewer.



- **[DuckDB CLI](https://github.com)**  

  Official fast in-process analytical SQL database engine with a built-in interactive terminal shell supporting direct Parquet, CSV, JSON, and S3 querying.



- **[VisiData](https://github.com)**  

  Interactive multitool for tabular data in the terminal that natively opens DuckDB databases, SQLite, Parquet, and CSV files for instant exploration.



- **[Beekeeper Studio](https://github.com)**  

  Modern, open-source cross-platform SQL editor and database manager with a clean interface and community support for DuckDB, Postgres, and SQLite.



- **[DBeaver Community Edition](https://github.com)**  

  Popular open-source universal database tool supporting DuckDB via JDBC alongside dozens of relational and analytical databases.



- **[Supabase Studio](https://github.com)**  

  Open-source web-based database management interface and SQL editor built for PostgreSQL, available for local self-hosting via Docker.



- **[Metabase](https://github.com)**  

  Open-source business intelligence and SQL exploration platform with community DuckDB driver support for self-hosted dashboards.



- **[Rainfrog](https://github.com)**  

  Lightweight, Vim-inspired terminal database management TUI written in Rust for fast keyboard-driven querying and schema inspection.



- **[Gobang](https://github.com)**  

  Cross-platform TUI database management tool written in Rust supporting PostgreSQL, MySQL, and SQLite directly in the terminal.



- **[usql](https://github.com)**  

  Universal command-line interface inspired by `psql` that provides a unified terminal prompt for DuckDB, PostgreSQL, MySQL, SQLite, and dozens of other databases.



- **[litecli / pgcli / mycli](https://github.com)**  

  Family of open-source terminal SQL clients with intelligent auto-completion and syntax highlighting for SQLite, PostgreSQL, and MySQL.



- **[Evidence](https://github.com)**  

  Open-source code-first business intelligence framework that uses Markdown and SQL powered by DuckDB to build fast static and interactive data apps.



- **[DuckDB UI (Official Local Web UI)](https://github.com-ui)**  

  Local browser-based notebook interface launched directly from the DuckDB CLI (`duckdb -ui`) for interactive SQL cells and schema exploration.



### Additional Strong Open-Source Options



- **[lazysql](https://github.com)** — Cross-platform TUI database management tool written in Go with Vim keybindings.

- **[dblab](https://github.com)** — Interactive terminal client for PostgreSQL, MySQL, and SQLite built in Go.

- **[sq](https://github.com)** — Swiss-army knife CLI tool to inspect, query, join, and convert SQL databases and flat files.

- **[Roapi](https://github.com)** — Automatically spin up read-only SQL/REST/GraphQL APIs on top of static Parquet, CSV, and DuckDB datasets.

- **[JupyterLab + JupySQL](https://github.com)** — Open-source notebook workflow for running DuckDB and SQL queries with minimal memory overhead.

- **[Apache Superset](https://github.com)** — Enterprise-ready open-source data exploration and visualization platform with DuckDB SQLAlchemy support.

- **[Dataherald / Vanna](https://github.com)** — Open-source natural-language-to-SQL frameworks compatible with DuckDB and local LLMs.



**Frameworks for building custom systems**: Combine **Harlequin** + **DuckDB CLI** + **VisiData** for terminal-first data engineering, or pair **DuckDB** with **Evidence**, **Metabase**, and **Ollama** for self-hosted analytical stacks.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Terminal SQL clients and DuckDB extensions may execute arbitrary local file reads or network requests; verify queries and credentials in shared environments.

- Self-hosted analytics and BI platforms require proper authentication and access controls when exposed over a network.



---



**Made for data engineers, analytics engineers, SQL power users, and open-source developers.**  

Let's make terminal SQL workflows and local-first analytics faster, open, and keyboard-driven.
