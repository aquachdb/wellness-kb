# Z-Score

## Definition

A z-score (also called a standard score) indicates how many standard deviations a data point is from the population mean. In wellness testing, z-scores help contextualize your biomarker values relative to a reference population.

## Formula
z = (X - μ) / σ

Where:
- **X** = Your observed value
- **μ** (mu) = Population mean
- **σ** (sigma) = Population standard deviation

## Interpretation in Wellness Reports

| Z-Score Range | Interpretation | Percentile Equivalent |
|---------------|----------------|----------------------|
| > +2.0 | Significantly above average | ~98th percentile |
| +1.0 to +2.0 | Above average | 84th - 98th percentile |
| -1.0 to +1.0 | Within normal range | 16th - 84th percentile |
| -2.0 to -1.0 | Below average | 2nd - 16th percentile |
| < -2.0 | Significantly below average | ~2nd percentile |

## Clinical Application

**Positive z-scores** indicate values above the population mean. Depending on the biomarker, this may be:
- Favorable (e.g., HDL cholesterol, vitamin D)
- Unfavorable (e.g., mercury, inflammatory markers)

**Negative z-scores** indicate values below the population mean.

## Example

If your vitamin D level is 45 ng/mL and the reference population has:
- Mean (μ) = 30 ng/mL
- Standard deviation (σ) = 10 ng/mL

Your z-score = (45 - 30) / 10 = **+1.5**

This means you're 1.5 standard deviations above average (approximately 93rd percentile).

## Limitations

- Assumes normal (bell-curve) distribution
- Reference population matters (age, sex, ethnicity, geographic location)
- Not all biomarkers follow normal distributions

## Related Concepts

- [Percentile](percentile.md) - Alternative way to express relative standing
- Reference ranges - Clinical cutoffs may differ from statistical ranges

## References

1. Altman DG, Bland JM. Standard deviations and standard errors. BMJ. 2005;331(7521):903.
2. Horton NJ, Switzer SS. Statistical methods in the journal. N Engl J Med. 2005;353(18):1977-1979.

---

*This page is for educational purposes. Consult healthcare providers for medical interpretation.*
