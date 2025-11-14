# UX Experiment – IMDb Judgment Study (Tsay Lab)

## Overview
This project investigates how people evaluate media quality when exposed to partial or biased information. The study combines IMDb/OMDb API metadata with an online behavioral experiment (N ≈ 120). I independently handled experiment design, data cleaning, and statistical modeling in R.

## Research Questions
- How do people judge the “quality” of movies when provided with incomplete metadata?
- Which factors (ratings, genre, popularity) influence perceived credibility?
- Do participants infer patterns or “rules” even when metadata is absent?

## Methods
- **Data sources:** IMDb + OMDb API JSON  
- **Experiment platform:** Qualtrics survey (between-subjects randomization)  
- **Measures:** Perceived quality, confidence rating, viewing likelihood  
- **Tools:** R (tidyverse), ggplot2, statsmodels, correlation tests  

## 📊 Research Workflow

```mermaid
flowchart TD
    A[IMDb / OMDb API<br>Raw JSON Data] --> B[Data Cleaning & Normalization<br>(R: tidyverse)]
    B --> C[Qualtrics Experiment Design<br>Randomized Conditions]
    C --> D[Participant Responses<br>Behavioral Measures]
    D --> E[Statistical Modeling<br>Correlations · Regression · EFA]
    E --> F[Findings & UX Insights<br>Decision-Making Under Uncertainty]
```

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
