# Data Analysis on Baobab Platform Responses

This repository contains the analysis of responses from the Baobab Platform, focusing on user behavior, opportunity applications, and demographic data. Various bivariate and multivariate analyses were performed to identify trends and insights, which can be used to improve user experience and platform engagement.

## Table of Contents

- [Overview](#overview)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Univariate Analysis](#univariate-analysis)
- [Bivariate and Multivariate Analysis](#bivariate-and-multivariate-analysis)
- [Visualizations](#visualizations)
- [Setup and Requirements](#setup-and-requirements)
- [License](#license)

## Overview

The analysis focuses on understanding:
- User demographics (e.g., gender, country of residence, education level).
- User interactions with the platform (e.g., opportunities applied to, frequency of visits, stage in application process).
- The success rate of opportunities (e.g., accepted offers).

The dataset includes responses from various users of the Baobab platform, a community platform for young African leaders and participants of Mastercard Foundation programs.

## Data Cleaning

Before performing analysis, the dataset was cleaned by:
- Handling missing or incomplete values.
- Converting categorical variables into suitable formats for analysis (e.g., encoding labels for gender and opportunity types).
- Removing duplicates and ensuring data consistency.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was performed to gain a better understanding of the dataset, identifying key trends and patterns. This included:
- Summarizing the distribution of responses for key demographic variables.
- Analyzing the relationships between different features of the data (e.g., gender vs. opportunities accessed, country of residence vs. application stages).

## Univariate Analysis

Univariate analysis was performed to explore individual variables and their distributions:
- **Gender Distribution**: Analyzed the proportion of male vs female respondents.
- **Country of Residence Distribution**: Examined the spread of users from different countries.
- **Education Level Distribution**: Investigated the education levels of users.
- **Opportunities Accessed Distribution**: Summarized how many opportunities users have accessed.

Univariate plots were created for these variables, including bar charts and histograms to better understand individual feature distributions.

## Bivariate and Multivariate Analysis

### Bivariate Analysis
We explored relationships between pairs of variables:
- **Gender vs. Opportunities Accessed**: Examining how gender influences the number of opportunities accessed.
- **Country of Residence vs. Number of Opportunities Accessed**: Identifying trends in opportunity access based on users' countries of residence.

### Multivariate Analysis
We performed more complex analyses involving multiple variables:
- **Education Level vs. Opportunities Accessed vs. Gender**: Understanding how education level influences opportunities accessed, broken down by gender.
- **Affiliation vs. Types of Opportunities Applied to vs. Success Rate**: Analyzing how affiliations and opportunity types correlate with the success rate (accepted offers).

## Visualizations

### Key Visualizations
The following plots were created to visualize the relationships in the data:
- **Grouped Bar Chart**: Gender vs. Opportunities Accessed.
- **Stacked Bar Chart**: Country of Residence vs. Opportunities Accessed vs. Gender.
- **Bar Chart**: Education Level vs. Resources of Interest vs. Gender.
- **Stacked Bar Chart**: Opportunities vs. Country of Residence vs. Gender.
- **Stacked Bar Chart**: Affiliation vs Types of Opportunities Applied to vs. Success Rate.
  
These plots help to identify trends and correlations that may be useful for improving user engagement on the platform.

## Setup and Requirements

To run this analysis, you'll need the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn

