# R-D-Quad-Analysis
This analysis is designed to identify projects that may be dilutive to R&D portfolio performance. This approach is particularly valuable for organizations experiencing R&D-to-income ratios that exceed industry benchmarks and to help drive actionable insights for executive decision-makers seeking to optimize resource allocation across their innovation portfolio.


## Strategy Model
When building a model for this company,  we identified 4 variables:

### Quantitative Variables:
**1. Gross Profit Variance:** Product Segment Gross Profit Performance in comparison to the Parent Company’s Gross Profit. 

**2. Discounted Payback Period:** The time it will likely take to get a return on dollars invested.

### Qualitative Variables:
**3. Risk Score:** After a comprehensive assessment on past performance, economic, and political factors, the Chief Strategy Officer or a Strategy Team lead will assign a score that’s in the range of 0 to 10. 

**4. Strategy Score:** Like the risk score, the Chief Strategy Officer or Strategy Team lead assigns a score from 0 to 10 based on how well the project aligns with the company's future. 

## Scoring Logic
For more information on how the quantitative variables are calculated and the scoring logic, refer to the following powerpoint file in this repository: *R&D Strategy Scoring Logic.pptx*

## Plotting to Quad
Once all financial data was collected and Strategy leadership scored all projects, the Project Names, Quantitative Scores, and Qualitative Scores were keyed into their respective data frames in the following script: *rd_jupyter_script* which ended up looking like the Quad in the following file: *R&D Script Results & Interpretation.pptx*

*Note: actual values could not be used since this is a public repository*

## Interpretation:
Quad 1: Top Left - High Qualitative Score, High Quantitative Score - *Recommendation: Sustain or Increase Spend*

Quad 2: Top Right - High Qualitative Score, Low Quantitative Score - *Recommendation: Optimize operational efficiency or reduce spend*

Quad 3: Bottom Left - Low Qualitative Score, High Quantitative Score - *Recommendation: Optimize operational efficiency or reduce spend*

Quad 4: Bottom Right - Low Qualitative Score, Low Quantitative Score - *Recommendation: Cut or defer program*

Depending on where a project falls you can derive assumptions that should be thouroughly reviewed and discussed with leadership. 


## Outcome
Deploying this model at the enterprise level, identified a significant cost-saving opportunity of $85M for the parent organization. Subsequent in-depth analysis and executive stakeholder review across all subsidiaries resulted in ~$10M of actualized savings and operating profit improvement for fiscal year 2025, with an additional ~$25M forecasted for 2026.

Feedback from engineering leadership indicated that the model's scoring framework substantially improved resource allocation decision-making, enabling more strategic deployment of technical talent across initiatives.
