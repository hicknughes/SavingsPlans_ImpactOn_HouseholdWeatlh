## Overview
To illustrate double ML in an example with high dimensional controls, I investigate the relationship between financial savings plans and household wealth. The 1991 Survey of Income and Program Participation (SIPP) consists of 9915 observations of household finances for households with at least one working age member. Similar data has been analyzed in a number of economics articles that investigate the relationship between tax advantaged savings plans (particularly the 401k plans that are offered by many employers in the US) and employee savings. This particular dataset is taken from Chernozhukov and Hansen (2004), where they investigate the treatment effect of 401(k) plan participation on total household wealth.

### Approach & The Data
I estimate the treatment effect of the 401(k) participation on total household wealth. The response y is 'tw', and the treatment d is the binary indicator 'p401', i1-i7 are income wealth categories, a1-a7 are categories for the age of the reference household member, and the remaining variables represent demographic information such as family size (fsize), whether the household member has completed high school (hs), some college (smcol), owns a house (hown), participates in an IRA savings plan (pira), or has a deferred benefits pension plan (db). [We convert inc to be measured in units of 10,000 to avoid numeric overload when computing quadratic and cubic transformations.]

### Conclusions
Detailed in the jupyter notebook, the merits of the different model approaches are weighed in this analysis.

##### This project is part of my MS Quantitative Economics coursework from California Polytechnic State University. 
##### Course: Machine Learning for Prediction and Causal Inference
