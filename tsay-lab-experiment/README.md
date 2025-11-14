# UX Experiment – IMDb Judgment Study (Tsay Lab)

## Overview
This project investigates how people evaluate media quality when exposed to partial or biased information. The study combines data collected from IMDb/OMDb APIs and an online behavioral experiment (N ≈ 120). I independently handled data cleaning, experimental materials, and statistical modeling in R.

## Research Questions
- How do people judge the “quality” of movies when provided with incomplete metadata?
- Which factors (ratings, genre, popularity) influence perceived credibility?
- Do participants infer patterns or “rules” even when metadata is absent?

## Methods
- **Data sources:** IMDb + OMDb API JSON  
- **Experiment platform:** Qualtrics survey (randomized conditions)  
- **Design:** Between-subjects, randomized assignment to metadata conditions  
- **Measures:** Perceived quality, confidence rating, viewing likelihood  
- **Tools:** R (tidyverse), ggplot2, statsmodels, correlation tests  

## Analysis
- Cleaned noisy API fields and normalized ratings  
- Ran Pearson/Spearman correlations  
- Performed regression models predicting judgments from metadata  
- Visualized distributions and interaction effects  
- Conducted exploratory factor analysis on perception items  

## Key Findings
- Users rely heavily on rating metrics even when warned about incompleteness  
- Genre stereotypes significantly affect perceived quality  
- Confidence does **not** track accuracy—participants overgeneralize missing cues  
- Regression model explains **42%** of variance in perceived quality ratings  

## Impact
This study demonstrates how users make decisions under uncertainty—insightful for:
- UX information architecture  
- Recommendation systems  
- Content ranking interfaces  
