# A/B Testing for E-Commerce Webpage Conversion Enhancement

## Project Overview
Project Overview
In this project, I set out to explore whether a new webpage design could enhance the user experience and increase conversions in an e-commerce setting. The focus wasn't just on running an A/B test, but on understanding the user journey and identifying the impact of specific design changes on user behavior.  

<img width="1098" alt="Screen Shot 2024-08-24 at 12 02 04 PM" src="https://github.com/user-attachments/assets/a9942767-d163-4b93-8f68-a8c62fa4524c">

## Objective
The primary goal was to assess if the new webpage design—crafted to simplify navigation and highlight key actions—would lead to more users completing their desired actions, such as making a purchase. The A/B test served as a tool to uncover whether this design change would truly resonate with users, or if the existing design was already optimized for conversions.
Hypotheses:

Null Hypothesis (H0): The conversion rate of the old page is equal to or higher than the conversion rate of the new page. <br>
Alternative Hypothesis (H1): The conversion rate of the new page is higher than the conversion rate of the old page.

##Design Feature

The design feature at the center of this study was a redesigned call-to-action section, intended to make the next steps more obvious and appealing to users. This change aimed to streamline the user journey, reduce friction, and ultimately increase conversions by making it easier for users to complete their purchases.

##Problem Statement

The key question driving this project was: Would this specific design change improve user engagement and lead to a higher rate of conversions? By running an A/B test, I aimed to gather insights that could either confirm the new design’s effectiveness or suggest that further refinements were needed.



## Dataset
The project utilized a dataset containing over 290,000 user sessions, including information on which version of the webpage the user was exposed to (`old_page` or `new_page`), and whether the user converted (completed a desired action, such as making a purchase).

### Key Columns:
- **id**: Unique identifier for each user session.
- **page_version**: Indicates whether the user saw the `old_page` or `new_page`.
- **converted**: Binary variable indicating whether the user converted (1 for conversion, 0 for no conversion).

## Approach
To answer this question, I compared user behavior on two versions of the webpage: the existing design and the newly proposed design. The A/B test allowed me to observe real user interactions with both designs, providing a direct comparison of their effectiveness.

## What I Achieved
Through this project, I gained valuable insights into how users interact with different webpage designs. The analysis helped me understand the strengths and weaknesses of the new design and whether it had the potential to replace the existing version.

## What’s Next?
While the initial analysis provided important insights, there are several areas that warrant further exploration:

- User Behavior Analysis: To gain a deeper understanding of why users might prefer one design over another, I would analyze more granular data on user interactions, such as click paths, time spent on each section, and user feedback.

- Segmentation: Future analysis could focus on different user segments, such as first-time visitors versus returning customers, or mobile users versus desktop users, to see if the design change impacts these groups differently.

Additional Data Sources: Incorporating data from user surveys, heatmaps, and session recordings could provide richer insights into user preferences and pain points. This would help in refining the design further or identifying other areas of the webpage that could benefit from similar optimizations

## Conclusion
Based on the results of the A/B test, I concluded that there is not enough evidence to support a significant improvement in conversion rates with the new webpage design. Therefore, I recommended maintaining the existing design while considering further tests or alternative strategies to optimize conversion rates.

## Future Work
While the current A/B test did not yield a statistically significant result, there are several potential avenues for future exploration:
- **Further A/B Testing**: Explore other design elements, such as call-to-action buttons or page layout, to identify potential improvements.
- **User Behavior Analysis**: Conduct in-depth analysis of user behavior to identify specific pain points or areas for optimization.
- **Segmented Testing**: Perform A/B tests on specific user segments (e.g., based on geography or device type) to see if the new design performs better in certain contexts.


