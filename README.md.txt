Workforce Salary Structure Analysis
Author

Elijah Maingi Kioko

Project Overview

This project analyzes the relationship between employee experience and salary structure within an organization. The objective is to determine whether salary progression is aligned with experience level and whether observed differences are statistically significant.

The analysis combines data visualization, correlation analysis, hypothesis testing, ANOVA, and regression modeling.

Objectives

Examine workforce distribution across experience levels

Analyze salary distribution patterns

Measure the strength of the relationship between experience and salary

Test whether salary differences between groups are statistically significant

Evaluate overall compensation structure using ANOVA

Model salary progression using linear regression

Methods Used

Descriptive Statistics

Data Visualization using ggplot2

Pearson Correlation

Welch Two-Sample t-test

One-Way ANOVA

Tukey Post-hoc Test

Linear Regression Model

Key Findings
1. Workforce Structure

The workforce includes three experience levels: Junior, Mid, and Senior employees. The distribution shows representation across all levels.

2. Salary Distribution

Salary levels are generally balanced, with higher salary concentrations among senior employees.

3. Experience vs Salary Relationship

A strong positive linear relationship exists between years of experience and salary.

Correlation coefficient (r ≈ 0.97) indicates a very strong positive association.

4. Junior vs Senior (t-test)

A Welch two-sample t-test revealed a statistically significant difference in mean salaries between junior and senior employees.

Seniors earn significantly more than juniors

p-value < 0.001

5. ANOVA Results

One-way ANOVA showed a significant difference in mean salary across experience levels.

F-statistic significant at 5% level

p-value < 0.001

6. Post-hoc Analysis (Tukey Test)

Senior vs Junior → Significant

Senior vs Mid → Significant

Mid vs Junior → Not significant at 5% level

This suggests that salary differentiation becomes clearly pronounced at the senior level.

7. Regression Model

A linear regression model confirmed that salary increases significantly with years of experience.

The model supports structured and progressive salary growth.

Conclusion

The analysis demonstrates a strong and statistically significant relationship between experience and salary. Senior employees earn substantially more than junior and mid-level employees, confirming a structured compensation progression system.

While differences between junior and mid-level employees are not statistically significant at the 5% level, overall evidence supports an experience-based salary framework.

Tools & Technologies

R Programming

ggplot2

Statistical Inference Techniques