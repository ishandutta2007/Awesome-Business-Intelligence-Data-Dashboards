# Awesome-Business-Intelligence-Data-Dashboards

# Top Business Intelligence & Data Dashboards Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Self-Service BI, Interactive Data Dashboards, Semantic Metrics Layers, BI-as-Code & Embedded Analytics*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Business Intelligence & Data Dashboards**. These tools query, model, visualize, explore, and share interactive business metrics, SQL/DuckDB analytics, and real-time operational dashboards across cloud data warehouses, lakehouses, and self-hosted analytics servers.

**Examples** include Tableau Cloud, Microsoft Power BI, Looker, Domo, Sisense, Metabase Cloud, Sigma Computing, ThoughtSpot, Qlik Sense, GoodData, and preset-io/agor (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted BI platforms (`Apache Superset`, `Metabase`, `Lightdash`, `Redash`), BI-as-Code & DuckDB-native dashboards (`Evidence`, `Rill Data`, `preset-io/agor`), and interactive data notebooks (`Observable Framework`, `Grafana`) — ideal for data analysts, analytics engineers, BI architects, and developers building transparent, version-controlled reporting systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tableau Cloud (Salesforce)](https://tableau.com)**  
  Enterprise visual analytics and business intelligence platform enabling interactive dashboard authoring, AI-assisted insights, and governed enterprise data sharing.

- **[Microsoft Power BI](https://microsoft.com)**  
  Widely adopted cloud business analytics service offering interactive data modeling (DAX), drag-and-drop report building, and tight Microsoft 365/Fabric integration.

- **[Looker (Google Cloud)](https://google.com)**  
  Enterprise BI and semantic modeling platform powered by LookML to define governed metrics once and power consistent dashboards and embedded analytics.

- **[Sigma Computing](https://sigmacomputing.com)**  
  Cloud-native analytics and BI platform featuring a familiar spreadsheet-like interface engineered to explore billions of rows directly inside cloud data warehouses.

- **[ThoughtSpot](https://thoughtspot.com)**  
  AI-powered self-service analytics platform enabling business users to query cloud data warehouses using natural-language search and automated Liveboards.

- **[Domo](https://domo.com)**  
  Cloud business intelligence and data experience platform combining ETL connectors, real-time executive dashboards, automated alerts, and custom data apps.

- **[Qlik Sense (Qlik Cloud)](https://qlik.com)**  
  Associative analytics and cloud BI platform offering in-memory data indexing, interactive visual exploration, and augmented AI dashboard generation.

- **[Sisense](https://sisense.com)**  
  API-first cloud analytics and embedded BI platform allowing product teams to compose customizable white-label dashboards directly into SaaS applications.

- **[GoodData](https://gooddata.com)**  
  Composable cloud BI and analytics-as-code platform supporting multi-tenant embedded dashboards, semantic models, and declarative metric governance.

- **[Metabase Cloud](https://metabase.com)**  
  Official managed hosting service for Metabase providing zero-maintenance deployments, SOC 2 compliance, embedded analytics, and interactive SQL/no-code querying.


## Open-Source GitHub Projects

- **[preset-io/agor](https://github.com)**  
  Open-source BI and analytics project from Preset (the creators of Apache Superset) designed for modern, agile, and AI-assisted data exploration and dashboard workflows.

- **[Apache Superset (`apache/superset`)](https://github.com)**  
  Flagship enterprise-ready open-source data exploration and visualization platform featuring a rich SQL IDE, 40+ chart types, semantic layers, and fine-grained RBAC.

- **[Metabase (`metabase/metabase`)](https://github.com)**  
  User-friendly open-source BI server enabling technical and non-technical teams to ask questions visually or via SQL, build interactive dashboards, and schedule Slack/email pulses.

- **[Lightdash (`lightdash/lightdash`)](https://github.com)**  
  Open-source Looker alternative built natively for `dbt`, turning `dbt` models and YAML metric definitions directly into a governed self-service BI and dashboard layer.

- **[Evidence (`evidence-dev/evidence`)](https://github.com)**  
  Open-source BI-as-Code framework that builds fast, interactive, version-controlled data web applications and reports using SQL queries embedded directly in Markdown.

- **[Rill Data (`rilldata/rill`)](https://github.com)**  
  Fast, opinionated open-source operational BI tool pairing an embedded DuckDB/ClickHouse engine with sub-second interactive exploratory dashboards defined as code.

- **[Redash (`getredash/redash`)](https://github.com)**  
  Classic open-source SQL-first query editor and dashboarding tool supporting dozens of SQL/NoSQL data sources, parameterized queries, and scheduled refreshes.

- **[Grafana (`grafana/grafana`)](https://github.com)**  
  Leading open-source observability and real-time operational dashboard platform connecting to SQL databases, Prometheus, ClickHouse, InfluxDB, and business data sources.

- **[Observable Framework (`observablehq/framework`)](https://github.com)**  
  Open-source static-site generator for data apps and dashboards combining polyglot data loaders (Python, R, SQL, JS) with reactive JavaScript visualizations.

- **[Datasette (`simonw/datasette`)](https://github.com)**  
  Open-source multi-tool for exploring, querying, visualizing, and publishing SQLite and DuckDB datasets as instant interactive web dashboards and JSON APIs.

- **[Cube (`cube-js/cube`)](https://github.com)**  
  Open-source universal semantic layer and headless BI engine providing consistent metric definitions, caching, and GraphQL/REST/SQL APIs for any frontend dashboard.

### Additional Strong Open-Source Options

- **[Streamlit (`streamlit/streamlit`)](https://github.com)** and **[Dash (`plotly/dash`)](https://github.com)** for rapidly building custom interactive Python analytics apps and executive dashboards.
- **[Apache ECharts (`apache/echarts`)](https://github.com)** and **[Tremor (`tremorlabs/tremor`)](https://github.com)** for open-source React/JavaScript visualization libraries tailored for modern BI interfaces.
- **[dbt Core (`dbt-labs/dbt-core`)](https://github.com)** for version-controlled SQL data transformation and testing upstream of BI dashboards.
- **[Vizro (`mckinsey/vizro`)](https://github.com)** for a low-code open-source Python toolkit built on Plotly and Dash for creating modular, design-validated BI dashboards.
- **[RawGraphs (`rawgraphs/rawgraphs-app`)](https://github.com)** for open-source browser-based custom vector chart generation from tabular CSV/TSV datasets.

**Frameworks for building custom systems**: Combine **dbt Core + Cube** for a governed semantic data layer, **Apache Superset** or **Metabase** for self-service team BI, and **Evidence** or **Rill Data** for Git-versioned BI-as-Code dashboards.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Self-hosted BI platforms and embedded analytics dashboards must enforce strict row-level security (RLS), role-based access control (RBAC), and read-only database credentials.
- Always validate metric definitions, SQL join fan-outs, and timezone aggregations before relying on dashboards for executive or financial reporting.

---

**Made for data analysts, analytics engineers, BI architects, product teams, and open-source contributors.**  
Let's make business intelligence and data visualization more open, governed, and accessible.
