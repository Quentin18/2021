# Statistical tests

p-value < 0.05 => we can reject H0

Test | Description | Python
--- | --- | ---
Shapiro-Wilk | Tests the null hypothesis that the data was drawn from a normal distribution. | `scipy.stats.shapiro`
Kolmogorov-Smirnov | Tests the null hypothesis that the data was drawn from a distribution. | `statsmodels.stats.diagnostic.kstest_normal`
Pearson | Tests non-correlation. | `scipy.stats.pearsonr`
Spearman | Tests non-correlation. | `scipy.stats.spearmanr`
T-test | Tests equality of means. | `scipy.stats.ttest_ind`
Z-test | Tests proportion. | `scipy.stats.proportion.proportions_ztest`

## References

- [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html#statistical-tests)
- [statsmodels](https://www.statsmodels.org/stable/stats.html)
