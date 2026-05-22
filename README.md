# Kenya Money Supply & Private Credit Dashboard

**Analyzing monetary transmission in Kenya: Is M3 growth reaching the real economy?**

*Period: Jan 2025 – Feb 2026 | Source: Central Bank of Kenya Monthly Economic Indicators*

---

## The Story Behind This

I started with a simple expectation:

If Kenya’s money supply was growing, private sector credit would probably grow at almost the same pace.

That is the basic idea behind monetary transmission. When liquidity expands in the financial system, we usually expect some of that money to flow into lending for businesses, households, and productive sectors.

But the data showed something different.

Between **January 2025 and February 2026**, Kenya’s **Money Supply M3 grew by 12.06%**.

Private sector credit grew by **7.17%**.

That gap became the story.

I built this Power BI dashboard using **Central Bank of Kenya Monthly Economic Indicators** to track whether liquidity growth is translating into lending, where private sector credit is actually going, and whether the banking system stays stable when cash movement becomes volatile.

This is a business intelligence project focused on turning official central bank data into a clear, decision-ready dashboard.

---

## Dashboard Preview

### Executive Summary

![Executive Summary](screenshots/executive_summary.jpg)

### Money Supply and Private Credit Overview

![Overview](screenshots/overview.jpg)

### Sector Credit Analysis

![Sector Credit Analysis](screenshots/sector_credit_analysis.jpg)

### Sector Credit Trends

![Sector Credit Trends](screenshots/sector_credit_trends.jpg)

### Monthly Change Analysis

![Monthly Change Analysis](screenshots/monthly_change_analysis.jpg)

---

## Main Business Question

**Is Kenya’s growth in money supply translating into stronger private sector credit?**

The dashboard answers this question by tracking:

- Money Supply M3
- Private Sector Credit
- Demand Deposits
- Currency Outside Banks
- Month-on-month cash movement
- Month-on-month private credit movement
- Sector-level private credit allocation

---

## Who This Helps

### Policy Researchers

Policy researchers can use this dashboard to quickly identify whether liquidity growth is reaching the real economy through private sector lending.

The dashboard highlights a possible **credit transmission gap**: Money Supply M3 grew faster than private sector credit.

This does not prove why the gap exists, but it creates a strong starting point for deeper analysis using interest rates, government borrowing, bank reserves, inflation, and government securities data.

---

### Investors and Fund Managers

Investors can use the sector credit analysis to see where lending is concentrated.

For example, the dashboard shows that **Trade received KSh 732.5B** in private sector credit in February 2026, while **Agriculture received only 4.70%** of total private sector credit.

This helps investors ask better questions:

- Which sectors are attracting credit?
- Which sectors may be underfunded?
- Is credit flowing more toward commerce, households, production, or assets?
- Are some sectors becoming more financially exposed than others?

---

### Bank Treasurers and Risk Analysts

Bank treasurers and risk analysts can use the dashboard to compare cash volatility with lending stability.

Cash outside banks moved sharply from **+4.85% in October 2025** to **-4.67% in January 2026**.

However, private sector credit declined by only **-0.78%** in January 2026.

This suggests that private sector credit was more stable than short-term cash movement during the period.

---

## What You’ll Find Inside

| Page | What It Shows | Key Takeaway |
|---|---|---|
| **Executive Summary** | KPI cards, sector ranking, and written insights | Money supply grew faster than private sector credit |
| **Overview** | 14-month trends for M3, private credit, deposits, and cash | M3 increased steadily, but credit grew more slowly |
| **Sector Credit Analysis** | Private sector credit ranking for Feb 2026 | Trade received the most credit |
| **Sector Credit Trends** | Top 5 sector credit movement over time | Trade remained the dominant credit recipient |
| **Monthly Change Analysis** | Cash MoM change vs private credit MoM change | Cash was more volatile than private sector credit |

---

## Key Questions Answered

### 1. Kenya Money Supply M3 Analysis

- Is Kenya’s broad money supply growing, shrinking, or stagnant?
- Is Money Supply M3 growing faster than private sector credit?
- What does the growth gap suggest about liquidity transmission?

---

### 2. Kenya Private Sector Credit Data

- Is private sector credit growing?
- Which sectors receive the most private sector credit?
- Which sectors receive the least private sector credit?
- Is credit concentrated in a few sectors?

---

### 3. Money Composition

- Is money growth coming from cash outside banks or demand deposits?
- How large is currency outside banks compared to Money Supply M3?
- Are cash movements stable or volatile?

---

### 4. Credit Stability and Volatility

- Which is more volatile: cash outside banks or private sector credit?
- Did the sharp cash decline in January 2026 lead to a major decline in private credit?
- Is lending more stable than short-term cash movement?

---

## The Numbers That Matter

1. **Transmission Gap**  
   Money Supply M3 grew by **12.06%**, while private sector credit grew by **7.17%**.  
   Liquidity expanded faster than lending.

2. **Sector Concentration**  
   Trade received **KSh 732.5B** in private sector credit in February 2026.  
   Agriculture received **4.70%** of total private sector credit.

3. **System Resilience**  
   Cash outside banks declined by **-4.67%** in January 2026.  
   Private sector credit declined by only **-0.78%** in the same month.

4. **Cash Volatility**  
   Cash outside banks showed a Q4 spike in this dataset and corrected in Q1.  
   More historical data would be needed to confirm whether this is a consistent seasonal pattern.

---

## Time Period Covered

The dashboard covers:

```text
January 2025 – February 2026
```

For month-on-month change analysis, the period starts from:

```text
February 2025 – February 2026
```

This is because month-on-month change requires a previous month for comparison.

---

## Data Source

The data was sourced from:

**Central Bank of Kenya — Monthly Economic Indicators**

Source files used:

- Monthly Economic Indicators — January 2026
- Monthly Economic Indicators — February 2026

The project uses selected indicators from CBK money, credit, and interest rate tables.

---

## Metrics Used

| Metric | Meaning |
|---|---|
| Money Supply M3 | Broad measure of money supply in the economy |
| Private Sector Credit | Credit extended to private businesses and households |
| Currency Outside Banks | Physical cash held outside the banking system |
| Demand Deposits | Money held in bank accounts that can be accessed quickly |
| Cash MoM Change % | Month-on-month change in currency outside banks |
| Private Credit MoM Change % | Month-on-month change in private sector credit |
| Sector Credit Value | Private sector credit by economic sector |
| M3 Growth % | Total growth in money supply over the period |
| Private Credit Growth % | Total growth in private sector credit over the period |
| Agriculture Share % | Agriculture’s share of total private sector credit |
| Cash Max MoM Swing | Largest monthly increase in cash outside banks |

---

## Dashboard Pages

### 1. Executive Summary

This page gives a high-level summary of the dashboard findings.

It includes:

- M3 total growth
- Private sector credit growth
- Peak cash volatility
- Agriculture’s share of private sector credit
- Top private sector credit recipients
- Key written insights

Main insight:

> Money Supply M3 grew faster than private sector credit, suggesting that liquidity expanded faster than lending to the private sector.

---

### 2. Overview

This page shows the trend of key money and credit indicators from January 2025 to February 2026.

Metrics shown:

- Money Supply M3
- Private Sector Credit
- Demand Deposits
- Currency Outside Banks

Main insight:

> Money Supply M3 increased steadily over the period. Private sector credit also increased, but at a slower pace than overall money supply.

---

### 3. Sector Credit Analysis

This page ranks private sector credit by economic sector for February 2026.

Sectors analyzed include:

- Trade
- Private Households
- Manufacturing
- Consumer Durables
- Real Estate
- Transport and Communications
- Business Services
- Building and Construction
- Agriculture
- Finance and Insurance
- Other Activities
- Mining and Quarrying

Main insight:

> Trade received the highest amount of private sector credit in February 2026, while Mining and Quarrying received the lowest.

---

### 4. Sector Credit Trends

This page tracks the top five credit-receiving sectors from January 2025 to February 2026.

Top sectors shown:

- Trade
- Private Households
- Manufacturing
- Consumer Durables
- Real Estate

Main insight:

> Trade remained the largest credit recipient throughout the period. Private Households and Consumer Durables showed steady growth, while Real Estate remained relatively stable.

---

### 5. Monthly Change Analysis

This page compares monthly changes in cash outside banks and private sector credit.

Metrics shown:

- Cash MoM Change %
- Private Credit MoM Change %

Main insight:

> Cash outside banks showed sharper monthly swings than private sector credit. Private sector credit remained more stable even when cash movement changed sharply.

---

## Data and Method

The original CBK data was arranged in a wide spreadsheet format:

```text
Indicator | Jan-25 | Feb-25 | Mar-25 | ...
```

This format is easy to read in Excel, but it is not ideal for Power BI analysis.

For Power BI, the data was transformed into long format:

```text
Date | Indicator | Value | Unit | Category
```

This made it easier to build:

- Line charts
- Filters
- Sector comparisons
- Time-series analysis
- DAX measures
- Executive summary KPIs

---

## Data Model

The project uses two main tables.

### PowerBI_Data

This table contains monthly money supply and private credit indicators.

Columns:

```text
Date
Indicator
Value
Unit
Category
```

Example indicators:

- Money Supply M3
- Currency Outside Banks
- Demand Deposits
- Private Sector Credit
- Cash MoM Change
- Private Credit MoM Change
- Cash as % of M3
- Cash as % of Liquid Money

---

### Sector_Credit_Data

This table contains private sector credit by economic sector.

Columns:

```text
Date
Sector
Credit_Value
Unit
Category
```

Example sectors:

- Agriculture
- Manufacturing
- Trade
- Building and Construction
- Transport and Communications
- Finance and Insurance
- Real Estate
- Mining and Quarrying
- Private Households
- Consumer Durables
- Business Services
- Other Activities

---

## DAX Measures Created

The Executive Summary page uses DAX measures to calculate high-level indicators.

Examples:

```DAX
M3 Growth %
Credit Growth %
Cash Max Swing
Agri Share %
```

These measures help summarize:

- Total money supply growth
- Total private sector credit growth
- Maximum monthly cash movement
- Agriculture’s share of total private sector credit

---

## Dashboard Insights by Page

| Page | Main Question | Main Insight |
|---|---|---|
| Executive Summary | What are the key findings? | M3 grew faster than private credit |
| Overview | Are money and credit growing? | Both grew, but M3 grew faster |
| Sector Credit Analysis | Who receives the most credit? | Trade received the highest credit |
| Sector Credit Trends | How did top sectors change over time? | Trade remained dominant |
| Monthly Change Analysis | Which is more volatile, cash or credit? | Cash outside banks was more volatile |

---

## Quick Start

Clone the repository:

```bash
git clone https://github.com/MastaT002/kenya-money-supply-private-credit-dashboard.git
```

Open the Power BI dashboard file:

```text
powerbi/CBK_Money_Supply_Private_Credit_Trends.pbix
```

Then open it in **Power BI Desktop**.

No database connection is required because the data is already embedded in the Power BI file.

If Power BI Desktop is not installed, browse the `/screenshots/` folder for static dashboard previews.

---

## Project Structure

```text
kenya-money-supply-private-credit-dashboard/
├── data/           # Cleaned Excel dataset
├── powerbi/        # .pbix dashboard file
├── screenshots/    # Page-by-page previews
├── docs/           # Original CBK source PDFs
├── LICENSE
└── README.md
```

---

## Limitations

This is an exploratory business intelligence analysis, not a full macroeconomic model.

To answer **“why is credit lagging M3?”** fully, additional data would be needed, including:

- CBK interest rate decisions over the period
- Government securities uptake
- Treasury bill rates
- Commercial bank lending rates
- Inflation and exchange rate data
- Non-performing loan ratios by sector

To determine whether December/January cash swings are seasonal or abnormal, more historical data would be needed.

To classify credit as productive or consumption-based, a formal sector grouping model would be needed.

This dashboard flags the questions. Deeper answers require deeper data.

---

## What’s Next

| Phase | Focus | Data Needed |
|---|---|---|
| Phase 2: Transmission Analysis | Where does excess liquidity go? | Government securities, T-bill rates, lending rates, inflation |
| Phase 3: Sector Grouping | Productive vs consumption credit | Sector classification model |
| Phase 4: Forecasting | Early warning signals | Multi-year historical data, trend forecasting |

---

## Files Included

| Folder | Contents |
|---|---|
| data | Cleaned Excel dataset used in Power BI |
| powerbi | Power BI `.pbix` dashboard file |
| screenshots | Dashboard page screenshots |
| docs | Original CBK source documents |
| README.md | Project documentation |
| LICENSE | MIT License |

---

## Skills Demonstrated

This project demonstrates:

- Data cleaning
- Data transformation
- Power BI dashboard design
- Power Query usage
- DAX measure creation
- Time-series analysis
- Sector-level credit analysis
- Business intelligence storytelling
- Economic data interpretation
- Executive summary reporting
- Dashboard documentation using GitHub

---
## About

**Trevor Mulundi (MastaT)**

Data Analytics and Business Intelligence Portfolio Project

---

## License

MIT License — see `LICENSE` for details.

Original data credited to the Central Bank of Kenya. Used for analytical and educational purposes.
