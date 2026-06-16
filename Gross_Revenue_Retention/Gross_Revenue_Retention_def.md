# Gross Revenue Retention

*Alternative Name: Gross Dollar Retention (GDR)*

## Definition

Gross Revenue Retention (GRR), also known as Gross Dollar Retention (GDR), measures the percentage of recurring revenue that is retained over a specific period of time. It captures lost revenue from customer departures or reduced usage commitments.

By contrast, Net Revenue Retention encompasses expansion revenue, while GRR focuses exclusively on churn and downsell effects from existing customers.

## Business Value and Insights

GRR serves as a critical stability indicator for SaaS enterprises. Companies achieving high GRR demonstrate greater predictability and expansion potential since churn doesn't significantly drain resources. Customer churn represents the primary downward pressure on GRR. Organizations with elevated GRR typically maintain low churn alongside healthy expansion from current customers. GRR will always be less than 100% as it does not include up-sell, cross-sell or usage expansion from existing customers.

## Calculation Formula

### Calculation #1: Cohort Method

$$\frac{\text{Adjusted MRR}^1 \text{ from the cohort of customers at the end of the period}}{\text{MRR at the beginning of the measurement period}}$$

<sup>1</sup> Adjusted MRR is the lesser of the beginning MRR or the current month's MRR. This technique mathematically eliminates expansion revenue while capturing shrinkage and churn.

The cohort method represents the most accurate approach and is preferred in most situations. It compares recurring revenue for a specific customer group over time. Beginning MRR appears in column one; current month MRR for those identical customers occupies column two; the third column, “Adjusted MRR,” equals the lesser of beginning or current MRR.

For this calculation, it's important to use recognized revenue and not bookings, billings, or cash accounting. Enterprise-focused SaaS companies with longer contracts and implementation cycles may employ Annual Recurring Revenue (ARR) or Contracted ARR (CARR). CARR captures churn during implementation and before revenue recognition.

#### Data Inputs Required

Data Input #1: MRR by customer at the beginning of the measurement period.

Data Input #2: Adjusted MRR<sup>1</sup> for that same group of customers at the end of the period.

<sup>1</sup> Adjusted MRR is the lesser of the beginning MRR or the current month's MRR. This technique mathematically eliminates expansion revenue while capturing shrinkage and churn.

The revenue recognition schedule contains most MRR data, and CARR might be found in the CRM or contract management system.

#### Sample Calculation

| Customers on 3/1/2021 | Beginning MRR (March 2021) | Ending MRR (March 2022) | Adjusted MRR (March 2022)<sup>1</sup> |
|---|---|---|---|
| Customer 1 | $100.00 | $200.00 | $100.00 |
| Customer 2 | $200.00 | $200.00 | $200.00 |
| Customer 3 | $500.00 | $ - | $ - |
| Customer 4 | $200.00 | $500.00 | $200.00 |
| Customer 5 | $300.00 | $1,500.00 | $300.00 |
| Customer 6 | $1,000.00 | $900.00 | $900.00 |
| Customer 7 | $300.00 | $200.00 | $200.00 |
| Customer 8 | $1,200.00 | $1,200.00 | $1,200.00 |
| Customer 9 | $400.00 | $600.00 | $400.00 |
| Customer 10 | $600.00 | $ - | $ - |
| **Total MRR** | **$5,000.00** | **$5,100.00** | **$3,800.00** |

<sup>1</sup> Adjusted MRR is the lesser of Beginning or Ending MRR.

$$\text{Gross Revenue Retention} = \frac{\$3{,}800}{\$5{,}000} = 76\%$$

$$\text{Net Revenue Retention} = \frac{\$5{,}100}{\$5{,}000} = 102\%$$

In the above sample calculation, some customers churned, some contracted, and some expanded; however, the GRR calculation only adjusts for contraction and churn. GRR can never exceed 100%.

#### Calculation Timing

The time period between beginning and ending MRR for the same customer set typically spans one year. Using GRR as an annual measurement is the most intuitive and easy to benchmark.

For measurement periods shorter than one year, annualization occurs by raising the result to the appropriate power. For quarterly measurements, use the 4th power; for monthly measurements, use the 12th power.

Generally, longer measurement periods benefit long sales-cycle companies with larger annual or multi-year contracts, while shorter periods suit companies with smaller contract values and shorter sales cycles. Regardless of measurement period, the metric is typically calculated monthly on a rolling basis.

#### Nuances to Consider

Nuance #1: The cohort approach is considered more accurate than the formula approach, whose deficiencies are outlined below.

Nuance #2: When using MRR, the cohort approach does not require separate tracking of revenue contraction or churn; it is embedded in the Adjusted Ending MRR.

Nuance #3: Revenue recognition accelerated due to a canceled contract should not be included in the beginning or ending MRR.

Nuance #4: Most companies define a “win-back” period of 30–90 days. If a churned customer renews within the win-back period, the resulting revenue is counted as a renewal and not a new sale.

Nuance #5: Using Contracted ARR (CARR) instead of MRR captures the churn of customers who cancel after signing their contract but before implementation is complete and revenue is recognized. This is a useful measure for companies with long implementation cycles.

Nuance #6: We recommend excluding variable revenue from usage-based pricing in the GRR calculation. GRR would capture the downside of variable “Usage-Based Revenue” and is not particularly helpful in understanding overall retention trends.

Nuance #7: The cohort approach's main drawbacks are: 1) It does not capture the retention performance of recently acquired customers; and 2) It may not be helpful for a new business with few or no customers older than one year.

### Calculation #2: Formula Method

$$\left(\frac{\text{Beginning MRR} - \text{Churned MRR} - \text{Down-Sell MRR}}{\text{Beginning MRR}}\right) \times 100 = \text{GRR (\%)}$$

The formula method divides churn for the period (adjusted for any expansion or contraction revenue) by the beginning revenue for the period. The calculation can use either Annual Recurring Revenue (ARR) or Monthly Recurring Revenue (MRR), with MRR being the most common.

#### Data Inputs Required

Data Input #1: Beginning MRR

Data Input #2: Churned MRR for the period

Data Input #3: Down-Sell MRR for the period

Churned MRR results from customers who canceled or did not renew in the period. Down-Sell MRR is the incremental MRR lost from existing customers due to a reduction in subscription commitment or other decrease in Contracted MRR.

#### Sample Calculation using MRR

##### List of Input Values

Beginning MRR: $100,000
Churned MRR in period: $1,000
Contraction MRR in period: $500

##### Calculation Formula

$$\text{GRR} = 1 - \frac{\$1{,}000 + \$500}{\$100{,}000} = 1 - \frac{\$1{,}500}{\$100{,}000} = 1 - 0.015 = 0.985 \text{ or } 98.5\%$$

If the above measurement period were one month, the annualized GRR metric would be:

$$\text{GRR} = 0.985^{12} = 83.4\%$$

If the measurement period were one quarter, the annualized GRR would be:

$$\text{GRR} = 0.985^{4} = 94.1\%$$

#### Calculation Timing

The calculation can cover a month, quarter, or year but is most accurate when measuring monthly time periods. Quarterly calculations are typically annualized, but monthly numbers might not be appropriate for annualization due to their inherent variability. Using the formula method over a year-long period introduces errors which are described below.

#### Nuances to Consider

The formula method is frequently used with lower annual contract value businesses that have relatively high churn. For example, it's frequently used in B2C and telecom companies who benchmark themselves based on monthly churn. The formula approach is also good for high growth businesses where many of the current customers have not been customers for more than one year and are therefore not captured in the cohort approach.

The main drawback to the formula approach is that some churn (or expansion) which occurs during the measurement period may not be related to customer revenue included in the beginning MRR, which is the denominator in the calculation. This effect can introduce significant errors in the calculation and becomes more pronounced over longer measurement periods.

## Links to related Standards

Contracted Annual Recurring Revenue (CARR) Standard: [Click Here](../Contracted_ARR/Contracted_ARR_def.md)
Annual Recurring Revenue (ARR) Standard: [Click Here](../Annual_Recurring_Revenue/Annual_Recurring_Revenue_def.md)
Net Revenue Retention (NRR) Standard: [Click Here](../Net_Revenue_Retention/Net_Revenue_Retention_def.md)
