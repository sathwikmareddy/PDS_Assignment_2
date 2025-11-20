# COMP_SCI-5530-0005-43793-2025FS-Principles of Data Science — Assignment 2 and Question-2


Data Set Link: https://app.box.com/s/7qv44umhw0vnzgmoe9krfkfkv5kf2atv

Google Colab Link : https://colab.research.google.com/drive/1i4hufrzqLOSXCssyTznQeda9vGgSma6h?usp=sharing
 
Files provided: a polished Jupyter notebook ready for Google Colab and a short README to help you upload to GitHub.

What this package contains
- `notebook/diabetes_analysis.ipynb` — The main analysis notebook (also placed at repo root here for convenience).
- `data/diabetes.csv` — *This dataset must be uploaded by you to the `data/` folder in the repo or used from the local path `/mnt/data/diabetes.csv` when running locally/Colab.*

## How to use in Google Colab
1. Open Google Colab and create a new notebook.  
2. Upload `diabetes.csv` (use the Colab upload widget) or connect your Google Drive and place the file at `/content/drive/MyDrive/...` then update the path in the notebook.  
3. Copy the notebook content from `notebook/diabetes_analysis.ipynb` into Colab or upload the `.ipynb` file directly (File → Upload notebook).  
4. Run all cells. The notebook uses standard libraries (pandas, numpy, matplotlib) that are preinstalled in Colab.

## What I included in the notebook
- A reproducible random sample (seeded) for Part (a) and comparisons with the population.
- 98th percentile calculations and visuals for BMI (Part b).
- A bootstrap procedure (B=500, sample size=150, replace=True) for BloodPressure and comparisons with population statistics (Part c).
- Concise but original interpretations for each result block.