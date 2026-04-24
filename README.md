# 🚛 Industrial Air Quality Analysis: Truck Workshop Case Study

![Banner](./outputs/graphs/banner.png)

## 📝 Overview
This project investigates the impact of heavy-vehicle maintenance on local air quality. Using a 30-day telemetry dataset, we decouple operational emissions (PM & VOC) from external factors like highway traffic and meteorological conditions through diagnostic EDA and data normalization.

## 📊 Visualizing the Results
You can explore the findings of this study in two ways:

1.  **Static Report (Recommended for quick view):** Open the [**`exports/analysis_report.html`**](./exports/air_quality_eda.html) file directly in any web browser to see the full executed analysis, including all interactive-style plots and conclusions.
2.  **Interactive Notebook:** Open [**`air_quality_eda.ipynb`**](./air_quality_eda.ipynb) if you wish to see the underlying Python logic or re-run the analysis with your own parameters.

## 🛠️ Tech Stack
- **Language:** Python 3.12
- **Data Science:** Pandas, NumPy, Scikit-Learn (MinMaxScaler)
- **Visualization:** Seaborn, Matplotlib
- **Environment:** Jupyter Notebook, ipykernel

## 📂 Project Structure
## 📂 Project Structure

```text
.
├── data/                       # Raw environmental CSV logs
│   ├── pm_data.csv
│   ├── voc_data.csv
│   ├── temp_hr_data.csv
│   ├── wind_speed_data.csv
│   ├── wind_dir_data.csv
│   ├── rain_data.csv
│   └── air_quality_analysis.csv # Final integrated dataset
├── outputs/                    # Visual assets and plots
│   └── graphs/
│       └── final_sensor_banner.png
├── exports/                    # Documentation and static reports
│   └── analysis_report.html     # Notebook exported for quick viewing
├── .venv/                      # Python Virtual Environment (ignored by Git)
├── air_quality_eda.ipynb       # Main analysis engine (Root directory)
├── README.md                   # Project documentation and portfolio cover
├── requirements.txt            # Reproducibility dependencies
└── .gitignore                  # Git filters and exclusions
```

## 🚀 Installation & Setup
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Jotarose/air_quality_eda.git](https://github.com/Jotarose/air_quality_eda.git)
   cd air_quality_eda
