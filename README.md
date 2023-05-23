## Experiment Analysis - A/B Test

The purpose of this project is to analyze the results of an experiment conducted with a data science team. The experiment took place from 2023-01-31 to 2023-02-06 inclusive and involved two groups: Group 2, which used one of the new post recommendation algorithms, and Group 1, which served as the control group.

### Preparation and Conducting an A/B Test

The project includes the following notebooks for the analysis:

| Project Name | Description | Used Libraries |
|--------------|-------------|----------------|
| [AA-test](aa_test.ipynb) | Validation of the correctness of the split testing system. | python, numpy, pandas, scipy.stats, matplotlib |
| [AB-test](ab_test_1.ipynb) | Conducting analysis of A/B test data. | python, numpy, pandas, scipy.stats, matplotlib |
| [AB-test](ab_test_2.ipynb) | Analysis of the test based on the metric of linearized likes. | python, numpy, pandas, scipy.stats, seaborn |

These notebooks provide step-by-step analysis, visualization, and statistical calculations to gain insights from the experiment results. By conducting this A/B test analysis, we aim to evaluate the impact of the new post recommendation algorithm and make data-driven decisions based on the findings.
