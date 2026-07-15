# Snowflake SaaS Operating Model & Power BI Dashboard

An Excel and Power BI portfolio project for Snowflake Inc. (`NYSE: SNOW`) covering historical financial performance, SaaS operating metrics, a four-year revenue forecast, profitability, scenario analysis, KPI reporting, and executive-level visualization.

[Original Snowflake SaaS workbook on GitHub](https://github.com/HilalBerhe/snowflake-saas-operating-model) 
> **Note:** All financial figures are in USD millions unless otherwise stated.

## Project overview

This project translates Snowflake's historical operating performance into a driver-based forecast for FY2027E through FY2030E. The Excel model separates product revenue from professional services, applies segment-level gross-margin assumptions, forecasts operating expenses as a percentage of revenue, and presents the results through downside, base, and upside scenarios.

The Power BI report turns the model outputs into a three-page management dashboard covering the executive outlook, financial forecast, SaaS metrics, customer growth, and scenario profitability. All monetary figures are in USD millions unless otherwise stated.

## Key findings

- Total revenue increases from **$4.68 billion in FY2026A to $9.94 billion in FY2030E**, representing an approximate **20.7% CAGR**.
- Product revenue remains the primary growth engine, reaching **$9.66 billion by FY2030E**, while modeled growth gradually moderates from **25% to 18%**.
- Gross margin expands from **67.2% to 75.8%** as product margins improve and professional-services losses decline.
- Operating income moves from a **$1.44 billion loss in FY2026A** to an **$803.7 million profit in FY2027E**, reaching **$2.32 billion by FY2030E**.
- Operating margin improves from **-30.6% to 23.3%**, illustrating the potential operating leverage created by revenue growth and expense discipline.
- Free cash flow increases from **$1.12 billion to $2.88 billion**, while free-cash-flow margin reaches **29.0% by FY2030E**.
- Historical SaaS indicators remain strong: FY2026A net revenue retention is **125%**, remaining performance obligations reach **$9.77 billion**, and customers generating more than $1 million in product revenue increase to **733**.

## Power BI dashboard

The Power BI report converts the operating model into a concise management view. The report uses Power Query transformations, KPI cards, forecast tables, line charts, and scenario comparisons across three pages.

### 1. Executive overview

The first page highlights the FY2027E outlook: **$5.82 billion of revenue**, **$803.7 million of operating income**, **$1.34 billion of free cash flow**, and a **13.8% operating margin**. It also compares FY2027E revenue across the downside, base, and upside cases and shows the total-revenue forecast through FY2030E.

[![Snowflake Power BI executive overview](Snow%20Flake%20Power%20Bi%20Part%201.png)](Snow%20Flake%20Power%20Bi%20Part%201.png)

### 2. Financial forecast

The second page presents the FY2026A-FY2030E forecast in a management table and visualizes the path of revenue, operating income, and free cash flow. The model shows operating income turning positive in FY2027E and free cash flow reaching **$2.88 billion by FY2030E**.

[![Snowflake Power BI financial forecast](Snowflake%20Power%20Bi%20Part%202.png)](Snowflake%20Power%20Bi%20Part%202.png)

### 3. SaaS metrics and scenario analysis

The final page combines historical SaaS KPIs with forward-looking scenario results. Customers generating more than $1 million increase from **449 in FY2024A to 733 in FY2026A**, while the scenario comparison shows positive operating income and free cash flow in all three modeled cases.

[![Snowflake Power BI SaaS metrics and scenario analysis](Snow%20Flake%20Power%20Bi%20Part%203.png)](Snow%20Flake%20Power%20Bi%20Part%203.png)

## Workbook structure

| Worksheet | Purpose |
|---|---|
| Cover Page | Identifies the company, ticker, sector, model type, and forecast period. |
| Historical Financials | Summarizes FY2024A-FY2026A revenue, gross profit, operating expenses, earnings, and cash flow. |
| SaaS Metrics | Tracks product-revenue growth, net revenue retention, large customers, RPO, and free cash flow. |
| Revenue Build | Forecasts product revenue, professional-services revenue, and total revenue through FY2030E. |
| Operating Model | Converts revenue and margin assumptions into gross profit, operating expenses, operating income, and free cash flow. |
| Scenario Analysis | Tests FY2027E downside, base, and upside assumptions and calculates the corresponding financial results. |
| KPI Summary | Compares FY2026A with FY2027E and presents the scenario outputs in a compact management view. |
| Dashboard | Visualizes financial performance, margins, profitability, scenario results, and management commentary. |

## Historical financial performance

Snowflake's revenue grew from $2.81 billion in FY2024A to $4.68 billion in FY2026A. Gross profit increased to $3.15 billion, while the company continued to report a GAAP operating loss because sales and marketing, research and development, and general and administrative spending remained above gross profit. Despite the reported operating loss, free cash flow remained positive and reached $1.12 billion in FY2026A.

## SaaS operating metrics

| Metric | FY2024A | FY2025A | FY2026A |
|---|---:|---:|---:|
| Product revenue | $2,666.8 | $3,462.4 | $4,472.3 |
| Product revenue growth | — | 29.8% | 29.2% |
| Net revenue retention | 133% | 126% | 125% |
| Customers with more than $1M of product revenue | 449 | 576 | 733 |
| Forbes Global 2000 customers | 716 | 750 | 790 |
| Remaining performance obligations | $5,174.7 | $6,867.5 | $9,771.5 |
| RPO / revenue | 1.84x | 1.89x | 2.09x |
| Free-cash-flow margin | 27.8% | 24.4% | 23.9% |

These KPIs show a business with strong customer expansion, growing contracted revenue visibility, and positive cash generation. Net revenue retention above 100% indicates that the existing customer base is expanding its spending, while rising RPO provides additional visibility into future revenue.

## Revenue forecast

| Metric | FY2026A | FY2027E | FY2028E | FY2029E | FY2030E |
|---|---:|---:|---:|---:|---:|
| Product revenue | $4,472.3 | $5,590.4 | $6,820.3 | $8,184.3 | $9,657.5 |
| Product revenue growth | 29.2% | 25.0% | 22.0% | 20.0% | 18.0% |
| Professional services and other revenue | $211.6 | $232.8 | $251.4 | $266.5 | $279.8 |
| Professional services growth | 29.0% | 10.0% | 8.0% | 6.0% | 5.0% |
| Total revenue | $4,683.9 | $5,823.1 | $7,071.6 | $8,450.8 | $9,937.3 |
| Total revenue growth | — | 24.3% | 21.4% | 19.5% | 17.6% |

The forecast assumes continued expansion in Snowflake's core product business, with growth moderating as the revenue base becomes larger. Professional services remain a small portion of the revenue mix, keeping the model primarily tied to the economics of the cloud platform.

## Forecast assumptions

| Driver | FY2027E | FY2028E | FY2029E | FY2030E |
|---|---:|---:|---:|---:|
| Product revenue growth | 25.0% | 22.0% | 20.0% | 18.0% |
| Professional services growth | 10.0% | 8.0% | 6.0% | 5.0% |
| Product gross margin | 75.0% | 76.0% | 77.0% | 78.0% |
| Services gross margin | -10.0% | -5.0% | 0.0% | 0.0% |
| Sales and marketing / revenue | 33.0% | 32.0% | 31.0% | 30.0% |
| Research and development / revenue | 19.0% | 18.5% | 18.0% | 17.5% |
| General and administrative / revenue | 5.8% | 5.5% | 5.3% | 5.0% |
| Free-cash-flow margin | 23.0% | 25.0% | 27.0% | 29.0% |

## Operating model output

| Metric | FY2026A | FY2027E | FY2028E | FY2029E | FY2030E |
|---|---:|---:|---:|---:|---:|
| Total revenue | $4,683.9 | $5,823.1 | $7,071.6 | $8,450.8 | $9,937.3 |
| Total gross profit | $3,146.1 | $4,169.5 | $5,170.8 | $6,301.9 | $7,532.8 |
| Gross margin | 67.2% | 71.6% | 73.1% | 74.6% | 75.8% |
| Total operating expenses | $4,581.3 | $3,365.8 | $3,960.1 | $4,588.8 | $5,217.1 |
| Operating income / loss | $(1,435.2) | $803.7 | $1,210.7 | $1,713.1 | $2,315.8 |
| Operating margin | -30.6% | 13.8% | 17.1% | 20.3% | 23.3% |
| Free cash flow | $1,120.3 | $1,339.3 | $1,767.9 | $2,281.7 | $2,881.8 |
| Free-cash-flow margin | 23.9% | 23.0% | 25.0% | 27.0% | 29.0% |

The central profitability thesis is margin expansion. Product gross margin improves while sales and marketing, research and development, and general and administrative costs decline as percentages of revenue. This creates operating leverage and allows gross-profit growth to translate into positive operating income.

## Scenario analysis

The scenario analysis changes revenue growth, gross margins, operating-expense ratios, and free-cash-flow margins to evaluate a range of FY2027E outcomes.

| Metric | Downside | Base | Upside |
|---|---:|---:|---:|
| Total revenue | $5,499 | $7,244 | $9,148 |
| Gross margin | 69.6% | 72.0% | 73.5% |
| Operating income | $393 | $1,028 | $1,739 |
| Operating margin | 7.1% | 14.2% | 19.0% |
| Free cash flow | $1,100 | $1,666 | $2,287 |

All three modeled cases generate positive operating income and free cash flow. The downside case demonstrates financial resilience, while the upside case shows the earnings and cash-flow potential created by stronger revenue growth, higher gross margins, and lower operating expenses as a share of revenue.

## KPI summary

The KPI Summary provides a compact comparison of FY2026A and FY2027E. In the operating forecast, product revenue grows 25.0%, total revenue grows 24.3%, and gross profit grows 32.5%. Gross margin expands by approximately 440 basis points, and operating income improves by approximately $2.24 billion. Free cash flow grows 19.6%, although the modeled margin temporarily declines by about 90 basis points before expanding in later forecast years.

## Excel executive dashboard

The dashboard brings the main decision-useful outputs together in one view:

- FY2026A versus FY2027E revenue and gross profit
- Gross, operating, and free-cash-flow margins
- Operating income and free cash flow
- Downside, base, and upside scenario results
- Management commentary on growth, profitability, resilience, and priorities

## Core model formulas

The workbook uses a straightforward driver-based approach:

```text
Product Revenue = Prior-Year Product Revenue × (1 + Product Revenue Growth)
Services Revenue = Prior-Year Services Revenue × (1 + Services Revenue Growth)
Total Revenue = Product Revenue + Services Revenue

Product Gross Profit = Product Revenue × Product Gross Margin
Services Gross Profit = Services Revenue × Services Gross Margin
Total Gross Profit = Product Gross Profit + Services Gross Profit
Gross Margin = Total Gross Profit ÷ Total Revenue

Operating Expense = Total Revenue × Expense as % of Revenue
Operating Income = Total Gross Profit − Total Operating Expenses
Operating Margin = Operating Income ÷ Total Revenue

Free Cash Flow = Total Revenue × Free-Cash-Flow Margin
```

## How to use the model

1. Download `SnowFlake Saas Operating Model.xlsx` and open it in Microsoft Excel.
2. Begin with **Historical Financials** and **SaaS Metrics** to understand the operating history.
3. Review the growth assumptions in **Revenue Build**.
4. Adjust the margin and operating-expense assumptions in **Operating Model**.
5. Change the downside, base, and upside drivers in **Scenario Analysis**.
6. Review the linked outputs in **KPI Summary** and **Dashboard**.
7. Review the three Power BI dashboard pages included above.

The workbook uses orange section headers for navigation and blue font to identify key historical values and forecast assumptions. Linked model outputs are presented in black.

## Repository structure

```text
snowflake-saas-operating-model/
├── README.md
├── SnowFlake Saas Operating Model.xlsx
├── Snow Flake Power Bi Part 1.png
├── Snowflake Power Bi Part 2.png
└── Snow Flake Power Bi Part 3.png
```

## Skills demonstrated

- Driver-based revenue forecasting
- SaaS KPI and unit-economics analysis
- Income-statement and free-cash-flow modeling
- Gross-margin and operating-leverage analysis
- Downside, base, and upside scenario planning
- Excel formulas, cross-sheet links, formatting, and charting
- Power BI dashboard design and executive reporting
- Power Query data transformation and unpivoting
- KPI cards, forecast visualizations, and scenario comparisons
- Executive dashboard design and management commentary

## Scope and disclaimer

This Excel model and Power BI report are independent educational and portfolio projects. They are not affiliated with or endorsed by Snowflake Inc. Historical figures are presented for modeling purposes, and all forward-looking estimates are assumption-driven illustrations rather than company guidance or investment advice. The model focuses on operating performance and does not include a full balance sheet, debt schedule, tax schedule, discounted-cash-flow valuation, or investment recommendation.

## Author

**Hilal Berhe**
[GitHub profile](https://github.com/HilalBerhe)

README.md
# Snowflake SaaS Operating Model & Power BI Dashboard

An Excel and Power BI portfolio project for Snowflake Inc. (`NYSE: SNOW`) covering historical financial performance, SaaS operating metrics, a four-year revenue forecast, profitability, scenario analysis, KPI reporting, and executive-level visualization.

[Original Snowflake SaaS workbook on GitHub](https://github.com/HilalBerhe/snowflake-saas-operating-model) | [Download the Excel model](SnowFlake%20Saas%20Operating%20Model.xlsx)

> **Note:** All financial figures are in USD millions unless otherwise stated.

## Project overview

This project translates Snowflake's historical operating performance into a driver-based forecast for FY2027E through FY2030E. The Excel model separates product revenue from professional services, applies segment-level gross-margin assumptions, forecasts operating expenses as a percentage of revenue, and presents the results through downside, base, and upside scenarios.

The Power BI report turns the model outputs into a three-page management dashboard covering the executive outlook, financial forecast, SaaS metrics, customer growth, and scenario profitability. All monetary figures are in USD millions unless otherwise stated.

## Key findings

- Total revenue increases from **$4.68 billion in FY2026A to $9.94 billion in FY2030E**, representing an approximate **20.7% CAGR**.
- Product revenue remains the primary growth engine, reaching **$9.66 billion by FY2030E**, while modeled growth gradually moderates from **25% to 18%**.
- Gross margin expands from **67.2% to 75.8%** as product margins improve and professional-services losses decline.
- Operating income moves from a **$1.44 billion loss in FY2026A** to an **$803.7 million profit in FY2027E**, reaching **$2.32 billion by FY2030E**.
- Operating margin improves from **-30.6% to 23.3%**, illustrating the potential operating leverage created by revenue growth and expense discipline.
- Free cash flow increases from **$1.12 billion to $2.88 billion**, while free-cash-flow margin reaches **29.0% by FY2030E**.
- Historical SaaS indicators remain strong: FY2026A net revenue retention is **125%**, remaining performance obligations reach **$9.77 billion**, and customers generating more than $1 million in product revenue increase to **733**.

## Power BI dashboard

The Power BI report converts the operating model into a concise management view. The report uses Power Query transformations, KPI cards, forecast tables, line charts, and scenario comparisons across three pages.

### 1. Executive overview

The first page highlights the FY2027E outlook: **$5.82 billion of revenue**, **$803.7 million of operating income**, **$1.34 billion of free cash flow**, and a **13.8% operating margin**. It also compares FY2027E revenue across the downside, base, and upside cases and shows the total-revenue forecast through FY2030E.

[![Snowflake Power BI executive overview](Snow%20Flake%20Power%20Bi%20Part%201.png)](Snow%20Flake%20Power%20Bi%20Part%201.png)

### 2. Financial forecast

The second page presents the FY2026A-FY2030E forecast in a management table and visualizes the path of revenue, operating income, and free cash flow. The model shows operating income turning positive in FY2027E and free cash flow reaching **$2.88 billion by FY2030E**.

[![Snowflake Power BI financial forecast](Snowflake%20Power%20Bi%20Part%202.png)](Snowflake%20Power%20Bi%20Part%202.png)

### 3. SaaS metrics and scenario analysis

The final page combines historical SaaS KPIs with forward-looking scenario results. Customers generating more than $1 million increase from **449 in FY2024A to 733 in FY2026A**, while the scenario comparison shows positive operating income and free cash flow in all three modeled cases.

[![Snowflake Power BI SaaS metrics and scenario analysis](Snow%20Flake%20Power%20Bi%20Part%203.png)](Snow%20Flake%20Power%20Bi%20Part%203.png)

## Workbook structure

| Worksheet | Purpose |
|---|---|
| Cover Page | Identifies the company, ticker, sector, model type, and forecast period. |
| Historical Financials | Summarizes FY2024A-FY2026A revenue, gross profit, operating expenses, earnings, and cash flow. |
| SaaS Metrics | Tracks product-revenue growth, net revenue retention, large customers, RPO, and free cash flow. |
| Revenue Build | Forecasts product revenue, professional-services revenue, and total revenue through FY2030E. |
| Operating Model | Converts revenue and margin assumptions into gross profit, operating expenses, operating income, and free cash flow. |
| Scenario Analysis | Tests FY2027E downside, base, and upside assumptions and calculates the corresponding financial results. |
| KPI Summary | Compares FY2026A with FY2027E and presents the scenario outputs in a compact management view. |
| Dashboard | Visualizes financial performance, margins, profitability, scenario results, and management commentary. |

## Historical financial performance

Snowflake's revenue grew from $2.81 billion in FY2024A to $4.68 billion in FY2026A. Gross profit increased to $3.15 billion, while the company continued to report a GAAP operating loss because sales and marketing, research and development, and general and administrative spending remained above gross profit. Despite the reported operating loss, free cash flow remained positive and reached $1.12 billion in FY2026A.

## SaaS operating metrics

| Metric | FY2024A | FY2025A | FY2026A |
|---|---:|---:|---:|
| Product revenue | $2,666.8 | $3,462.4 | $4,472.3 |
| Product revenue growth | — | 29.8% | 29.2% |
| Net revenue retention | 133% | 126% | 125% |
| Customers with more than $1M of product revenue | 449 | 576 | 733 |
| Forbes Global 2000 customers | 716 | 750 | 790 |
| Remaining performance obligations | $5,174.7 | $6,867.5 | $9,771.5 |
| RPO / revenue | 1.84x | 1.89x | 2.09x |
| Free-cash-flow margin | 27.8% | 24.4% | 23.9% |

These KPIs show a business with strong customer expansion, growing contracted revenue visibility, and positive cash generation. Net revenue retention above 100% indicates that the existing customer base is expanding its spending, while rising RPO provides additional visibility into future revenue.

## Revenue forecast

| Metric | FY2026A | FY2027E | FY2028E | FY2029E | FY2030E |
|---|---:|---:|---:|---:|---:|
| Product revenue | $4,472.3 | $5,590.4 | $6,820.3 | $8,184.3 | $9,657.5 |
| Product revenue growth | 29.2% | 25.0% | 22.0% | 20.0% | 18.0% |
| Professional services and other revenue | $211.6 | $232.8 | $251.4 | $266.5 | $279.8 |
| Professional services growth | 29.0% | 10.0% | 8.0% | 6.0% | 5.0% |
| Total revenue | $4,683.9 | $5,823.1 | $7,071.6 | $8,450.8 | $9,937.3 |
| Total revenue growth | — | 24.3% | 21.4% | 19.5% | 17.6% |

The forecast assumes continued expansion in Snowflake's core product business, with growth moderating as the revenue base becomes larger. Professional services remain a small portion of the revenue mix, keeping the model primarily tied to the economics of the cloud platform.

## Forecast assumptions

| Driver | FY2027E | FY2028E | FY2029E | FY2030E |
|---|---:|---:|---:|---:|
| Product revenue growth | 25.0% | 22.0% | 20.0% | 18.0% |
| Professional services growth | 10.0% | 8.0% | 6.0% | 5.0% |
| Product gross margin | 75.0% | 76.0% | 77.0% | 78.0% |
| Services gross margin | -10.0% | -5.0% | 0.0% | 0.0% |
| Sales and marketing / revenue | 33.0% | 32.0% | 31.0% | 30.0% |
| Research and development / revenue | 19.0% | 18.5% | 18.0% | 17.5% |
| General and administrative / revenue | 5.8% | 5.5% | 5.3% | 5.0% |
| Free-cash-flow margin | 23.0% | 25.0% | 27.0% | 29.0% |

## Operating model output

| Metric | FY2026A | FY2027E | FY2028E | FY2029E | FY2030E |
|---|---:|---:|---:|---:|---:|
| Total revenue | $4,683.9 | $5,823.1 | $7,071.6 | $8,450.8 | $9,937.3 |
| Total gross profit | $3,146.1 | $4,169.5 | $5,170.8 | $6,301.9 | $7,532.8 |
| Gross margin | 67.2% | 71.6% | 73.1% | 74.6% | 75.8% |
| Total operating expenses | $4,581.3 | $3,365.8 | $3,960.1 | $4,588.8 | $5,217.1 |
| Operating income / loss | $(1,435.2) | $803.7 | $1,210.7 | $1,713.1 | $2,315.8 |
| Operating margin | -30.6% | 13.8% | 17.1% | 20.3% | 23.3% |
| Free cash flow | $1,120.3 | $1,339.3 | $1,767.9 | $2,281.7 | $2,881.8 |
| Free-cash-flow margin | 23.9% | 23.0% | 25.0% | 27.0% | 29.0% |

The central profitability thesis is margin expansion. Product gross margin improves while sales and marketing, research and development, and general and administrative costs decline as percentages of revenue. This creates operating leverage and allows gross-profit growth to translate into positive operating income.

## Scenario analysis

The scenario analysis changes revenue growth, gross margins, operating-expense ratios, and free-cash-flow margins to evaluate a range of FY2027E outcomes.

| Metric | Downside | Base | Upside |
|---|---:|---:|---:|
| Total revenue | $5,499 | $7,244 | $9,148 |
| Gross margin | 69.6% | 72.0% | 73.5% |
| Operating income | $393 | $1,028 | $1,739 |
| Operating margin | 7.1% | 14.2% | 19.0% |
| Free cash flow | $1,100 | $1,666 | $2,287 |

All three modeled cases generate positive operating income and free cash flow. The downside case demonstrates financial resilience, while the upside case shows the earnings and cash-flow potential created by stronger revenue growth, higher gross margins, and lower operating expenses as a share of revenue.

## KPI summary

The KPI Summary provides a compact comparison of FY2026A and FY2027E. In the operating forecast, product revenue grows 25.0%, total revenue grows 24.3%, and gross profit grows 32.5%. Gross margin expands by approximately 440 basis points, and operating income improves by approximately $2.24 billion. Free cash flow grows 19.6%, although the modeled margin temporarily declines by about 90 basis points before expanding in later forecast years.

## Excel executive dashboard

The dashboard brings the main decision-useful outputs together in one view:

- FY2026A versus FY2027E revenue and gross profit
- Gross, operating, and free-cash-flow margins
- Operating income and free cash flow
- Downside, base, and upside scenario results
- Management commentary on growth, profitability, resilience, and priorities

## Core model formulas

The workbook uses a straightforward driver-based approach:

```text
Product Revenue = Prior-Year Product Revenue × (1 + Product Revenue Growth)
Services Revenue = Prior-Year Services Revenue × (1 + Services Revenue Growth)
Total Revenue = Product Revenue + Services Revenue

Product Gross Profit = Product Revenue × Product Gross Margin
Services Gross Profit = Services Revenue × Services Gross Margin
Total Gross Profit = Product Gross Profit + Services Gross Profit
Gross Margin = Total Gross Profit ÷ Total Revenue

Operating Expense = Total Revenue × Expense as % of Revenue
Operating Income = Total Gross Profit − Total Operating Expenses
Operating Margin = Operating Income ÷ Total Revenue

Free Cash Flow = Total Revenue × Free-Cash-Flow Margin
```

## How to use the model

1. Download `SnowFlake Saas Operating Model.xlsx` and open it in Microsoft Excel.
2. Begin with **Historical Financials** and **SaaS Metrics** to understand the operating history.
3. Review the growth assumptions in **Revenue Build**.
4. Adjust the margin and operating-expense assumptions in **Operating Model**.
5. Change the downside, base, and upside drivers in **Scenario Analysis**.
6. Review the linked outputs in **KPI Summary** and **Dashboard**.
7. Review the three Power BI dashboard pages included above.

The workbook uses orange section headers for navigation and blue font to identify key historical values and forecast assumptions. Linked model outputs are presented in black.

## Repository structure

```text
snowflake-saas-operating-model/
├── README.md
├── SnowFlake Saas Operating Model.xlsx
├── Snow Flake Power Bi Part 1.png
├── Snowflake Power Bi Part 2.png
└── Snow Flake Power Bi Part 3.png
```

## Skills demonstrated

- Driver-based revenue forecasting
- SaaS KPI and unit-economics analysis
- Income-statement and free-cash-flow modeling
- Gross-margin and operating-leverage analysis
- Downside, base, and upside scenario planning
- Excel formulas, cross-sheet links, formatting, and charting
- Power BI dashboard design and executive reporting
- Power Query data transformation and unpivoting
- KPI cards, forecast visualizations, and scenario comparisons
- Executive dashboard design and management commentary

## Scope and disclaimer

This Excel model and Power BI report are independent educational and portfolio projects. They are not affiliated with or endorsed by Snowflake Inc. Historical figures are presented for modeling purposes, and all forward-looking estimates are assumption-driven illustrations rather than company guidance or investment advice. The model focuses on operating performance and does not include a full balance sheet, debt schedule, tax schedule, discounted-cash-flow valuation, or investment recommendation.

## Author

**Hilal Berhe**
[GitHub profile](https://github.com/HilalBerhe)
