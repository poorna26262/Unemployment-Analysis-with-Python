# Unemployment Analysis with Python – India

## Objective
Explore regional and temporal unemployment trends in India, focusing on the COVID-19 period.

## Dataset
Download the Kaggle dataset **Unemployment in India**:
https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india

After extracting the download, copy `Unemployment in India.csv` into the `data/` folder.

The dataset is not bundled in this ZIP. Kaggle may require a free account and acceptance of its dataset terms.

## Project files
- `Unemployment_Analysis_India.ipynb` — commented notebook with cleaning, EDA, regional and monthly trends, three-region time series, top-10 ranking, correlation heatmap, and pre-/post-COVID comparison.
- `requirements.txt` — required Python packages.
- `data/` — place the downloaded CSV here.

## Run
```bash
pip install -r requirements.txt
jupyter notebook
```
Open `Unemployment_Analysis_India.ipynb` and select **Kernel → Restart & Run All**.

## Important interpretation notes
- The commonly used Kaggle file includes `Estimated Employed`, which is an estimated count, not an employment rate. The notebook labels it as a count in the correlation heatmap.
- The pre-COVID / COVID-period split uses 1 March 2020 as the cutoff.
- The dataset is historical and limited in coverage; it is not a current unemployment dashboard.
- Observational comparisons and correlations do not establish causation.
