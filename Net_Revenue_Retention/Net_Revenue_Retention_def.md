# Net Revenue Retention

*Alternative Name: Net Dollar Retention (NDR)*

## Definition

Net Revenue Retention (NRR), also known as Net Dollar Retention (NDR), measures the percentage of recurring revenue retained over a specific period. It captures lost revenue from customer attrition, reduced usage, or subscription downgrades, offset by expansion from existing customers through upsells, cross-sells, price increases, or increased usage. The “net” terminology reflects how lost revenue is offset against expansion revenue.

## Business Value and Insights

NRR indicates revenue stability by measuring retention on a revenue basis rather than customer count, and includes growth potential from existing customers. High-NRR businesses are more predictable and demonstrate stronger growth potential since churn creates less revenue drain. Revenue churn and downsells negatively impact NRR, but upsell and cross-sell activities can offset these losses. Companies with higher NRR typically experience lower churn and healthy expansion revenue. NRR typically exceeds 100% but may fall below this threshold for companies experiencing shrinking existing customer revenue or limited expansion opportunities.

## Calculation Formula

### Calculation #1: Cohort Method

$$\frac{\text{MRR at the end of accounting period from the cohort of customers at the beginning of the period}}{\text{MRR from the customers at the beginning of accounting period}} = \text{NRR}$$

The cohort method represents the most accurate approach and is preferred in most situations. It compares recurring revenue for a specific customer group over time, typically annualized. For example, year-over-year measurements compare MRR from one year ago with current MRR for those same customers, excluding new customers acquired during the measurement year.

For accurate calculation, companies should use revenue rather than bookings, billings, or cash accounting. Monthly Recurring Revenue (MRR) is commonly used and suitable for most companies. Enterprise SaaS companies with longer contracts and implementation cycles can alternatively use Annual Recurring Revenue (ARR) or Contracted ARR (CARR). Using CARR captures churn occurring during the implementation cycle.

#### Data Inputs Required

Data Input #1: MRR by customer at the beginning of the measurement period.

Data Input #2: MRR by customer for the same group of customers at the end of the measurement period.

This data is typically sourced from revenue recognition schedules. When using CARR, the value may come from CRM or contract management systems.

#### Sample Calculation

| Customers on 3/1/2021 | Beginning MRR (March 2021) | Ending MRR (March 2022) |
|---|---|---|
| Customer 1 | $100.00 | $200.00 |
| Customer 2 | $200.00 | $200.00 |
| Customer 3 | $500.00 | $ - |
| Customer 4 | $200.00 | $300.00 |
| Customer 5 | $1,000.00 | $1,500.00 |
| Customer 6 | $300.00 | $200.00 |
| Customer 7 | $500.00 | $900.00 |
| Customer 8 | $1,200.00 | $1,200.00 |
| Customer 9 | $400.00 | $600.00 |
| Customer 10 | $600.00 | $ - |
| **Total MRR** | **$5,000.00** | **$5,100.00** |

$$\frac{\$5{,}100}{\$5{,}000} = 102\% \text{ Net Revenue Retention}$$

This sample demonstrates that despite some customer churn, contractions, and expansions, the net outcome retained 102% of prior-year revenue.

#### Calculation Timing

The period between beginning and ending MRR for the same customer cohort is typically one year, making NRR most intuitive and benchmarkable on an annual basis.

For measurement periods shorter than one year, results can be annualized by raising the result to the appropriate power. For quarterly measurements, raise to the 4th power; for monthly, raise to the 12th power.

Generally, longer measurement periods work best for long sales-cycle companies with large annual or multi-year contracts, while shorter periods suit companies with smaller contract values and shorter sales cycles. Regardless of measurement period, the metric is typically calculated monthly on a rolling basis.

#### Nuances to Consider

Nuance #1: The cohort approach is more accurate than the formula approach.

Nuance #2: The cohort approach does not require separate tracking of Cross-Sells, Up-Sells, or Down-Sells.

Nuance #3: Revenue recognition accelerated due to a canceled contract should not be included in beginning or ending MRR.

Nuance #4: “Win-Back Period” is the timeframe a company views a non-renewal as still possible and would count the ultimate re-start of the agreement as a renewal versus a new customer. Most companies define a “win-back” period of 30–90 days. If a churned customer renews within the win-back period, the resulting revenue counts as a renewal, not a new sale.

Nuance #5: Using CARR captures churn from customers who cancel after signing but before implementation and revenue recognition. Therefore, companies with long implementation cycles find CARR most useful.

Nuance #6: There is debate about including usage-based pricing revenue exceeding the commitment level (overages) in NRR calculations. If variable revenue is significant and included, NRR becomes more of a revenue metric than a recurring revenue stability metric. Regardless, variable revenue from usage-based pricing should be clearly highlighted and consistently applied across all revenue-based retention metrics.

Nuance #7: The cohort approach's main drawbacks are: 1) It does not capture retention performance of recently acquired customers; 2) It may not help very early-stage companies with few or no customers older than one year.

### Calculation #2: Formula Method

$$\frac{\text{Beginning MRR} - \text{Churned MRR} + \text{Expansion MRR} - \text{Contraction MRR}}{\text{Beginning MRR}} = \text{NRR}$$

The formula method divides churn for the period (adjusted for expansion or contraction revenue) by the beginning period revenue. The calculation can use ARR, CARR, or MRR.

#### Data Inputs Required

Data Input #1: Beginning MRR

Data Input #2: Churned MRR for the period

Data Input #3: Expansion (Up-Sell, Cross-Sell) MRR for the period

Data Input #4: Contraction (Down-Sell) MRR for the period

Churned MRR represents revenue from customers who canceled or did not renew during the period. Expansion MRR is incremental MRR growth from existing customers for any reason. Contraction MRR is incremental MRR loss from an existing customer for any reason.

#### Sample Calculation

##### List of Input Values

Beginning MRR: $100,000
Churned MRR in period: $9,000
Expansion MRR in period: $11,000
Contraction MRR in period: $500

##### Calculation Formula

$$\frac{\$100{,}000 - \$9{,}000 + \$11{,}000 - \$500}{\$100{,}000} = 101.5\% \text{ Net Revenue Retention}$$

#### Calculation Timing

The formula method works best for SaaS companies with smaller transaction sizes and shorter sales cycles, frequently calculated monthly or quarterly. The formula method responds more quickly to churn from new customers than the cohort method.

Over longer periods, however, the formula method is subject to out-of-cycle errors. Error potential increases with extended measurement periods, making the formula method poorly suited for annual measurements.

#### Nuances to Consider

##### Nuance #1: Formula Method is best for lower value ACV companies

The formula method is frequently used in lower annual contract value businesses with higher churn.

##### Nuance #2: Formula method is great for high growth businesses

The formula method suits high-growth businesses where many current customers have not been customers for more than one year and are therefore not captured in the cohort approach.

##### Nuance #3: Some churn or expansion may not be related to existing customer segment

The main drawback to the formula method is that some churn or expansion during the measurement period may not relate to customer revenue included in beginning MRR. This effect can introduce significant errors that become more pronounced over extended measurement periods.

Example Error: If a customer's start date was after the beginning MRR calculation date and the customer churned during the period, the retention formula would understate the retention rate for that period. In subsequent periods, the churned customer's MRR would be included in beginning MRR, but churned revenue would not, thus overstating NRR for that period.

##### Nuance #4: Usage-Based Pricing Models may require the “double back” approach

SaaS companies with most revenue derived from usage-based pricing may consider the “double back” approach. The metric is calculated using cohort methodology; however, it uses twelve months of revenue and extends back two years.

$$\frac{\text{Last 12 months (Months 13–24) of revenue from customers who had revenue 24 months ago}}{\text{Prior 12 months (Months 1–12) of revenue from customers who had revenue 24 months ago}} = \text{NRR}$$

This approach mitigates spikes in NRR resulting from the standard ramp-up period for typical usage-based pricing customers.

## Links to related Standards

Gross Revenue Retention: [Click Here](../Gross_Revenue_Retention/Gross_Revenue_Retention_def.md)
Annual Recurring Revenue (ARR): [Click Here](../Annual_Recurring_Revenue/Annual_Recurring_Revenue_def.md)
Contracted ARR (CARR): [Click Here](../Contracted_ARR/Contracted_ARR_def.md)
Logo Retention: [Click Here](../Logo_Retention/Logo_Retention_def.md)
