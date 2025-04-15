# Life Satisfaction in EU Countries (2013-2023)

This repository contains a simple analysis of life satisfaction levels across European Union countries, examining demographic and economic factors that influence subjective well-being.

## Data

The analysis uses data from the European Survey on Income and Living Conditions (EU-SILC) conducted by Eurostat, including:
- Overall life satisfaction scores (2013 vs 2023)
- Demographic breakdowns (gender, age groups, education levels)
- Economic indicators (median equivalized disposable income in PPS)

## Research Questions

1. How did life satisfaction levels change between 2013 and 2023?
2. What is the impact of demographic factors (gender, age, education) on life satisfaction?
3. What is the relationship between economic conditions and subjective well-being?

## Methodology

- Analysis of variance (ANOVA) for group comparisons
- Tukey's post-hoc tests for pairwise comparisons
- Mixed effects models for nested data structures
- Correlation and regression analysis for economic relationships

## Key Findings

- **Temporal Changes**: Significant increase in average life satisfaction from 6.92 in 2013 to 7.25 in 2023 (+4.8%)
- **Gender**: No statistically significant differences between men and women
- **Age**: Clear decline in satisfaction with age (youth: 7.63, seniors: 7.07)
- **Education**: Strong positive relationship with higher education levels showing greater satisfaction
- **Income**: Moderate correlation (r=0.61) between income and satisfaction, explaining ~37% of variation

## Files

- `projekt.ipynb`: Notebook containing all analysis steps and visualizations 
- `projekt.md`: Main analysis document (in Polish)
- `source/data.csv`: Dataset containing life satisfaction scores and demographic breakdowns
- `assets/`: Directory containing visualizations

## Usage

To reproduce the analysis:
1. Clone this repository
2. Run the `projekt.ipynb`
3. Refer to `projekt.md` for detailed methodology and findings