# Operations Performance Analytics Dashboard

![Operations Performance Dashboard](./Project-03-Telecom-NOC.jpg)

**Power BI · Power Query · DAX · Excel · PostgreSQL**

## Business Problem

Operational teams often work with high-volume incident and outage records across multiple projects. Without a centralized reporting view, it becomes difficult for management to quickly understand incident volume, restoration performance, SLA exposure, recurring issues, and the operational drivers behind KPI movement.

This project demonstrates how operational ticket data can be transformed into a management-ready analytics solution for monitoring network and field-service performance.

## Business Objectives

The dashboard is designed to help stakeholders:

- Monitor incident volume and operational workload
- Track **Mean Time to Repair (MTTR)**
- Monitor **uptime and availability**
- Evaluate **SLA performance and breaches**
- Analyze incidents by **Root Cause Analysis (RCA)**
- Identify recurring alarms and operational problem areas
- Compare performance across projects, portfolios, and operational dimensions
- Support data-driven escalation and improvement decisions

## Data & Architecture

The project uses operational ticket data containing information such as:

- Incident/ticket identifiers
- Site identifiers
- Project or portfolio
- Alarm/incident information
- Escalation and dispatch timestamps
- Restoration/resolution timestamps
- RCA classification
- Severity
- SLA information

The analytical workflow follows:

**Source Data → Power Query → Data Model → DAX Measures → Power BI Dashboard**

A PostgreSQL/Supabase staging layer was used for structured operational data storage and reporting connectivity.

## KPI Framework

### MTTR

Measures the average time required to restore or resolve operational incidents, supporting performance monitoring and service improvement.

### Uptime / Availability

Measures service availability by relating elapsed outage time to the total available operating time for the monitored population.

### SLA Performance

Tracks whether incidents were resolved within the applicable service-level target and highlights potential SLA exposure.

### RCA Analysis

Groups incidents by root cause to identify the operational drivers contributing to downtime and recurring issues.

## Dashboard Analysis

### Executive Operations View

Provides a high-level view of operational workload and KPI performance so stakeholders can quickly identify areas requiring attention.

### MTTR & Performance

Analyzes restoration performance over time and across operational dimensions to identify performance gaps and trends.

### Uptime & Availability

Provides visibility into outage duration and availability performance.

### RCA & Incident Analysis

Breaks down incidents by root cause, alarm type, project, and other relevant dimensions to identify recurring operational problems.

### SLA Monitoring

Highlights incidents that approach or exceed applicable service-level targets.

## Key Business Questions

The dashboard is designed to answer questions such as:

1. Which projects or portfolios have the highest incident workload?
2. Where is MTTR above the expected performance level?
3. Which RCA categories contribute most to downtime or incidents?
4. Are recurring alarms concentrated in particular sites or projects?
5. Which incidents create the greatest SLA exposure?
6. How is operational performance changing over time?

## Business Value

The solution converts detailed operational ticket data into a centralized KPI reporting layer that can support management reviews, operational escalation, performance monitoring, and continuous improvement.

The emphasis is not only on displaying operational data, but on connecting **KPIs → operational drivers → business decisions**.

## Tools & Skills Demonstrated

- **Power BI** — dashboard design and interactive reporting
- **Power Query** — data transformation and preparation
- **DAX** — KPI calculations and analytical measures
- **PostgreSQL / Supabase** — structured data staging
- **Excel** — operational data preparation and reporting
- **Data Modeling** — analytical relationships and reporting structure
- **Operations Analytics** — MTTR, uptime, SLA, RCA, and incident analysis

## Portfolio Note

This project is presented as a portfolio case study using operational analytics concepts and data structures derived from telecommunications and field-service reporting experience. Client and project-specific information is generalized for confidentiality.
