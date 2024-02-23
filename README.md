# Synthetic RTT Data Analysis

This project aims to analyze a synthetic Referral to Treatment (RTT) dataset to identify any inequalities in the wait times for patients to be seen by a clinician. The analysis covers various aspects, including patient demographics, the index of multiple deprivation, and ethnicity, to ascertain their impact on the wait times from referral to treatment.

## Dataset Description

The dataset mimics real-world RTT data, focusing on several key attributes:

- Patient Age
- Index of Multiple Deprivation (IMD)
- Patient Ethnicity
- Date Seen by Healthcare Professional
- Referral Date

## Analysis

The primary task is to explore potential inequalities in patient wait times using the provided dataset. This involves:

- Loading and preprocessing the dataset
- Conducting exploratory data analysis to understand the data structure and distribution
- Creating additional metrics, such as 'Wait Time'
- Visualizing data to identify outliers and distribution characteristics
- Performing statistical tests to analyze the impact of different variables on wait times

### Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- SciPy and Pingouin for statistical analysis
- Scikit-posthocs for post-hoc analysis
