# Analyze A/B Test Results

A/B Tests are very commonly performed by data analysts to interpret and examine given datasets. From this Udacity Data Analysis project, we are trying to analyze datasets from an e-commerce new web page A/B test results. Our goal is to help the company understand if they should implement new web page, keep the old page, or perhaps run the experiment longer to make their decision.

## Requirements

Software: Python 3 
Packages: Pandas, Numpy, Matplotlib, StatsModels, Scipy
Raw Data: _ab\_data.csv_ (`df`), _countires.csv_ (`countries_df`)

## Project Scope

Part 1: Probability: By comupting the probabilities for converting rate regardless of page, we will be able to analyze if one page or the other led to more conversions.

      - All users
      - Only the treatment group.
      - Only the control group.

Part 2: A/B Test: Hypothesis testing is conducted by assuming old page is better unless the new page proves to be definitely better at a Type I error rate of 5%.

      - Boothstraping and sampling distribution for both pages. 
      - Comparison of p-value.
      - Validation/Double-check results to decide whether to reject the null hypothesis

Part 3: Regression: Logistic regression is performed 

      - Logistic regression is performed to confirm the results.
      - By further adding country variable, we attempt to see whether country has impact on conversion.

Part 4: Conclusion: Summarize and conclude the findings and provide company with insights obtained from the combination of A/B testing and statistical analysis. 
