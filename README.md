# ConnectTel Call Centre – Cost & Performance Analysis

> **Vuuma Presentation** | Analyst: Reabetswe Tsotetsi

## Project Overview

This project is a cost and performance review of the ConnectTel Call Centre. The goal is to identify drivers of high operational costs, spot inefficiencies across teams and shifts, and recommend actionable improvements.

## Objectives

- Identify drivers of high costs
- Spot operational inefficiencies
- Recommend improvements to staffing and team performance

## Files

| File | Description |
|------|-------------|
| `Reabetswe_Tsotetsi_ConnectTel_CallCenterData.xlsx` | Raw call centre data and analysis pivot tables |
| `Reabetswe_Tsotetsi_Vuuma_Presentation.pdf` | Presentation summarising key findings and recommendations |

## Dataset

**Source file:** `ConnectTel_CallCenterData.xlsx`
**Sheets:** `Raw` (98 records) + `Analysis`

### Columns

| Column | Description |
|--------|-------------|
| `Team` | Team identifier (Team A, B, or C) |
| `AgentID` | Unique agent identifier |
| `Day` | Day of the week |
| `Shift` | Shift worked (Morning, Afternoon, Evening) |
| `Experience` | Agent experience band |
| `CallsHandled` | Number of calls handled |
| `AvgCallDuration` | Average call duration (minutes) |
| `EscalationRate` | Proportion of calls escalated |
| `FCRRate` | First Call Resolution rate |
| `CSATScore` | Customer Satisfaction score |
| `OvertimeHours` | Overtime hours logged |
| `CostPerCall` | Cost per call (ZAR) |
| `Total Escalations` | Derived: CallsHandled x EscalationRate |
| `Total FCRRate` | Derived: FCRRate x CallsHandled |

## Key Findings

### 1. Demand by Shift
- The **Morning shift** handles the highest volume of calls
- The **Evening shift** handles the least

### 2. Overtime vs Demand
- The **Afternoon shift** receives the most overtime hours
- The **Morning shift** (highest demand) receives the least overtime — a clear inefficiency

### 3. Team Performance

| Team | Total Calls | Avg Duration (min) | Avg Cost/Call (ZAR) | Escalation Rate | FCR Rate |
|------|-------------|-------------------|----------------------|-----------------|----------|
| Team A | 8,027 | 6.06 | 25.41 | 11.76% | 79.25% |
| Team B | 8,082 | 7.52 | 27.57 | 10.58% | 79.89% |
| Team C | 8,229 | 5.98 | 25.24 | 11.27% | 78.27% |

- **Team B** has the highest average call duration and cost per call
- Team B's duration is ~20% longer than Team C, with ~9% higher cost per call

### 4. Cost Drivers
- Longer call durations inflate costs
- Overtime is not aligned with peak demand periods
- High escalation handling increases overall call duration

## Recommendations

- **Train Team B** on efficient call handling to reduce duration and cost per call
- **Realign overtime** — prioritise Morning and Afternoon shifts where demand is highest
- **Coach high-escalation agents** to improve first-call resolution

## Risks and Assumptions

| Risk | Description |
|------|-------------|
| Call Complexity | Longer durations or higher costs may reflect complex cases, not inefficiency |
| Escalation Interpretation | High escalation rates may indicate difficult issues, not poor performance |
| Timeframe Limitation | Analysis covers a limited period and may not capture seasonal or long-term trends |

## Tools Used

- **Microsoft Excel** – Data storage, pivot analysis, and charting
- **PowerPoint / PDF** – Presentation of findings

## Author

**Reabetswe Tsotetsi**
ConnectTel Call Centre Analysis – Vuuma Presentation
