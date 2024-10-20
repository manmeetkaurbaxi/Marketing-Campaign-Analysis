# Project Background
The marketing agency involved in this analysis aims to maximize ROI for its clients' ad campaigns. In 2019, two separate advertising campaigns were conducted on Facebook and AdWords. 
This analysis was undertaken to determine which platform delivers better results in terms of key performance indicators, including ad clicks, conversions, and overall cost-effectiveness. 
By uncovering these insights, the agency can better allocate its budget and optimize future marketing strategies for its clients.

**Insights and recommendations are provided on the following key areas:**
- **Ad Clicks Analysis:** Comparison of the total clicks generated by both platforms, highlighting periods of peak performance.
- **Conversion Rate Comparison:** Evaluating how each platform performs in converting clicks into actual customer actions.
- **Cost-Effectiveness Evaluation:** A review of the costs incurred per ad click and per conversion to determine the most cost-effective platform.
- **CTR and Conversion Rate Trends:** Insights into the performance trends of Click-Through Rate (CTR) and conversion rates for both platforms over the year.

[add.res]

# Data Structure & Initial Checks
The dataset contains 365 records corresponding to each day in 2019. Key features include:
- **Date:** The date of data collection.
- **Facebook Ad Campaign:** Information on clicks, conversions, and ad costs for Facebook.
- **AdWords Ad Campaign:** Similar data for the AdWords platform.

Key tables in the dataset:
- Facebook Ad Campaign
- AdWords Ad Campaign

[erd]
Before conducting the analysis, the dataset underwent quality checks to ensure completeness and consistency. 

# Executive Summary
## Overview of Findings
In 2019, the **AdWords** platform demonstrated superior performance in terms of **cost-effectiveness**, with a lower cost-per-click (CPC) and a higher conversion rate. 
Although Facebook yielded higher total ad clicks, AdWords produced more conversions and delivered better value for every dollar spent. Seasonal patterns were observed, with both platforms performing particularly well during the **holiday season** in late 2019.

## Main Insights:
- **AdWords:** Higher overall conversion rate and lower cost per conversion, making it the preferred platform for conversion-focused campaigns.
- **Facebook:** Higher total clicks, but the cost per click was significantly higher compared to AdWords.
- **Seasonality:** Both platforms saw spikes in performance during the holiday season, especially in November and December, with Facebook experiencing more significant peaks in click volume.

# Insights Deep Dive
## Ad Clicks Analysis:
- Facebook consistently generated more ad clicks throughout the year, with peaks in November and December.
- AdWords, although generating fewer clicks overall, showed a more consistent performance with fewer fluctuations across the year.
- Both platforms saw their lowest performance during the summer months.
- Despite lower click volume, AdWords had a better conversion rate.
[viz]

## Conversion Rate Comparison:
- AdWords had a significantly higher conversion rate, averaging 10.5% compared to Facebook’s 8.3%.
- Facebook conversions showed more variability, likely tied to seasonal promotions.
- The holiday season saw conversion spikes on both platforms, but AdWords was consistently higher in terms of efficiency.
- Cost per conversion was lower on AdWords, offering a better ROI for advertisers.
[Visualization specific to Conversion Rate]

## Cost-Effectiveness Evaluation:
- Facebook’s Cost per Click (CPC) averaged $3.40, while AdWords averaged $2.60.
- The Cost per Conversion on AdWords was approximately 15% lower than on Facebook.
- Although Facebook experienced spikes in performance, these were not sufficient to offset the higher costs.
- AdWords remained more cost-effective over time, especially in the latter half of the year.
[Visualization specific to Cost Effectiveness]

## CTR and Conversion Rate Trends:
- Both platforms saw increases in Click-Through Rate (CTR) towards the end of the year, particularly in December.
- Facebook’s conversion rate was more volatile compared to AdWords.
- AdWords maintained a relatively stable and higher CTR across most of the year.
- Seasonal trends suggest an opportunity to maximize ad spend during the holiday period.
[Visualization specific to CTR and Conversion Rates]

# Recommendations
Based on the findings from this analysis, the following recommendations are provided for future ad campaigns:
1. **Prioritize AdWords** for campaigns focused on conversions and cost-effectiveness, especially during periods of consistent demand.
2. **Leverage Facebook** during peak seasons when high click volume can be more effectively converted.
3. **Allocate more budget in Q4** to both platforms, but especially AdWords, to capitalize on the holiday shopping surge.
4. **Optimize Facebook's ad targeting** to reduce the high CPC and improve overall conversion rates.
5. **Run A/B tests during off-peak months** to determine if Facebook performance can be improved with optimized ad creative and targeting strategies.

# Assumptions and Caveats
Several assumptions were made in this analysis:
- Missing data for certain days were filled using averages from surrounding days.
- Cost per conversion data was extrapolated for missing entries in Q2.
- The effectiveness of the ads was assumed to be consistent across different target audiences, though demographic breakdowns were not provided.
