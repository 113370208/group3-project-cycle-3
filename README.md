# Project Cycle 3: Two-Sample Inference

**Group Members:**
- 113370208 李瑞澄
- 113370227 游尚鈞

## Research Question
**Question 6:** Does the average BMI percentile differ between students who currently smoke and those who do not?
(目前有吸菸與沒有吸菸的學生，其平均 BMI 百分位數是否不同？)

## Variables Defined
- **Grouping Variable (分組變數):** `SmokeStatus` (Binary). 
  - `0` = Non-smokers (Control group)
  - `1` = Currently Smoke (Exposure group)
- **Response Variable (反應變數):** `BMIPCT` (Quantitative / Continuous). BMI percentile of the students.

## Statistical Method
**Welch's Two-Sample t-test**
We chose this method because we are comparing the means of a quantitative response variable between two independent groups, and we do not assume equal population variances.

## Brief Conclusion
Yes, there is a statistically significant difference (p-value = 0.0032). Students who currently smoke have a slightly higher average BMI percentile (mean = 66.23) compared to non-smoking students (mean = 64.39).# group3-project-cycle-3
