# Analyze A/B Test Results
## by Eunice Oduwole

## Introduction 
A/B tests are very commonly performed by data analysts and data scientists. As such, this project is aimed at understanding the results of an  A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product.

The goal is help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer before making their decision.


## Dataset

The dataset contains 294478 entries with 5 columns;
- User id,
- timestamp,
- group which is either control or treatment,
- landing_page which is  either old page or new page,
- converted which is either 0 (for no) or 1 (for yes)

## Hypothesis

**H_0: p_(old) >  p_(new)**

**H_1: p_(old) < p_(new)**


## Summary of Findings

From the results obtained, the p-values were not statistically significant, as such, we do not have enough evidence to reject the null hypothesis. Thus, we can conclude base on this findings that the old page is performing better than the new page. 


