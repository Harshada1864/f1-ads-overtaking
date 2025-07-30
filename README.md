# F1-Inspired ADS Overtaking Stress Test

Analyzes 2020 F1 telemetry (Turkish GP) with an ADS-like model for overtaking in rainy conditions. Logs decisions and visualizes success rates by turn with an interactive Plotly bar chart.

## Files
- `f1_ads_overtaking.ipynb`: Analyzes data, simulates ADS decisions, saves results.
- `f1_ads_visualization.ipynb`: Creates interactive bar chart.
- `overtaking_success.html`: Interactive chart.

## Setup
1. Install Anaconda Navigator: https://www.anaconda.com/
2. Install libraries: `conda install pandas plotly scikit-learn`
3. Download dataset from https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020
4. Place `lap_times.csv`, `races.csv`, `drivers.csv` in a `data/` folder in the project directory.
5. Run `f1_ads_overtaking.ipynb` in Jupyter Notebook via Anaconda Navigator.
6. Run `f1_ads_visualization.ipynb` in Jupyter Notebook.

## Results
Shows ADS-like overtaking success rates by turn in a rainy F1 scenario, highlighting key corners (e.g., Turn 11) for autonomous driving optimization.

## Credits
- Dataset: Formula 1 World Championship (1950-2020) by Rohan Rao (Kaggle). URL : https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020
