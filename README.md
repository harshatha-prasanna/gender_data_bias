# Gender-Aggregated Data Bias in ACS Income Dataset

## Overview
This project analyzes gender and racial income disparities in the 2018 American Community Survey (ACS) data, with a focus on how household-level data aggregation obscures individual economic inequality. Inspired by Caroline Criado Perez's *Invisible Women*, this analysis examines structural biases in how we collect and represent income data.

## Motivation
After reading *Invisible Women*, I became interested in how data collection practices can encode gender bias. The ACS Income dataset's use of 'household reference persons' exemplifies how structural choices in data design can mask individual disparities, particularly for women. This project explores...

## Research Questions
- How does income vary by gender and race in the 2018 ACS data?
- Does the household aggregation method obscure individual gender disparities?
- How do intersectional identities (e.g., race + gender) affect income outcomes?
- What would more equitable data collection practices look like?

## Dataset
- **Source**: American Community Survey (2018) via fairlearn library
- **Size**: [X observations, Y features]
- **Key Variables**: Sex, Race, Age, Education, Employment Status, Income
- **Geographic Coverage**: []

## Methodology
Brief description of your approach:
- Exploratory data analysis
- Statistical testing for disparities
- Intersectional analysis
- Visualization of findings
- Proposals for fairer data practices

## Key Findings
[Fill this in after you do the analysis]
- Finding 1
- Finding 2
- Finding 3

## Tools & Libraries
- Python 3.11
- pandas
- fairlearn
- matplotlib/seaborn
- scipy/statsmodels [if using statistical tests]

## Project Structure
```
├── README.md
├── data_exploration.ipynb    # Initial data exploration
├── bias_analysis.ipynb        # Main analysis
├── visualizations/            # Generated plots
└── report.pdf                 # Final writeup
```

## How to Run
```bash
pip install fairlearn pandas matplotlib seaborn
jupyter notebook bias_analysis.ipynb
```

## Future Work
- Expand to more states for geographic comparison
- Develop automated bias detection tool
- Compare with other income datasets
- [Other ideas you have]

## References
- Criado Perez, C. (2019). *Invisible Women: Data Bias in a World Designed for Men*
- [Papers you read]
- [fairlearn documentation]

## Author
Harshatha Prasanna
https://github.com/harshatha-prasanna

## Acknowledgments
