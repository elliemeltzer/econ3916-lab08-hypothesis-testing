# Hypothesis Testing — Is Job Training Worth It?

## Objective

I tested whether participation in the National Supported Work job-training program was associated with higher earnings in the LaLonde experimental sample.

## Methodology

- I analyzed 445 participants: 185 trainees and 260 controls.
- I compared the two groups’ 1978 earnings distributions.
- I conducted a one-sample t-test and a two-sample Welch’s t-test.
- I calculated Welch’s t-statistic manually and checked it against SciPy.
- I calculated Cohen’s d to measure the size of the earnings difference.
- I examined the study’s achieved power and the sample sizes required to detect smaller effects.
- I tested treatment effects across five overlapping demographic subgroups.
- I applied Bonferroni and Benjamini–Hochberg corrections.
- I simulated p-values when the null hypothesis was true and when a real effect existed.

## Key Findings

Trainees earned an average of $1,794.34 more than controls in 1978. Welch’s test produced a t-statistic of 2.6741 and a p-value of 0.0079.

The estimated Cohen’s d was 0.2727, indicating that the earnings difference was small relative to the variation among participants. The study’s calculated power at this observed effect size was 0.808.

Two of the five subgroup comparisons had uncorrected p-values below 0.05. After applying Bonferroni correction, only one remained significant. Benjamini–Hochberg also retained one subgroup.

These results provide evidence that the training program increased average earnings in this experimental sample, but statistical significance alone does not determine whether the program’s benefits exceeded its costs.
