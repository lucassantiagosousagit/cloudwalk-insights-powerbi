# CloudWalk – TPV Insights Dashboard (Power BI)

This project is a technical solution for the Operations Intelligence Analyst role at **CloudWalk**. It includes a Power BI dashboard that analyzes transaction data and simulates an AI-powered assistant capable of generating daily strategic insights.

## 📊 Key Features

- **Total Payment Volume (TPV)** analysis by:
  - Entity (PF or PJ)
  - Product
  - Payment Method
  - Price Tier
  - Installment Option
- **Average Ticket** calculation and segmentation
- **Growth Comparisons**:
  - Month-over-month (MoM) TPV variation
  - Alerts on drops above thresholds
- **Automated Insight Simulation**:
  - Text cards displaying dynamic alert messages
  - Product-specific performance detection
  - Bot-style narrative: "⚠️ ALERT: TPV dropped by 23% compared to February"

## 🤖 AI Assistant Logic

The dashboard uses DAX to simulate an assistant that:

- Tracks monthly TPV evolution
- Compares current performance vs previous month
- Detects segments with underperformance
- Generates clear alert messages in natural language

> Example generated insight:
>
> ```
> 📊 Monthly TPV Report – March 2025
> - TPV: $3.27M
> - Growth vs Feb: -21.3% ⚠️
> - Tap product underperformed: 36% below monthly average
> - Average ticket for credit card dropped 18%
> ```
