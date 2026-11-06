# Salon Causal Inference: Evaluating Customer Retention Strategies

## Project Overview
This project applies statistical analysis and causal inference techniques to evaluate customer retention strategies for a fictional salon and spa chain operating 22 outlets in Coimbatore.

The project uses synthetic datasets containing approximately 300,000 operational appointment records, along with experimental and historical datasets, to demonstrate how data-driven decisions can be made.

## Download Dataset

[Download the complete 300,000-record synthetic dataset](data/DATASET_DOWNLOAD_LINK.md)

## Project Objectives
- Design a statistically sound A/B testing experiment.
- Evaluate treatment and control group balance.
- Perform Sample Ratio Mismatch (SRM) testing.
- Estimate treatment effects with confidence intervals.
- Conduct statistical power analysis.
- Apply Difference-in-Differences (DiD) to historical observational data.
- Use CUPED for variance reduction.
- Analyse treatment effects across customer segments.
- Develop a data-driven GO / NO-GO / EXTEND recommendation.

## Methodology

### 1. Data Cleaning and Preparation
- Handle missing values and duplicate records.
- Standardise service categories.
- Validate appointment dates and revenue values.
- Prepare datasets for causal analysis.

### 2. A/B Testing
- Randomisation balance assessment.
- Sample Ratio Mismatch testing.
- Welch's independent t-test.
- Bootstrap confidence intervals.
- Treatment effect estimation.

### 3. Statistical Power Analysis
- Evaluate sample size requirements.
- Estimate the statistical power of the experiment.

### 4. Difference-in-Differences (DiD)
- Compare treatment and control outlets.
- Evaluate pre- and post-intervention outcomes.
- Examine parallel trends.
- Calculate outlet-clustered standard errors.

### 5. CUPED
- Apply pre-experiment covariates.
- Reduce outcome variance.
- Compare adjusted and unadjusted estimates.

### 6. Customer Segmentation
- Evaluate treatment effects across customer groups.
- Identify differences in retention and business outcomes.

## Key Performance Metrics
- 90-day Customer Retention
- Revenue per Visit
- No-show Rate

## Technology Stack
- Python
- Pandas and NumPy
- SciPy and Statsmodels
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab
- GitHub

## Repository Structure

```text
salon-causal-inference/
│
├── data/
│   ├── ab_experiment_synthetic.csv
│   ├── historical_did_synthetic.csv
│   ├── DATA_DICTIONARY.txt
│   └── DATASET_DOWNLOAD_LINK.md
│
├── notebooks/
│   └── Salon_Causal_Inference_Analysis.ipynb
│
├── reports/
│   ├── Experiment_Design.docx
│   └── Decision_Memo.docx
│
├── results/
│   └── Statistical analysis result CSV files
│
├── graphs/
│   └── Generated analysis visualisations
│
└── README.md
```

## Key Outcome
The project demonstrates an end-to-end causal inference workflow combining experimental and observational analysis to evaluate customer retention strategies. It illustrates how A/B testing, DiD, CUPED, statistical testing, and segmentation can support evidence-based business decisions.

## Important Disclaimer
**All datasets used in this project are synthetic and generated for educational and analytical purposes.** They do not represent actual salon customers, transactions, or business performance. Findings demonstrate analytical methodology and should not be interpreted as real-world business impact.

## Author
Data Science and Artificial Intelligence & Machine Learning Project
