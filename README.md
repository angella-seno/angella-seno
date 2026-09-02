# Angella Seno

Senior Power BI Developer. Semantic modeling, DAX, and Power Query, with the
data platform work that sits underneath them.

Nine years building reporting for teams in the Philippines, Australia, and the
United States, across engineering, IT, finance, HR, and commercial real estate.
Around 30 production dashboards, most of them still in daily use.

Microsoft Power BI Data Analyst and Azure Data Fundamentals certified.

---

## Selected dashboards

Everything below was built end to end: requirements, data model, DAX, layout,
publishing, and refresh. All of it lives inside company tenants, so it is
described here rather than linked. Masked screenshots are available on request.

### Leasing and portfolio
United States, commercial real estate, Power BI on Databricks

| Dashboard | What it answers |
|---|---|
| Leasing Leaderboard | Which agents are performing, ranked, published to the company intranet |
| Leasing Activity Overview | Executed and signed deal metrics by agent and property |
| In Negotiation, Estimated Execution | Which deals are close, and which have no execution date |
| DM Stage History | How deals move through Deal Manager stages, and where they stall |
| Current Lease Expirations | What rolls off in the next 12 months, by SF and by count |
| Availability Overview | Vacant area by property, unit type, and leasing manager |
| Top Tenants Overview | Portfolio exposure by tenant corporate credit |
| Lease Provisions | Clause-level lease terms: co-tenancy, termination, ROFO, and options |
| Exclusive and Restricted Uses | Which uses are barred at a property before a new deal is signed (paginated report) |

### Capital and construction cost
United States, Power BI on Databricks

| Dashboard | What it answers |
|---|---|
| Job Cost Summary - Tenant | Budget versus billed across job types, with variance and % utilized |
| Job Cost Summary - CapEx | All CapEx jobs by fund, property, and status |
| Construction Manager Details | Cost category, transaction, and line-item drill-down |

### Finance and project performance
Australia, global engineering firm, Power BI on Azure SQL / Synapse

| Dashboard | What it answers |
|---|---|
| Azure EA Usage and Cost Management | Where cloud spend is going, by subscription and tag |
| Working Capital, WIP Ageing | Cash position and unbilled work by project |
| Project Cost Report, Profit and Loss | Which projects are profitable, and which are not |
| Pipeline, New Work Secured | What is coming, supporting bid and resourcing decisions |
| Purchase Orders and Invoices | Procurement and software renewal exposure |

### IT operations and resource planning
Australia, Power BI Premium, ServiceNow and Workday

| Dashboard | What it answers |
|---|---|
| Service Desk Tickets, Ageing and Backlog SLA | Whether the desk is meeting SLA, and where it is slipping |
| Resource Planning suite | Utilization, forecasting, and workforce distribution globally |
| Major Incident Report, IT Risk Register | What broke, and what is likely to |
| Quality Audits and Client Satisfaction | CSAT and audit outcomes by resolver group |
| Network Incidents, Bandwidth Utilization | Infrastructure health and capacity |

### Security and compliance
Australia, Power BI with ServiceNow, Mimecast, KnowBe4

| Dashboard | What it answers |
|---|---|
| Phishing Emails and Account Lockout | Attack volume and response time |
| Security Incident Monitoring (ISIRT) | Open incidents and resolution status |
| Cyber Awareness Training | Which teams have not completed mandatory training |

---

## How I build

**Semantic models.** Star schema over pre-joined gold tables, with row-level
security, KPI-driven measure design, and deployment pipelines across Dev, Test,
and Prod. Enough performance tuning that a business question does not become a
source-system query.

**Data platform.** Source-to-warehouse mapping, field-level catalogs, and
migration scoping. Most recently a 90+ table catalog that retired a legacy
third-party reporting platform, delivered with the data engineering team.

**Validation.** Automated reconciliation between source systems and published
dashboards. Six recurring reports went from three hours each to under thirty
minutes.

**Enablement.** Two internal Power BI training programs, plus documentation and
self-service reporting that cut ad hoc requests by 40%.

---

## Repos

Public work, rebuilt on synthetic or open data. The dashboards above cannot be
published, so these show the engineering patterns behind them instead.

| Repo | What it is |
|---|---|
| [bi-reconciliation-engine](https://github.com/YOUR-HANDLE/bi-reconciliation-engine) | Config-driven reconciliation between a source export and a BI export, with per-measure tolerances and an HTML verdict report |

More coming: a documented semantic model as code, a DAX pattern library, and a
reusable Power Query M function set.

---

## Stack

`Power BI` `DAX` `Power Query (M)` `SQL` `Star schema` `RLS` `Deployment pipelines`
`Databricks` `Azure SQL / Synapse` `Python` `Power Automate`

Sources I have modeled against: Yardi Voyager and Deal Manager, ServiceNow,
Workday, BST, Saviom, SharePoint, Azure EA.

---

## Contact

- [LinkedIn](https://www.linkedin.com/in/angella-seno-a16165191/)
- angellaseno@gmail.com
- Portfolio deck available on request

