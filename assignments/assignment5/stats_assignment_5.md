---
title: "Statistics Assignment 5"
author: "Daniel Fuller"
date: "03/03/2020"
output:
      html_document:
        keep_md: true
---

# Statistics Assignment 5 - ANOVA

## General instructions

You must submit the following. 

**SPSS** 

- Syntax file
- Report in Word doc form with tables/figures cut and pasted from SPS output file

**R**

- RMarkdown file
- Knit report in HTML or PDF

Your report should include the following headings

1. Research Question
2. Research Design and Variables
3. Analysis and Results

## Data and research question

You are interested in determining the effect of relaxation techniques on level of stress. You develop a 3-group independent, post-test only experimental study. You randomly assigned 30 people into one of three groups

1.  yoga (n = 10)
2. guided imagery (n = 10)
3. placebo (breathe as normal; n = 10). 

Each group participates in a 30 minute relaxation technique. After the relaxation, you measure their overall levels of stress (on a 0-100 scale, with higher scores indicating greater levels of stress). 

## Research Question
What are the differences between relaxation techniques on level of stress? 

Conduct two one-way ANOVA
- with hypotheses (planned comparisons)
- without hypotheses (post hoc tests). 

## Part 1 Explore the data (18 Points)

- Discuss the normality of the data
- Must report and discuss the following for all main variables (IV & DV):
    - Histograms
    - Skewness & Kurtosis
    - Kolmogorov-Smirnov test
- Identify and discuss any outliers by presenting boxplots for all main variables (IV & DV) 
- Descriptive statistics for all main variables (IV & DV) (mean, standard deviation, and standard error) 
    - Overall
    - By group

## Part 2 ANOVA Planned Comparisons

Hypothesize that the yoga group will have the most positive effect on stress (i.e., lowest
stress level), followed by the deep breathing group, and then the guided imagery group (i.e., lowest
stress level).

Remember that you have to look at how the groups are coded in the data editor. The lowest value is for
placebo (1), then guided imagery (2), and the highest value is for yoga (3).

- Report the group differences in terms of the F-statistic, descriptive data, and planned comparisons.
- Report the F-statistic for the overall effect of the relaxation techniques on level of stress
- Report the F-statistic for the Polynomial Linear trend.
- Report both p-values and confidence intervals

Weights

| Group | Contrast 1 | Contrast 2 | Product |
|-----|-------|--------|-------|
| Placebo | -2 | 0 | 0 |
| Imagery | 1 | -1 | -1 |
| Yoga | 1  | 1 | 1 |
| Total | 0  | 0 | 0 |

## Part 2 ANOVA Post hoc comparisons

Now assume that you do not have a hypothesis and are just looking at the general trend of the data. 

- Report the group differences in terms of the F-statistic, descriptive data, and post-hoc tests.
- Conduct the following post-hoc tests  
    - Bonferonni (SPSS and R)
    - Tukey (SPSS and R)
    - Games Howell (SPSS and R)
- Report one of the tests and provide a rational for selecting the test you did.
- Report both p-values and confidence intervals
