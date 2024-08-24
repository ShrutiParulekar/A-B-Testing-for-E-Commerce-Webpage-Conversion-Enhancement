# A/B Testing for E-Commerce Webpage Conversion Enhancement

## Project Overview
This project focuses on the application of A/B testing to evaluate the impact of a new webpage design on conversion rates in an e-commerce environment. By comparing user interactions on two different versions of a webpage (the existing design and a new proposed design), I aimed to determine whether the new design would lead to a statistically significant improvement in conversion rates.

<img width="1098" alt="Screen Shot 2024-08-24 at 12 02 04 PM" src="https://github.com/user-attachments/assets/a9942767-d163-4b93-8f68-a8c62fa4524c">

## Objective
The primary goal of this project was to use data-driven techniques to assess whether the new webpage design could enhance user conversions compared to the existing design. The A/B test was designed to provide insights that would inform a decision on whether to implement the new design, keep the current one, or explore further optimization opportunities.

## Design of the experiment
Objective: The objective of the experiment is to determine whether the new web page leads to a higher conversion rate compared to the old page for an e-commerce website.

Hypotheses:

Null Hypothesis (H0): The conversion rate of the old page is equal to or higher than the conversion rate of the new page. <br>
Alternative Hypothesis (H1): The conversion rate of the new page is higher than the conversion rate of the old page.

## Dataset
The project utilized a dataset containing over 290,000 user sessions, including information on which version of the webpage the user was exposed to (`old_page` or `new_page`), and whether the user converted (completed a desired action, such as making a purchase).

### Key Columns:
- **id**: Unique identifier for each user session.
- **page_version**: Indicates whether the user saw the `old_page` or `new_page`.
- **converted**: Binary variable indicating whether the user converted (1 for conversion, 0 for no conversion).

## Methodology

### Data Preparation:
- Merged and cleaned datasets to ensure consistency.
- Filtered data to remove any inconsistencies, ensuring that users in the control group only saw the old page and users in the treatment group only saw the new page.

### Statistical Analysis:
- Calculated conversion rates for both the control (`old_page`) and treatment (`new_page`) groups.
- Performed a Z-test to compare the conversion rates between the two groups.

### Key Metrics:
- **Z-Score**: 1.37
- **P-Value**: 0.17
- **Conversion Rate Difference**: 0.2%

## Results
The Z-score of 1.37 and a P-value of 0.17 indicated that the observed difference in conversion rates between the control and treatment groups was not statistically significant at the 95% confidence level. The slight increase in conversion rate for the new page (0.2%) did not provide enough evidence to justify implementing the new design.

## Conclusion
Based on the results of the A/B test, I concluded that there is not enough evidence to support a significant improvement in conversion rates with the new webpage design. Therefore, I recommended maintaining the existing design while considering further tests or alternative strategies to optimize conversion rates.

## Future Work
While the current A/B test did not yield a statistically significant result, there are several potential avenues for future exploration:
- **Further A/B Testing**: Explore other design elements, such as call-to-action buttons or page layout, to identify potential improvements.
- **User Behavior Analysis**: Conduct in-depth analysis of user behavior to identify specific pain points or areas for optimization.
- **Segmented Testing**: Perform A/B tests on specific user segments (e.g., based on geography or device type) to see if the new design performs better in certain contexts.


