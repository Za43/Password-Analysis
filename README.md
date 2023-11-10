# Password-Analysis

## Title: How Do Password Characteristics Affect Password Strength?

### Authors: Zaid Muqsit and Zoe Spicer

---

This report, presented at USCLAP 2023, delves into the critical realm of data security by examining the impact of various password characteristics on their strength. It features an algorithm-based strength measure and analyzes the time required for a brute force attack to crack passwords.

### Overview

Drawing on a dataset from Tidy Tuesday and Information is Beautiful, which includes the 500 most popular passwords from 20 data breaches in 2017, we scrutinize password length, digits, letters, and unique characters. Through exploratory data analysis and regression models, the study highlights the relationship between password complexity and security.

### Findings and Conclusions

Our research underscores that a higher count of unique characters correlates with stronger passwords. Additionally, lengthier passwords offer increased resistance to brute force attacks, thus reinforcing their significance in safeguarding online data. Despite the insights, the dataset's focus on common passwords from data breaches may limit the generalizability of our results. Further inquiries could expand on diverse password samples and consider emerging AI-powered hacking methodologies.

### Repository Contents and Instructions

- `Exploratory_Data_Analysis/`: Visualization and summary statistics scripts.
- `Models/`: Code for regression analyses that underpin the study's conclusions.
- `Discussion/`: In-depth discussions on the implications of our findings and suggestions for future research avenues.

### Technical Requirements

- **Programming Languages**: R
- **Key Libraries**: tidyverse, lme4, ggplot2 for R

### Setup

Clone the repository and install the necessary R libraries to replicate the analyses and explore the password dataset in depth.

### Reference Links

- Alkhatib, B. (2023). Keeper Security Blog.
- Specops. (2023). BleepingComputer.
- Tidy Tuesday GitHub Repository: [Password Data](https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-01-14).

The full report should be consulted for an in-depth analysis and comprehensive understanding of the study's methods and implications.
