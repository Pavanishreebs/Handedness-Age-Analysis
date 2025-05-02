# 🧠 Handedness & Lifespan: A Bayesian Analysis
This project explores the correlation between handedness (left vs right) and average age at death using Bayesian statistical techniques. The goal is to estimate how average lifespan differs between left-handed and right-handed individuals by modeling probability distributions with real-world datasets.
# 📁 Datasets Used
handedness.csv
Contains percentage data on left-handedness by age and gender.

Age	Male	Female
10	13.2	12.5
...	...	...

death_distribution.csv
Contains number of deaths by age across genders.

Age	Both Sexes	Male	Female
0	12000	...	...
...	...	...	...

# 🚀 Project Objectives
Visualize left-handedness across age and birth cohorts.

Estimate the probability of being left-handed given age at death: P(LH | A)

Use Bayes' Theorem to reverse the conditional: estimate P(A | LH) and P(A | RH)

Visualize and compare probability distributions.

Estimate average age at death for LH vs RH individuals.

Repeat analysis for a more modern population (2018 vs 1986) to explore historical bias.

# 📊 Key Techniques
Bayesian Inference

Data interpolation

Pandas & Matplotlib for visualization

Data manipulation and probability modeling

# 📎 Google Colab Instructions
Upload the two CSV files when prompted.

Run each code block sequentially to:

Load and process data

Apply Bayesian modeling

Visualize probability distributions

Compute and compare results

# 📌 Results Summary
The model computes expected average ages at death for left- and right-handed individuals.

It shows how shifting birth rates and handedness prevalence over time affects the interpretation.

A comparison between 1986 and 2018 data reveals how past studies may have been biased due to demographic trends.

# 📁 Files in Repository
handedness.csv – Left-handedness data

death_distribution.csv – Age-wise death statistics

handedness_analysis.ipynb – Colab-ready notebook with full code and visualizations

README.md – This file

👩‍🔬 Authors & Credits
This project was implemented using Python and Google Colab as part of a statistical modeling assignment. The concept is inspired by real-world research examining population bias in perceived left-handed mortality.
