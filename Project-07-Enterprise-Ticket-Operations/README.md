# Enterprise IT Service Management & NOC Operations Dashboard

**Looker Studio · KPI Reporting · SLA Analysis · Operations Analytics · NOC Reporting**

## Live Dashboard

**[Open the Interactive Looker Studio Dashboard →](https://datastudio.google.com/reporting/5396b9c3-0ae7-40f8-bbde-88f277bfa075)**

> **Portfolio note:** This dashboard uses synthetic/demo ticket data and is not production data.

## Business Problem

Enterprise service and NOC teams manage high volumes of tickets across customers, branches, services, assignment groups, priorities, and root causes. Without a centralized reporting view, managers can struggle to quickly understand workload, SLA exposure, ticket aging, and areas requiring attention.

This project demonstrates a management-ready ticket operations analytics solution designed around practical service-management questions.

## Management Questions

The dashboard is organized around four questions:

1. **What's happening?** — Executive Overview
2. **Where is the workload?** — Ticket Operations
3. **Are we meeting our commitments?** — SLA & Aging
4. **Who needs attention?** — Customer / Branch

## Dashboard Pages

### 01. Executive Overview

Provides a management-level view of ticket volume and service performance, including:

- Total Tickets
- Open Backlog
- SLA Compliance
- SLA Breaches
- At-Risk Tickets
- Average Resolution Time
- P1 Critical Tickets
- Average CSAT
- Ticket volume trend
- Ticket mix by priority, status, and category
- Executive insights
- Critical attention items

### 02. Ticket Operations

Analyzes where ticket workload is concentrated across:

- Assignment Groups
- Assigned Agents
- Channels
- Services
- Ticket creation trends
- Open backlog by assignment group
- Open backlog by priority
- Open backlog by customer
- Top performers and attention-required areas
- Ticket-level detail

### 03. SLA & Aging

Focuses on service commitments and unresolved workload:

- SLA compliance
- SLA breaches
- At-risk tickets
- P1 breach exposure
- Resolution performance
- Open ticket aging
- Aging buckets
- SLA performance by priority
- SLA trend analysis

### 04. Customer / Branch

Provides customer and branch-level performance analysis, including:

- Ticket volume
- SLA compliance
- Average resolution time
- Customer performance
- Branch performance
- Root-cause analysis
- Areas requiring management attention

## KPI Framework

| KPI | Definition |
|---|---|
| **Total Tickets** | Count of Ticket ID across the selected filters |
| **Open Backlog** | Tickets currently in open statuses |
| **SLA Compliance** | Met SLA ÷ (Met + Breached), excluding at-risk tickets from the denominator |
| **SLA Breaches** | Tickets flagged as SLA breached |
| **SLA At Risk** | Tickets flagged as at risk of breaching SLA |
| **Avg Resolution Time** | Average Resolution Hours for resolved/closed tickets |
| **P1 Critical** | Tickets with Priority = P1 - Critical |
| **Avg CSAT** | Average CSAT for rated tickets |
| **Open Ticket Age** | Age of currently open tickets in days |
| **Total Branches** | Distinct customer and branch combinations |

## Data Structure

The dashboard is built from a synthetic enterprise ticket dataset containing fields such as:

- Ticket ID
- Created Date
- Customer
- Branch
- Region
- Service
- Category
- Priority
- Assignment Group
- Assigned To
- Status
- SLA Target Hours
- SLA Status
- Root Cause
- CSAT
- Is Open
- SLA Breach Flag
- SLA At Risk Flag
- Resolution Hours

## Analytics Demonstrated

- KPI dashboard design
- Interactive filtering
- Ticket volume analysis
- Workload distribution
- SLA compliance analysis
- SLA breach and at-risk monitoring
- Aging analysis
- Customer and branch performance
- Root-cause analysis
- Trend analysis
- Executive exception reporting
- Management-oriented data storytelling

## Tools

- **Looker Studio** — interactive dashboard and visualization
- **CSV / structured ticket data** — synthetic analytical dataset
- **Calculated Fields** — KPI and analytical calculations
- **Data Visualization** — scorecards, tables, bar charts, trend charts, and operational views

## Portfolio Value

This project demonstrates the ability to translate operational requirements into an interactive BI dashboard and present data around business questions rather than simply displaying charts.

The project complements the Power BI dashboards in this portfolio and demonstrates multi-platform Business Intelligence capability.

## Confidentiality

This portfolio project uses synthetic/demo data. No production customer, ticket, employee, credential, or confidential operational information is included.
