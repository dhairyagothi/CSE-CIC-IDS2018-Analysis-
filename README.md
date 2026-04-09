# Group 2 - Foundation of Data Science (FDS)

## Project Overview
This notebook performs exploratory data analysis (EDA) on a network intrusion detection dataset from Kaggle (`solarmainframe/ids-intrusion-csv`).
It compares benign and attack traffic patterns using statistical summaries, visualizations, and hypothesis testing.

## Key Objectives
- Load and process intrusion detection CSV files in chunks.
- Analyze attack-type distribution.
- Compare attack vs benign traffic using selected flow features.
- Run statistical significance testing (Welch's t-test).
- Detect outliers in attack traffic.

## Features Used
- `Flow Duration`
- `Flow Byts/s`
- `Flow Pkts/s`
- `Label` (Benign vs Attack classes)

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- SciPy (`ttest_ind`)
- Kaggle API (for dataset download)

## How to Run
1. Open the notebook `Group_2_FDS.ipynb` in Google Colab or Jupyter.
2. Install dependencies if needed:
   - `pip install pandas numpy matplotlib scipy kaggle`
3. Upload your `kaggle.json` API key when prompted.
4. Run all cells in order:
   - Dataset download and extraction
   - EDA and visualizations
   - Distribution, mean comparison, t-tests, and outlier analysis

## Output Highlights
- Bar chart of attack label distribution
- Histograms comparing benign and attack traffic
- Descriptive statistics (mean, std, min, max)
- p-values showing whether feature differences are statistically significant
- Outlier counts for attack traffic

## Notes
- The notebook is optimized for large files by reading data in chunks.
- Numeric conversion with error handling is used to avoid invalid values.
- Infinite and missing values are cleaned before analysis.
# CSE-CIC-IDS2018-Analysis-
ML Model prediction data analysis of IDS 2018 Intrusion CSVs (CSE-CIC-IDS2018) . Foundation of Data Science Assignment Group 2
