# Synthetic-Dataset-Generation-for-Geotechnical-Parameters
This project involves generating a synthetic dataset for geotechnical parameter testing by tailoring random data to reflect realistic field conditions. 
This project generates a synthetic dataset tailored for geotechnical parameter testing, simulating realistic field conditions for research, analysis, and modeling. It incorporates statistical controls and realistic correlations to mimic real-world geotechnical behavior, making it ideal for testing predictive models or validating analytical approaches. 


PRNGs (Pseudo-Random Number Generators), such as those in Python’s numpy library, are deterministic and reproduce results when seeded. They’re ideal for generating synthetic datasets based on specified statistical parameters.

**Features**

1. Correlation Between Variables

- Variables exhibit realistic interdependencies (e.g., higher soil density correlates with higher shear strength).
- Correlations are customizable and derived from domain knowledge or input data.

2. Statistical Metrics
Each variable adheres to the following statistical properties:

- Minimum (min) and Maximum (max) values.
- Mean and Standard Deviation (std) for realistic variability.
- Customizable distributions (e.g., normal, uniform, log-normal).

3. Sample Size

- Users can specify the number of samples required for their test scenarios. 

**Use Cases**

- Testing and validating geotechnical models.
- Sensitivity analysis for geotechnical parameters.
- Training machine learning models in the absence of real-world data. 

**Requirements**

- Python 3.8 or later.
- numpy, pandas, matplotlib, seaborn, scipy.
