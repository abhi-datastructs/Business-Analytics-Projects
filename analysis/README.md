This folder contains A/B testing analysis files, calculations, and results.

# Experiment Overview

This project analyzes an A/B test conducted to evaluate the effectiveness of advertisements on user conversion.

# Objective
Evaluate whether showing ads leads to a higher conversion rate compared to a Public Service Announcement (PSA) using real marketing data.

# Test Groups
- **Control Group (psa):** Users shown a public service announcement
- **Test Group (ad):** Users shown advertisements

# Primary Metric
- **Conversion Rate:** Number of converted users divided by total users in each group

# Hypothesis
- **Null Hypothesis (H₀):** There is no difference in conversion rates between the ad and psa groups
- **Alternative Hypothesis (H₁):** The ad group has a higher conversion rate than the psa group

________________________________________________________________________________________________________________________________________________

# Marketing A/B Testing Analysis

## Dataset
- Located in the `data/` folder  
- Two groups:
  - Ad group
  - PSA group  
- Total users analyzed: **588,101**

## Tools Used
- Microsoft Excel  
- Tableau
- Pivot Tables  
- Z-test for two proportions  

## Analysis Steps
1. Aggregated users and conversions using pivot tables  
2. Calculated conversion rates for both groups  
3. Performed a two-proportion Z-test  
4. Evaluated statistical significance using p-value  

## Results

| Group | Users | Conversions | Conversion Rate |
|------|-------|-------------|-----------------|
| Ad   | 564,577 | 14,423 | 2.55% |
| PSA  | 23,524 | 420 | 1.79% |

- **Z-score:** 7.37  
- **p-value:** 8.53e-14  

## Visualization
The chart below compares conversion rates between the Ad and PSA groups.

![Conversion Rate Comparison](visuals/Conversion Rate by Campaign.png)

## Conclusion
The Ad campaign performs significantly better than the PSA campaign.  
The difference in conversion rates is statistically significant at the 95% confidence level.
