# Marketing A/B Testing Analysis (Excel)

## Project Objective
Evaluate whether showing ads leads to a higher conversion rate compared to a Public Service Announcement (PSA) using real marketing data.

-----------------------------------------------------------------------------------------------

## Dataset
- Uploaded under the `Data/` folder
- Two groups:
  - **Ad group**
  - **PSA group**
- Total users analyzed: 588,101

-----------------------------------------------------------------------------------------------

## Tools Used
- Microsoft Excel
- Pivot Tables
- Z-test for two proportions

-----------------------------------------------------------------------------------------------

## Analysis Steps
1. Aggregated users and conversions using pivot tables
2. Calculated conversion rates for both groups
3. Performed a two-proportion Z-test
4. Evaluated statistical significance using p-value

-----------------------------------------------------------------------------------------------

## Results

| Group | Users | Conversions | Conversion Rate |
|-----|------|------------|----------------|
| Ad | 564,577 | 14,423 | 2.55% |
| PSA | 23,524 | 420 | 1.79% |

- **Z-score:** 7.37  
- **p-value:** 8.53e-14  

-----------------------------------------------------------------------------------------------

### Visualization
The chart below was created using Tableau to compare conversion rates between the Ad and PSA groups.

-----------------------------------------------------------------------------------------------

## Conclusion
The Ad campaign performs **significantly better** than the PSA campaign.
The difference in conversion rates is statistically significant at the 95% confidence level.

-----------------------------------------------------------------------------------------------

## Files in this Repository
- `Data/` → Raw dataset
- `ab_testing_analysis_excel.xlsx` → Excel analysis & calculations
