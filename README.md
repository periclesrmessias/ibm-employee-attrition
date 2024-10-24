# IBM HR Analytics Employee Attrition Report

## Introduction

This report presents an analysis of employee attrition using a fictitious dataset from International Business Machines Corp (IBM), demonstrating the work of a data analyst. It primarily focuses on the analytical process and decision-making strategies utilized throughout the analysis, providing insights valuable to my learning and career development. 
Methodology
The decision to analyze this data was made after seeing a YouTube video from Andre Yukio, in which he talks about the job of a data analyst. This analysis first started being done blindly (without actually watching the analysis process in the video), in order to see if my decision-making process aligns with Yukio’s who is a well-known data scientist in Brazil. 
Project Timeline, Tools and Goals
May 27, 2024: Project initiation, data downloaded from Kaggle, tools used were Excel and ChatGPT.

Began analyzing the data with the goal to:
-	Learn the analysis process and put into perspective how it actually works.
-	Track progress throughout the project and see how decision-making evolves.
-	Compare the process to a professional analysis.
Note: This dataset is entirely fictional and publicly accessible, facilitating its collaboration with ChatGPT. It's imperative to emphasize that if the dataset were not publicly available, its use would be ethically prohibited.

## Analysis and Key Findings
### 1. Demographic and Job-Related Variables
#### Age, department and commute distance
Finding: Employees in their late 20s to mid-30s (45%) from the Sales department (20%) are more likely to leave. One interesting finding was that 45% of the employees actually lived on average closer than 4 miles to the job, which is unusual and would require further investigation.
Actionable Insight: Consider targeting retention strategies for Sales employees in this age group and commuting distance.


#### Education Field
Finding: Attrition rates are higher in employees with a bachelor’s degree (43%).
Actionable Insight: Implement career development programs based on educational background to enhance retention.
Environment Satisfaction
Finding: 30% of the employees who left the company were not satisfied with the environment, but most of them (52%) were satisfied or very satisfied with the environment.
Actionable Insight: Conduct surveys to better understand and improve workplace environment satisfaction.

### 2. Gender and Compensation
#### Gender Attrition
Finding: 17% attrition rate among men, with men constituting 60% of the workforce.
Actionable Insight: Investigate specific factors affecting gender-based attrition and address any disparities.
Hourly Rates
Finding: Minimal difference in average hourly rates between genders.
Actionable Insight: Ensure ongoing pay equity audits to maintain fairness.
Despite a slight disparity in the proportion of male to female employees, hourly rates exhibit minimal gender-based variance, with women averaging US$65.9 and men US$65.8. Notably, both genders hold a comparable share of the highest-paying positions, with a near-even distribution of 46 women to 69 men. In this topic I made a calculation error that initially skewed the gender ratio and took me a lot of time, highlighting the importance of diligent analysis and the attention to human error.

### 3. Job Role and Satisfaction
#### Job Involvement and Level
Finding: Most employees have moderate job involvement and are at the lowest job levels.
Actionable Insight: Enhance engagement initiatives and provide clear career progression paths.
#### Job Satisfaction
Finding: Significant proportion of employees were unsatisfied.
Actionable Insight: Implement regular feedback mechanisms and address key areas of dissatisfaction.


### 4. Additional Variables
#### Marital Status
Finding: 50% are single, 34% married, 14% divorced.
Actionable Insight: Consider family-friendly policies to support married and divorced employees.
Monthly Income and Rate
Finding: Wide income range with a concentration in the $2000-$3000 range.
Actionable Insight: Review compensation packages to ensure competitive salaries.
#### Overtime
Finding: Nearly equal split, 52% did overtime 48% did not, between employees working overtime and those who do not.
Actionable Insight: Monitor overtime patterns to prevent burnout.
#### Performance Rating
Finding: Majority (86%) received excellent performance ratings.
Actionable Insight: Provide performance improvement plans and recognition programs.

### 5. Correlations and Insights
#### Promotion and Tenure
Finding: Moderate correlation 0.69 between lack of promotion and attrition. This moderate to high correlation between years at the company and years without a promotion among departing employees, potentially contributed to employee attrition. Whereas the correlation level between years at the company and years without a promotion within employee’s that still work at the company is lower at 0.54.
Actionable Insight: Develop transparent promotion criteria and frequent opportunities for career advancement.

## Recommendations for Future Analysis

After watching the video and taking a look at the project, a few realizations emerged: 
1.	Lack of Specific Variables: lack of variables or a specific criterion to analyze the data lead to a broad and time-consuming analysis. Establishing specific questions or business problems to solve before beginning the analysis is a good strategy. 
2.	Utilizing Excel Tools: Using pivot tables to relate variables, automated calculations and data analysis tools to streamline data processing.
3.	Accurate Visualizations: One thing to keep in mind seen in Yukio’s video is remembering to be mindful when making graphics of pivot tables and also when selecting values for these graphics. Graphics can be misleading making smaller differences appear larger, like in this case:
<br>
<div align="center">
  
  <img src="https://github.com/periclesrmessias/ibm-employee-attrition/blob/main/images/avg-distance-home-y-axis.png" alt=" " />

</div>
<br>
If you only look at the difference between the employees who left the company and the ones who didn’t, on the X-axis, it may seem that employees who left the company lived almost three times farther away than those who stayed. However, if you examine the Y-axis, you see the difference is only from 8 miles to 11 miles. Here’s the correct graphic:

<br>
<br>
<div align="center">
  
  <img src="https://github.com/periclesrmessias/ibm-employee-attrition/blob/main/images/avg-distance-home.png" alt=" " />

</div>
<br>
Understanding these nuances is essential to provide accurate information to project stakeholders and avoid misconceptions.

## Conclusion
This report provides a comprehensive overview of employee attrition analysis, highlighting the importance of a structured approach to data analysis. This experience has given me valuable insights into the analytical process and decision-making strategies necessary for effective data analysis It also emphasized the need to focus on clear objectives, accurate visualizations, and a thorough exploration of correlations to drive meaningful outcomes. Future projects should build on these practices to achieve even more precise and impactful results.

## References
[Kaggle Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

[Andre Yukio Youtube Video](https://www.youtube.com/watch?v=i_evacoZcPY)
