# clabsi-sampling-strategies-analysis
# CLABSI Sampling Strategies Analysis

This repository contains the Capstone project submitted for BZAN 6360 – Capstone Practicum in Business Analytics at the University of Houston. The project focuses on selecting and evaluating sampling techniques for estimating Central Line-Associated Bloodstream Infections (CLABSI) in a skewed healthcare dataset.

## 📁 Contents

- `CapstoneReport1.ipynb` – Exploratory Data Analysis and feature understanding
- `CapstoneReport2.ipynb` – Sampling implementation and comparative statistical analysis
- `Project Report 2 pdf.pdf` – Final report submitted for the course
- `bzan6361_clabsi_1.csv.zip` – Raw dataset (zipped for size constraints)

## 📌 Objective

To analyze and compare probabilistic sampling techniques—specifically **Simple Random Sampling** and **Stratified Random Sampling**—to obtain representative 10% samples for predictive modeling of CLABSI occurrence.

## 🧪 Methodology

1. **Population Profiling** – Identify skewness in patient occurrence and CLABSI event distributions.
2. **Sampling Techniques** – Evaluate:
   - Simple Random Sampling
   - Stratified Random Sampling
3. **Statistical Analysis** – Compare descriptive statistics (mean, median, standard deviation) and perform hypothesis testing to validate sample representativeness.

## 🧠 Key Findings

- Stratified sampling better captured rare CLABSI cases and the distribution's skewness.
- Simple random sampling was easier to execute but less effective in representing outliers and rare events.
- Hypothesis testing confirmed sample validity in both methods, though stratified sampling showed slightly better alignment with the population.

## 📊 Tools Used

- Python (Pandas, NumPy, Matplotlib)
- Excel (for initial random sampling)
- Jupyter Notebook
