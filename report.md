# Euphoria User Engagement Analysis Report

**Author:** Vuyo Mkhatshwa  
**Date:** Mar/11/2025

---

## Introduction

This report analyzes user data for OmniCo's three algorithms; JoyStream, SerenityFlow, and DeepPulse. The objective is to understand user behavior and satisfaction across these algorithms, providing insights for future development and optimization. By evaluating average happiness ratings and session durations, we aim to identify the most effective algorithms and areas for improvement for each.
4

## Methodology

The analysis involved processing data from a CSV file ("euphoria_data.csv"). The code first initialized a dictionary to store statistics for each algorithm, including total happiness ratings, total session durations, and session counts. It then read the CSV file, parsed each line, and summed the data. The Average happiness and session duration were also calculated for each algorithm by dividing using the number of session run in each algorithm (session_counts). Finally, the algorithms with the highest average happiness and longest average session duration were identified.

## Results

- **Average Happiness Rating per Algorithm**

  - JoyStream: 8.50
  - SerenityFlow: 7.00
  - DeepPulse: 5.00

- **Total Number of Sessions per Algorithm**

  - JoyStream: 4
  - SerenityFlow: 3
  - DeepPulse: 3

- **Average Session Duration per Algorithm**

  - JoyStream: 37.50 minutes
  - SerenityFlow: 30.00 minutes
  - DeepPulse: 45.00 minutes

- **Highest and Lowest Performers**
  - Highest Average Happiness Rating: 8.50
  - Longest Average Session Duration: 45.00 minutes

## Observations and Insights

Typically we would expect to see the algorithm with the highest happiness rating be correlated with longer session duration which we can see with the JoyStream and SerenityFlow algorithms respectively, however we also observe an anomaly, specifically with the DeepPulse algorithm. Despite having the lowest average happiness rating, the DeepPulse algorithm produced the longest average session duration, which was unexpected.

## Conclusions and Recommendations

In conclusion, JoyStream appears as the most successful algorithm based on user happiness, while SerenityFlow shows moderate performance in both happiness and session duration. DeepPulse, while having the lowest average happiness, has the longest average session duration, which is cause for further exploration. looking at session counts for each algorithm, there were too few observations and data in the euphoria data file to be able to achieve any statistically significant results, hence I would suggest collecting more data as a future recommendation. This could also help with my next recommendation, of exploring whether the anomal result found with the DeepPulse algorithm was an outlier or if another variable is in play manipulating the result.

---

_This report contains confidential information proprietary to OmniCo. Unauthorized use or disclosure is strictly prohibited._
