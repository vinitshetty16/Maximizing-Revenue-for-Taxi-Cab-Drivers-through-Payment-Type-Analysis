# Maximizing Revenue for Taxi Cab Drivers through Payment Type Analysis

<img src="https://cdn.vox-cdn.com/thumbor/Ge0nFOIuQMfhEtKyM8YNIL2hCjQ=/0x0:4752x3168/920x613/filters:focal(1996x1204:2756x1964):format(webp)/cdn.vox-cdn.com/uploads/chorus_image/image/55123497/4859177053_c3fb190917_o.0.jpg" alt="Description of the Image" style="width: 100%; height: 50%; object-fit: cover;" />



## Problem Statement
In the fast-paced taxi booking sector, making the most of revenue is essential for long-term success and driver happiness. Our goal is to use data-driven insights to maximise revenue streams for taxi drivers in order to meet this need. Our research aims to determine whether payment methods have an impact on fare pricing by focusing on the relationship between payment type and fare amount

## Objective
This project's main goal is to run an A/B test to examine the relationship between the total fare and the method of payment. We use Python hypothesis testing and descriptive statistics to extract useful information that can help tail drivers generate more cash, in particular, we want to find out if there is a big difference in the fares for those who pay with credit cards versus those who pay with cash

## Research Question
Is there a relationship between total fare amount and payment type and can we nudge customers towards payment methods that generate higher revenue for drivers without negatively impacting customer experience?

**Dataset source:** https://data.world/vizwiz/nyc-taxi-jan-2020/workspace/file?filename=yellow_tripdata_2020-01.csv

## Results

### 1. Hypothesis Testing

The two-tailed t-test results comparing fare amounts between payment types are as follows:

- **T-statistic:** `169.209`
- **P-value:** `0.00`

Based on the p-value, we can determine whether there is a statistically significant difference in fare amounts between credit card payments and cash payments.


## Conclusion

The analysis of the data has provided the following insights:

- **Statistical Significance:** The p-value from the two-tailed t-test indicates whether there is a significant difference in fare amounts between credit card and cash payments.
- **Fare Distribution:** The histograms and boxplots reveal the distribution patterns and potential outliers in fare amounts for different payment types.

Overall, the findings suggest that there is a significant difference in fare amounts between credit card and cash payments, with one method potentially yielding higher fares than the other.

## Recommendations

Based on the analysis, the following recommendations are proposed to optimize revenue for taxi drivers:

1. **Encourage Preferred Payment Method:** If the analysis indicates that one payment method results in higher fare amounts, drivers should consider encouraging customers to use that method.
2. **Customer Communication:** Implement strategies to inform customers about the benefits of using the preferred payment method, such as convenience or added incentives.
3. **Further Analysis:** Conduct additional analyses on other factors that might influence fare amounts, such as trip duration, distance, or time of day, to gain a more comprehensive understanding of revenue optimization strategies.

Feel free to adjust any sections as needed for your specific project details or preferences!
