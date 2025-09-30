# Z-Score

## Definition

A Z-score (also called a standard score) is a statistical measurement that describes a value's relationship to the mean of a group of values. It is measured in terms of standard deviations from the mean.

## Formula

```
Z = (X - μ) / σ
```

Where:
- **Z** = Z-score
- **X** = Individual data point
- **μ** = Population mean
- **σ** = Population standard deviation

## Interpretation

- **Z = 0**: The value is exactly at the mean
- **Z > 0**: The value is above the mean
- **Z < 0**: The value is below the mean
- **|Z| > 2**: The value is considered unusual (more than 2 standard deviations from mean)
- **|Z| > 3**: The value is considered very unusual (more than 3 standard deviations from mean)

## Clinical Applications in Wellness Reports

### Biomarker Analysis
Z-scores help standardize biomarker values across different populations and reference ranges:

- **Normal Range**: Z-scores between -2 and +2 (approximately 95% of population)
- **Borderline**: Z-scores between -3 and -2, or +2 and +3
- **Abnormal**: Z-scores beyond ±3

### Age and Gender Adjustments
Z-scores allow comparison of biomarker values adjusted for:
- Age-specific reference ranges
- Gender-specific normal values
- Population-specific baselines

## Example in Wellness Context

If a patient's vitamin D level is 25 ng/mL:
- Population mean: 30 ng/mL
- Standard deviation: 10 ng/mL
- Z-score = (25 - 30) / 10 = -0.5

This indicates the patient's vitamin D level is 0.5 standard deviations below the population average, which is within normal range.

## Advantages

1. **Standardization**: Enables comparison across different scales and units
2. **Population Context**: Shows where an individual stands relative to peers
3. **Outlier Detection**: Easily identifies unusual values
4. **Statistical Interpretation**: Provides probabilistic meaning to measurements

## Limitations

1. **Assumes Normal Distribution**: May not be appropriate for skewed biomarker distributions
2. **Population Dependency**: Reference population must be appropriate and representative
3. **Clinical Context**: Statistical normality doesn't always equal clinical optimality

## Related Concepts

- [Percentile](./percentile.md): Alternative way to express relative position
- Standard Deviation: Measure of variability used in Z-score calculation
- Normal Distribution: Statistical distribution assumed in Z-score interpretation