# Clustering Urban Mobility Patterns Using Bike-Sharing Data

Lab assignment: clustering days of bike-share activity (not individual rides) using the
[UCI Bike Sharing Dataset](https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset).

## Project Structure
```
.
├── data/
│   ├── hour.csv          # raw hourly dataset (UCI)
│   ├── day.csv           # raw daily dataset (UCI, reference only)
│   └── Readme.txt         # UCI's original dataset documentation
├── clustering_analysis.ipynb   # main notebook: cleaning, features, clustering, evaluation
├── report/                # IEEE-format report (added later)
├── requirements.txt
└── README.md
```

## Methods Used
- K-Means
- Agglomerative Hierarchical Clustering (single / complete / average linkage)
- DBSCAN

## Status
🚧 In progress — built step by step. See commit history for progress.

## Reproducibility
- Random seed fixed at `42` throughout.
- Library versions pinned in `requirements.txt`.
