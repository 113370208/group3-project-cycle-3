# Recoding Notes

Research question: Is the mean BMI percentile different between students who currently use cigarettes and those who do not?

Group variable: CurrentCigaretteUse

Recoding:
- Original code 1 -> 0 = Non-current cigarette user
- Original codes 2 through 7 -> 1 = Current cigarette user
- Missing or invalid CurrentCigaretteUse values are excluded

Response variable:
- BMIPCT = BMI percentile
- Missing BMIPCT values are excluded
- BMI percentile values are kept only if they are between 0 and 100

Method planned:
- Welch two-sample t-test
- 95% confidence interval for the difference in mean BMI percentile
- Difference order: current cigarette users minus non-current cigarette users
