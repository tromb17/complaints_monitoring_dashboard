# Complaints Monitoring Dashboard

Power BI dashboard for customer complaints monitoring and processing workflow tracking.

## Overview

This dashboard provides real-time monitoring of customer complaints processing in a pharmaceutical distribution company.

It helps managers track claim status, employee workload, and processing deadlines.

All sensitive data (employee names, customer organizations) is anonymized for portfolio demonstration.

## Business Context

Customer complaints processing requires clear visibility into:
- Current status of each complaint (filing, response preparation, shipment, etc.)
- Workload distribution across team members
- Overdue tasks and bottlenecks
- Statistics by customer organization

This dashboard centralizes all claim data in one view and provides weekly/monthly performance tracking.

## Dashboard Structure

The report includes four main pages:

### 1. Current Status Overview
- Complaints by stage (monitoring, filing, response preparation, shipment planned, in transit)
- Weekly dynamics (backlog at start, incoming, completed, current remaining)
- Breakdown by employee with overdue task highlighting

### 2. Monthly View
- Same structure as weekly view but for the current month
- Trend tracking for longer-term performance analysis

### 3. Statistics by Customer Organization
- Total complaints per organization
- Open complaints count
- Overdue complaints
- Complaints requiring urgent response (РНП)

### 4. Detailed Task List
- Full complaint list with filters by status
- Employee assignments
- Creation dates and deadlines
- Overdue task tracking

## Key Metrics

- **Backlog** (Было на начало периода) — complaints pending at period start
- **Incoming** (Пришло) — new complaints received
- **Completed** (Сделано) — complaints resolved
- **Remaining** (Текущий остаток) — open complaints at period end
- **Overdue** (Просрочено) — complaints past deadline

## Tech Stack

- **Power BI Desktop** — dashboard development
- **Data source** — internal corporate database (not included for confidentiality)

## Repository Structure

```text
claims-monitoring-dashboard/
├── README.md
├── .gitignore
├── report/
│   └── Otchet-po-pretenziiam.pdf    # Anonymized dashboard export
└── screenshots/
    └── (optional additional screenshots)
```

## Usage

The dashboard is used by:
- **Team members** — track their own workload and deadlines
- **Team lead** — monitor team performance and redistribute tasks
- **Management** — review claim resolution efficiency

## Note

All employee names and customer organization names are anonymized or blurred in the published materials. The dashboard structure and metrics are representative of the actual working tool.

## Skills Demonstrated

- Power BI dashboard design
- Business process monitoring
- KPI definition and tracking
- Data visualization for operational management
