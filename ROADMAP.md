# 🚀 Data Analytics & Microsoft Fabric Career Roadmap

**Target role:** Data Analyst / Power BI / Microsoft Fabric Analytics Engineer  
**Target compensation:** ₱120K+ monthly  
**Primary certification path:** PL-300 → DP-600  
**Optional advanced certification:** DP-700  
**Target study duration:** 24 weeks  
**Recommended pace:** 1.5–2 hours/day, 5 days/week

---

## 🎯 North Star

Build the ability to take a business question from **requirements → data → SQL/Power Query → Fabric → data model → DAX → semantic model → Power BI → validation → actionable insight**.

This roadmap is designed around the skills requested in the target job description:

- Power BI
- Microsoft Fabric
- OneLake
- Lakehouse
- Warehouse
- Direct Lake
- SQL
- DAX
- Power Query
- KQL
- Excel
- Data modeling
- Dashboarding
- Customer/business insights
- Reporting requirements
- Data validation
- Actionable insights

---

# 🧭 The Rule When You Lose Track

**Never restart the whole course.**

1. Open `LEARNING-TRACKER.md`.
2. Find the last unchecked item.
3. Continue from there.
4. If you stopped for more than 2 weeks, spend one session reviewing the previous completed phase, then continue.
5. Do not move to the next phase just because you watched the lessons. Move when the **hands-on gate** is complete.

> **Learning rule:** 20% theory + 80% hands-on.

---

# 🗺️ 24-Week Roadmap

| Phase | Weeks | Focus | Hands-on Output | Gate |
|---|---:|---|---|---|
| 1 | 1–2 | Analytics fundamentals | Telecom Operations Analytics | ⬜ |
| 2 | 3–4 | Advanced Excel + Power Query | O&M KPI workbook | ⬜ |
| 3 | 5–7 | SQL | 50+ business queries | ⬜ |
| 4 | 8 | Power Query | Reusable transformation workflow | ⬜ |
| 5 | 9–12 | Power BI + Data Modeling + DAX | Professional BI dashboard | ⬜ |
| 6 | 13 | Power BI Service | Published/reporting workflow | ⬜ |
| 7 | 14–17 | Microsoft Fabric | Lakehouse + Warehouse + Direct Lake | ⬜ |
| 8 | 18 | KQL / Real-Time Analytics | NOC event analysis | ⬜ |
| 9 | 19 | Dataflows Gen2 + Pipelines | Automated ingestion | ⬜ |
| 10 | 20 | Architecture + Modeling | Medallion architecture | ⬜ |
| 11 | 21 | Business Requirements | Reporting requirements document | ⬜ |
| 12 | 22 | Data Validation | Source-to-report validation | ⬜ |
| 13 | 23 | Insight Generation | Executive recommendations | ⬜ |
| 14 | 24 | Capstone | End-to-end Fabric Analytics Platform | ⬜ |

---

# 📚 Phase 1 — Data Analytics Fundamentals

## Weeks 1–2

### Learn

- Descriptive, diagnostic, predictive and prescriptive analytics
- KPIs vs metrics
- Dimensions vs measures
- Business questions
- Reporting requirements
- Data quality
- Data validation
- Data lineage
- Stakeholder requirements
- Turning analysis into recommendations

### Hands-on

Build **Telecom Operations Analytics** using fields such as:

`Site ID | Region | Province | Alarm | RCA | Dispatched | Arrival | Resolution | Technician | Vendor | Downtime | MTTR | SLA`

Answer at least 10 business questions:

- Which regions have the highest downtime?
- Which RCA contributes most to downtime?
- Which sites repeatedly fail?
- Which technicians have the highest MTTR?
- Which alarms breach SLA?
- What changed month-over-month?

### Gate

- [ ] 10 business questions answered
- [ ] Findings documented
- [ ] At least 5 recommendations written

---

# 📊 Phase 2 — Advanced Excel + Power Query

## Weeks 3–4

### Excel

Master:

- XLOOKUP
- INDEX/MATCH
- SUMIFS
- COUNTIFS
- AVERAGEIFS
- IF / IFS / IFERROR
- TEXT / LEFT / RIGHT / MID
- DATE / YEAR / MONTH / DAY / WEEKNUM
- Pivot Tables
- Pivot Charts
- Dynamic arrays
- Tables

### Power Query

Master:

- Data types
- Filtering
- Replacing values
- Splitting columns
- Merging queries
- Appending queries
- Group By
- Pivot / Unpivot
- Custom columns
- Parameters
- Reusable transformations
- Query folding concepts

### Hands-on

Build **O&M Monthly Performance Report**.

KPIs:

- Site count
- Alarm count
- Downtime
- MTTR
- Uptime
- SLA %
- Top RCA
- Repeated alarms
- Technician performance

### Gate

- [ ] Workbook completed
- [ ] Power Query transformation documented
- [ ] Refresh tested successfully

---

# 🗄️ Phase 3 — SQL

## Weeks 5–7

### Level 1

- SELECT
- FROM
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- DISTINCT
- TOP

### Level 2

- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN
- Primary/foreign keys

### Level 3

- CASE
- COALESCE
- NULLIF
- CAST / CONVERT
- Date functions
- String functions

### Level 4

- CTEs
- Subqueries
- Window functions
- ROW_NUMBER
- RANK
- DENSE_RANK
- LAG
- LEAD
- SUM OVER
- AVG OVER

### Hands-on

Use:

`Sites | Alarms | Tickets | Technicians | Regions | RCA`

Create at least **50 SQL queries**.

Suggested repository structure:

```text
SQL/
├── 01_Basic_Queries.sql
├── 02_Aggregations.sql
├── 03_Joins.sql
├── 04_CTE.sql
├── 05_Window_Functions.sql
├── 06_Date_Analysis.sql
└── 07_Business_Questions.sql
```

### Gate

- [ ] 50 queries completed
- [ ] 10 JOIN exercises
- [ ] 10 aggregation exercises
- [ ] 10 CTE/subquery exercises
- [ ] 10 window-function exercises
- [ ] 10 business questions solved

---

# 🔄 Phase 4 — Power Query Deep Dive

## Week 8

Build a reusable data preparation workflow.

### Gate

- [ ] Multiple source files combined
- [ ] Data types validated
- [ ] Nulls handled
- [ ] Duplicates handled
- [ ] Transformation steps documented
- [ ] Refresh tested

---

# 📈 Phase 5 — Power BI + Data Modeling + DAX

## Weeks 9–12

### Week 9 — Power BI

- Power BI Desktop
- Power BI Service
- Reports
- Semantic models
- Workspaces
- Data refresh
- Filters
- Slicers
- Drill-through
- Tooltips
- Bookmarks

### Week 10 — Data Modeling

Master:

- Fact tables
- Dimension tables
- Star schema
- Primary/foreign keys
- Cardinality
- One-to-many
- Many-to-many
- Filter direction
- Active/inactive relationships
- Date tables

### Week 11 — DAX

Master:

- SUM
- COUNTROWS
- DISTINCTCOUNT
- CALCULATE
- FILTER
- ALL
- REMOVEFILTERS
- VALUES
- SELECTEDVALUE
- SWITCH
- IF
- DIVIDE
- SUMX
- AVERAGEX
- MINX / MAXX

### Time intelligence

- TOTALYTD
- TOTALMTD
- TOTALQTD
- DATEADD
- SAMEPERIODLASTYEAR
- YTD
- MTD
- YoY %
- MoM %
- Rolling 12 months

### Week 12 — Visualization

Build an executive-quality dashboard with:

- KPI cards
- Trend charts
- Matrix
- Drill-through
- Tooltips
- Conditional formatting
- Decomposition tree
- Waterfall
- Executive summary

### Gate

- [ ] Star schema implemented
- [ ] 25+ DAX measures
- [ ] Time intelligence completed
- [ ] Dashboard published
- [ ] Business insights documented

---

# ☁️ Phase 6 — Power BI Service

## Week 13

Learn:

- Workspaces
- Semantic models
- Reports
- Dashboards
- Apps
- Scheduled refresh
- Gateway concepts
- Permissions
- Row-Level Security
- Data lineage
- Impact analysis

### Gate

- [ ] Report published
- [ ] Refresh configured/tested
- [ ] Workspace structure documented
- [ ] RLS concept demonstrated

---

# 🏗️ Phase 7 — Microsoft Fabric

## Weeks 14–17

### Week 14 — Fabric Fundamentals

Learn:

- Microsoft Fabric architecture
- OneLake
- Workspaces
- Lakehouse
- Warehouse
- Data Factory
- Power BI integration
- Real-Time Intelligence

### Week 15 — Lakehouse

Learn:

- Files
- Tables
- Delta tables
- Parquet
- SQL endpoint
- Spark basics
- Data ingestion
- Data transformation
- Medallion architecture

### Week 16 — Warehouse

Learn:

- Fabric Warehouse
- T-SQL
- Tables
- Views
- Dimensional modeling
- Fact/dimension design
- Security
- Monitoring

### Week 17 — Direct Lake + Semantic Models

Understand:

- Import
- DirectQuery
- Direct Lake
- Semantic models
- Storage modes
- Performance considerations
- When to use each approach

### Hands-on

Build:

```text
CSV / Excel
    ↓
Fabric Pipeline
    ↓
OneLake
    ↓
Lakehouse
    ↓
Bronze → Silver → Gold
    ↓
Semantic Model
    ↓
Power BI
```

### Gate

- [ ] OneLake concepts understood
- [ ] Lakehouse created
- [ ] Warehouse created
- [ ] Data loaded
- [ ] Gold layer created
- [ ] Semantic model connected
- [ ] Direct Lake studied/tested

---

# ⚡ Phase 8 — KQL / Real-Time Analytics

## Week 18

Learn:

- KQL basics
- where
- project
- extend
- summarize
- count
- sum
- avg
- top
- sort
- join
- union
- parse
- bin

### Hands-on

Build **Real-Time NOC Monitoring** with:

`Timestamp | Site | Alarm | Severity | Region | Temperature | Power | Battery | Signal | Status`

Analyze:

- Alarms per hour
- Alarms per region
- Top failing sites
- Power abnormalities
- Battery abnormalities
- Alarm trends

### Gate

- [ ] 20+ KQL queries
- [ ] Eventhouse/KQL concepts studied
- [ ] NOC real-time analysis documented

---

# 🔁 Phase 9 — Dataflows Gen2 + Pipelines

## Week 19

Learn:

### Dataflows Gen2

- Ingestion
- Transformation
- Power Query Online
- Destinations

### Pipelines

- Copy Data
- Activities
- Scheduling
- Parameters
- Monitoring
- Error handling

### Hands-on

Automate:

```text
Source files
   ↓
Dataflow / Pipeline
   ↓
Lakehouse
   ↓
Gold tables
   ↓
Power BI
```

### Gate

- [ ] Dataflow created
- [ ] Pipeline created
- [ ] Pipeline executed successfully
- [ ] Monitoring checked

---

# 🧱 Phase 10 — Analytics Architecture

## Week 20

Master:

- ETL vs ELT
- Data lake
- Data warehouse
- Lakehouse
- Data mart
- OneLake
- Medallion architecture
- Star schema
- Semantic model
- Data lineage
- Data governance

### Gate

Draw and explain your complete architecture without notes.

---

# 🧑‍💼 Phase 11 — Business Requirements

## Week 21

For every reporting request, document:

- Business owner
- Purpose
- Audience
- Business questions
- Data sources
- KPI definitions
- Filters
- Refresh frequency
- Security requirements
- Acceptance criteria

### Hands-on

Create a **Reporting Requirements Document** for your Telecom Operations Analytics project.

### Gate

- [ ] Requirements document completed
- [ ] KPI definitions documented
- [ ] Acceptance criteria documented

---

# 🔍 Phase 12 — Data Validation

## Week 22

Master:

- Duplicate detection
- Null checks
- Outlier detection
- Referential integrity
- Data type validation
- Row-count reconciliation
- Source-to-SQL reconciliation
- SQL-to-Power BI reconciliation
- KPI validation

### Example

```text
Source tickets = 10,245
SQL tickets    = 10,245
Power BI       = 10,245

Source downtime = 82,451 min
SQL downtime    = 82,451 min
Power BI         = 82,451 min
```

### Gate

- [ ] Validation checklist created
- [ ] Source vs SQL reconciled
- [ ] SQL vs Power BI reconciled
- [ ] Exceptions documented

---

# 💡 Phase 13 — Actionable Insights

## Week 23

Move from:

> "Downtime increased 12%."

To:

> "Downtime increased 12% month-over-month, primarily driven by grid-related incidents in Region X. The five highest-impact sites account for 38% of total downtime. Prioritizing preventive maintenance for these sites should address the largest concentration of downtime."

### Practice

For every dashboard page, write:

1. What happened?
2. Why did it happen?
3. Where is the biggest impact?
4. What should management do?

### Gate

- [ ] 10 insights written
- [ ] 10 recommendations written
- [ ] Executive summary completed

---

# 🏆 Phase 14 — Final Capstone

## Week 24

# Telecom Operations Analytics Platform

Build the complete solution:

```text
                CSV / Excel / SQL
                       ↓
                Fabric Pipeline
                       ↓
                     OneLake
                       ↓
                   Lakehouse
                       ↓
               Bronze → Silver → Gold
                       ↓
                 Semantic Model
                       ↓
                      DAX
                       ↓
                    Power BI
                       ↓
             Executive Dashboard
                       ↓
              Business Recommendations
```

### Required dashboard pages

1. Executive Overview
2. Operations Performance
3. MTTR Analysis
4. Uptime / SLA
5. Repeated Alarms
6. Management Recommendations

### Required technical evidence

- [ ] SQL scripts
- [ ] Power Query transformations
- [ ] Star schema
- [ ] DAX measures
- [ ] Fabric Lakehouse
- [ ] Fabric Warehouse
- [ ] Pipeline
- [ ] Dataflow Gen2
- [ ] KQL exercises
- [ ] Semantic model
- [ ] Power BI report
- [ ] Data validation document
- [ ] Business requirements document
- [ ] Executive recommendations

---

# 🎓 Certification Roadmap

## 1. PL-300 — Microsoft Certified: Power BI Data Analyst Associate

**Priority: MUST HAVE**

Study after completing the Power BI, modeling, Power Query and DAX phases.

Official certification:  
https://learn.microsoft.com/en-us/credentials/certifications/data-analyst-associate/

Official study guide:  
https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/pl-300

### PL-300 readiness checklist

- [ ] Prepare the data
- [ ] Model the data
- [ ] Visualize and analyze the data
- [ ] Manage and secure Power BI
- [ ] Complete Microsoft Learn preparation
- [ ] Complete practice exams
- [ ] Build one complete portfolio project
- [ ] Schedule exam
- [ ] Pass PL-300

---

## 2. DP-600 — Microsoft Certified: Fabric Analytics Engineer Associate

**Priority: HIGHLY RECOMMENDED**

Study after gaining hands-on Fabric experience.

Official certification:  
https://learn.microsoft.com/en-us/credentials/certifications/fabric-analytics-engineer-associate/

Focus on:

- Analytics solutions
- Semantic models
- Lakehouses
- Warehouses
- Data preparation
- Data enrichment
- Security
- Managing analytics assets
- Stakeholder requirements

### DP-600 readiness checklist

- [ ] Fabric fundamentals
- [ ] OneLake
- [ ] Lakehouse
- [ ] Warehouse
- [ ] Data modeling
- [ ] Semantic models
- [ ] Power BI integration
- [ ] Data preparation
- [ ] Security
- [ ] Portfolio capstone
- [ ] Practice assessment
- [ ] Schedule exam
- [ ] Pass DP-600

---

## 3. DP-700 — Microsoft Certified: Fabric Data Engineer Associate

**Priority: OPTIONAL ADVANCED**

Take this after PL-300 + DP-600 if you want to move deeper into Fabric/data engineering.

Official certification:  
https://learn.microsoft.com/en-us/credentials/certifications/fabric-data-engineer-associate/

Focus:

- Data ingestion
- Data transformation
- Pipelines
- Spark
- Data architecture
- Monitoring
- Optimization

---

# 🧪 Microsoft Learn Priority List

Use Microsoft Learn as the primary source for Microsoft technologies.

1. Power BI / PL-300 study guide
2. Get started with Microsoft Fabric
3. Explore analytics data stores in Fabric
4. Implement a Lakehouse with Fabric
5. Implement a Data Warehouse with Fabric
6. Ingest Data with Fabric
7. Design and transform analytics data in Fabric
8. DAX learning path
9. PL-300 practice assessment
10. DP-600 preparation

---

# 💼 Portfolio Projects Required Before Job Applications

## Project 01 — Executive Business Analytics

Power BI + DAX + Excel

## Project 02 — Customer Analytics

Power BI + Data Modeling + DAX

## Project 03 — Telecom NOC Analytics

Power BI + SQL + DAX + KPI analytics

## Project 04 — Inventory Analytics

Power BI + Power Query

## Project 05 — HR Analytics

Power BI + DAX

## Project 06 — Bulk Distance Calculator

Python + Excel + API integration

## Project 07 — SQL Analytics

SQL + business questions + window functions

## Project 08 — Fabric Lakehouse

OneLake + Lakehouse + Medallion architecture

## Project 09 — Fabric Warehouse

Warehouse + T-SQL + dimensional model

## Project 10 — End-to-End Fabric Analytics

Pipeline + Lakehouse + Warehouse + Semantic Model + Power BI + validation + recommendations

---

# 🧠 Interview Readiness

Before applying for the ₱120K+ target, be able to explain these without memorized answers:

### Power BI

- What is a star schema?
- Why use a date table?
- Difference between calculated column and measure?
- What does CALCULATE do?
- Import vs DirectQuery vs Direct Lake?
- How do you improve Power BI performance?
- How do you validate a KPI?

### SQL

- INNER JOIN vs LEFT JOIN
- GROUP BY vs HAVING
- CTE vs subquery
- RANK vs ROW_NUMBER
- How to find duplicates
- How to calculate running totals
- How to find top N per group

### Fabric

- What is OneLake?
- Lakehouse vs Warehouse?
- What is Delta Lake?
- What is Medallion architecture?
- What is Direct Lake?
- Dataflow Gen2 vs Pipeline?
- When would you use KQL?

### Business Analytics

- How do you gather reporting requirements?
- How do you define a KPI?
- How do you validate a dashboard?
- How do you handle conflicting metric definitions?
- How do you turn analysis into an actionable recommendation?

---

# 🏁 Definition of Done

You are ready to aggressively target these roles when you can truthfully say:

> **I can gather reporting requirements, prepare data with Power Query/SQL/Fabric, design dimensional models, write DAX, build semantic models and Power BI dashboards, work with Fabric Lakehouses/Warehouses/OneLake, use KQL for real-time analysis, validate metrics, and communicate actionable business insights to stakeholders.**

The certification proves knowledge.  
The portfolio proves hands-on ability.  
The interview proves you can explain and apply it.

---

# 🔄 Monthly Reset

At the end of every month, update:

- Current phase
- Completed modules
- Projects completed
- GitHub evidence
- Microsoft Learn progress
- Certification progress
- Weakest skill
- Next milestone

**Do not measure progress by hours watched. Measure progress by things you can build without following a tutorial.**

---

## ⭐ Current Mission

**Next target:** Complete SQL fundamentals + Power BI/DAX strengthening, then begin Microsoft Fabric hands-on work.

**Certification target #1:** PL-300  
**Certification target #2:** DP-600  
**Portfolio target:** End-to-End Telecom Operations Analytics Platform  
**Career target:** Data Analyst / Power BI / Microsoft Fabric role at ₱120K+ monthly
