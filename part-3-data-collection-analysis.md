# Part 3: Data Collection and Analysis

This is where your plan comes to life. A well-organized process is key to getting high-quality data. For a practical field guide on online survey research [here](https://drive.google.com/file/d/19q75tjplzmiTPv1flYbRzs-0XVnsljtN/view?usp=share_link).

## 3.1 Plan and Pilot Your Data Collection

* Who, Where, How: Decide who will collect the data (and train them well to avoid interviewer bias), where it will happen (clinic, online), and how (interviews, self-administered forms).
*   **Pilot Study**: Administer the refined questionnaire to a larger sample (e.g., 10-30 individuals) under actual field conditions. This allows for a final check of procedures, and required resources for ascertainment of recruitment rate. This helps you catch glitches before they become major problems.

    #### Data Collection
* **Enumerator Training**: Train data collectors thoroughly to ensure they understand the questions, follow the protocol, and administer the survey in a standardized, neutral manner to minimize interviewer bias.
* **Participant Recruitment and Consent (for physical and face-to-face)**: Approach eligible individuals, explain the study, and obtain informed consent.
* **Data Administration**: This can be interviewer-administered (good for populations with low literacy) or self-administered (reduces social desirability bias for sensitive topics).
* **Quality Control**: The researcher or the principal investigator as the field supervisor should perform spot-checks and review completed forms daily for completeness and consistency.

## 3.2 Create a Data Analysis Plan

For a real published example [HERE](https://drive.google.com/file/d/1BvTn5cu9v4rIhfUJDMee8gjc4Z6wyH7v/view?usp=share_link). Decide before you collect data how you will analyse it. This prevents bias and ensures you use the right statistical tests. This plan prevents p-hacking and data-dredging. It should detail: • The software to be used (e.g., SPSS, Stata, R). • How variables will be coded and scored (e.g., how to define "good knowledge" vs. "poor knowledge" from a series of questions). • The specific statistical tests that will be used to address each research objective.

### Your Plan Should Include:

1. **Descriptive Statistics**: To summarize your sample's characteristics (e.g., means, percentages) and your main outcomes (e.g., prevalence with 95% confidence intervals). Data quality and distribution to use the right parametric or non-parametric tests.
2. **Outliers and Missing Data**: A plan for how to handle it.
3. **Bivariate Analysis**: To explore initial associations between two variables.
   * Chi-square test: For two categorical variables (e.g., education level and vaccination status).
   * t-test/ANOVA: To compare average scores between groups (e.g., mean knowledge score by gender).
4. **Multivariable Analysis**: To identify predictors of an outcome while controlling for other factors. Include model diagnostics (see further elaboration).
   * Logistic Regression: For binary outcomes (e.g., good vs. poor practice).
   * Linear Regression: For continuous outcomes (e.g., predicting a quality-of-life score).

## 3.3 Data Analysis, Statistical Assumptions and Model Diagnostics

Statistical analysis is essential for producing valid and precise research results. To achieve this, you must understand your data's characteristics and ensure that the underlying assumptions of your statistical models are met. This guide will walk you through describing your data before moving to the key assumptions and diagnostic checks for multiple logistic and linear regression, which are foundational pillars for ensuring the reliability and interpretability of your findings. For elaboration of the following [HERE](https://drive.google.com/file/d/1HkkE10fEqBEMVdSAZo1naFm1jABaBOGz/view?usp=share_link).

1. **Descriptive Statistics**: The First Look. This is the initial, essential step to characterize your data before modelling.

* Core Measures: Assess central tendency (mean, median), spread (standard deviation), and distribution.
* _Normality Checks_:
  * Visualize: Use histograms and Q-Q plots.
  * Coefficients: Check that skewness and kurtosis values are between -1 and +1.
  * Formal Tests: Use Shapiro-Wilk or Kolmogorov-Smirnov with caution, as they are sensitive to sample size.
  * _Outlier Detection_: Identify outliers using boxplots, where points beyond 1.5 times the IQR are flagged.

2. **Multiple Logistic Regression**: For Binary Outcomes This model is used for outcomes with two categories (e.g., yes/no).

* Key Assumptions:
  * Linearity of Logit: The relationship between continuous predictors and the log-odds of the outcome is linear.
  * Independence: Observations are not clustered or repeated.
  * No Multicollinearity: Check that the VIF is less than 2.5.
  * Adequate Sample Size: Ensure at least 10-20 events per variable (EPV) to prevent overfitting.
  * _Diagnostics_:
    * Model Fit: Assess calibration (accuracy of predictions) and discrimination (ability to distinguish between outcomes).
    * Outliers: Investigate standardised Pearson residuals greater than 2.0.

3. **Multiple Linear Regression**: For Continuous Outcomes This model is used for continuous outcome variables.

* Key Assumptions:
  * Linearity, Normality & Homoscedasticity: Check these by plotting residuals versus predicted values. The plot should be random, with no clear pattern or fanning shape.
  * Independence: The Durbin-Watson statistic should be around 2.
  * No Multicollinearity: VIF should be less than 2.5.
  * Sufficient Sample Size: A common guideline is 20 subjects per variable.
  * **Influential Outliers**:
    * Check standardised residuals (values > 3 are extreme).
    * Assess Cook's Distance (values > 1 or > 4/n are influential).

## 3.4 Planning for Success:

Measures to Take Before You Analyse Proactive planning is key to mitigating statistical issues and enhancing the credibility of your research.

* **A Priori Power Analysis**: Before the study begins, conduct a power analysis to determine the necessary sample size to detect a clinically meaningful effect.
* Develop a **Detailed Research Protocol**: A pre-specified protocol is essential and should outline research questions, hypotheses, outcomes, and the statistical analysis plan. This helps prevent bias.
* **Careful Variable Selection**: Prioritize including variables based on clinical relevance, biological plausibility, and existing literature, not solely on statistical significance.
* Plan for **Data Quality**: Design robust data collection methods to minimize missing data. Pre-plan how missing data will be handled, for instance, by using multiple imputation.
* Emphasize **Transparency in Reporting**: Clearly articulate the theoretical basis and assumptions of your model. Always report how missing data were handled. Use confidence intervals in preference to P-values.
* **Collaborate with Statisticians**: Engage a biostatistician from the very beginning of your study design and maintain collaboration throughout the entire process.
