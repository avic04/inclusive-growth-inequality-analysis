# inclusive-growth-inequality-analysis
Cross-country analysis of economic growth, inequality, poverty and inclusive growth using World Bank data.
# Inclusive Growth & Inequality Benchmarking

## Overview

This project analyzes the relationship between economic growth,
economic development, poverty and income inequality across India
and five benchmark economies.

The analysis uses World Bank data from 2000–2024.

## Research Question

How can economic growth translate into more inclusive economic
outcomes, and how does India compare with peer economies?

## Countries

- India
- China
- Brazil
- South Africa
- United States
- Germany

## Variables

| Variable | Description |
|---|---|
| GDP Growth | Annual GDP growth (%) |
| GDP per Capita | GDP per capita |
| Gini | Income inequality |
| Poverty | Poverty headcount ratio |
| Population | Total population |

## Methodology

1. Retrieve World Bank data through the API
2. Clean and validate the dataset
3. Conduct descriptive analysis
4. Analyze growth vs inequality
5. Estimate a Kuznets-style nonlinear relationship
6. Analyze growth vs poverty
7. Conduct country benchmarking
8. Estimate regression and fixed-effects models
9. Develop an inclusive-growth scorecard

## Key Analysis

### Growth and Inequality

Examines whether countries with stronger economic growth
experience different inequality outcomes.

### Kuznets Analysis

Tests whether the relationship between GDP per capita and
inequality is consistent with an inverted-U relationship.

### Country Benchmarking

Compares countries across:

- Economic growth
- GDP per capita
- Inequality
- Poverty

### Inclusive Growth Scorecard

Countries are benchmarked using normalized scores across
growth, development, inequality and poverty.

## Tools

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- World Bank API

## Reproducibility

The notebook retrieves data directly from the World Bank API,
allowing the analysis to be reproduced without manually
downloading the dataset.

## Limitations

The analysis identifies statistical associations and does not
establish causal relationships. Differences in data availability
and measurement across countries may also affect comparisons.

## Author

Your Name
