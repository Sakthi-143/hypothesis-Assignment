# hypothesis-Assignment
# Readme File

 ## Question 1  
### Objective:  
To determine whether there is any significant difference in the diameter of the cutlet between two units.

### Data:
- **Input File:** `Cutlets.csv`
- **Description:** A randomly selected sample of cutlets from both Unit A and Unit B, with their respective diameters measured.

### Analysis: 
- **Hypothesis Test:** Two-sample t-test
- **Assumptions Checked:**
  1. Normality of data (Shapiro-Wilk test)
  2. Homogeneity of variances (Levene's test)
- **Significance Level:** 5%

### Results:
- **Null Hypothesis:** There is no significant difference in the diameter of the cutlet between Unit A and Unit B.
- **Conclusion:** Fail to reject the null hypothesis, indicating no significant difference.

## Question 2
### Objective:
To determine whether there is any difference in the average Turn Around Time (TAT) of reports among different laboratories.

### Data:
- **Input File:** `LabTAT.csv`
- **Description:** TAT for reports from four different laboratories.

### Analysis:
- **Hypothesis Test:** One-way ANOVA
- **Significance Level:** 5%

### Results:
- **Null Hypothesis:** There is no significant difference in average TAT among laboratories.
- **Conclusion:** Reject the null hypothesis, indicating a significant difference in average TAT among laboratories.

## Question 3
### Objective:
To find if male-female buyer ratios are similar across regions.

### Data:
- **Input File:** `BuyerRatio.csv`
- **Description:** Sales of products in four different regions categorized by gender.

### Analysis:
- **Hypothesis Test:** Chi-square test of independence
- **Significance Level:** 5%

### Results:
- **Null Hypothesis:** There is no association between gender and region.
- **Conclusion:** Fail to reject the null hypothesis, indicating no association between gender and region.

## Question 4
### Objective:
To check whether the defective percentage varies by center in processing customer order forms.

### Data:
- **Input File:** `CustomerOrderForm.csv`
- **Description:** Audit results of customer order forms from four different centers.

### Analysis:
- **Hypothesis Test:** Chi-square test of independence
- **Significance Level:** 5%

### Results:
- **Null Hypothesis:** There is no association between country and defective status.
- **Conclusion:** Fail to reject the null hypothesis, indicating no association between country and defective status.
