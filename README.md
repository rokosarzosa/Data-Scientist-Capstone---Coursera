![Python](https://img.shields.io/badge/Python-3.8+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Complete-success)
# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## Overview
End-to-end data science project that analyzes SpaceX launch data to predict the success of Falcon 9 first stage landings. By accurately predicting landing outcomes, we can estimate launch costs and provide competitive intelligence for the aerospace industry.

## Business Context
- SpaceX Falcon 9 launches cost **$62 million** vs competitors at **$165+ million**
- Cost savings driven by **first stage reusability**
- Predicting landing success = Predicting launch cost

## Project Highlights
- 📊 **Data Collection**: REST API integration + Web scraping
- 🔍 **Exploratory Analysis**: SQL queries, statistical visualizations
- 🗺️ **Interactive Analytics**: Folium maps + Plotly Dash dashboard
- 🤖 **Machine Learning**: Classification models with 94%+ accuracy

## Tech Stack
- **Python**: pandas, numpy, scikit-learn
- **Data Collection**: requests, BeautifulSoup
- **Visualization**: matplotlib, seaborn, Plotly, Folium
- **Database**: SQL (SQLite)
- **ML**: Logistic Regression, SVM, Decision Trees, KNN

## Key Findings
- ✅ Success rate improved from 45% to 92+ over time
- ✅ KSC LC-39A shows highest success rate across all launch sites
- ✅ Decision Tree Classifier achieved best predictive performance
- ✅ Orbit type and payload mass are significant predictors

## Repository Structure
```
├── data/                          # Raw and processed datasets
├── notebooks/                     # Jupyter notebooks for analysis
│   ├── 01_data_collection_api.ipynb
│   ├── 02_web_scraping.ipynb
│   ├── 03_data_wrangling.ipynb
│   ├── 04_eda_sql.ipynb
│   ├── 05_eda_visualization.ipynb
│   ├── 06_interactive_map.ipynb
│   ├── 07_dashboard.ipynb
│   └── 08_machine_learning.ipynb
├── presentation/                  # Project presentation slides
└── README.md
```

## Getting Started
```bash
# Clone the repository
git clone https://github.com/tu-usuario/spacex-landing-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run notebooks in order (01 through 08)
```

## Results & Insights
Full analysis and results available in the [presentation slides](./presentation/RODRIGO_SARZOSA_DATA_SCIENTIST_CAPSTONE.pdf)

## Author
**Rodrigo Sarzosa**
- LinkedIn: [tu-perfil]
- Portfolio: [tu-portfolio]

## Acknowledgments
Data sourced from SpaceX API and Wikipedia

🚀 OPCIÓN 3: Minimalista (si prefieres algo más breve)
markdown# SpaceX Falcon 9 Landing Prediction

Machine learning project predicting first stage landing success of SpaceX Falcon 9 rockets.

**Highlights:**
- Data collected via SpaceX API & web scraping
- Comprehensive EDA with SQL and visualizations
- Interactive dashboard and geospatial analysis
- ML models achieving 94%+ accuracy

**Stack:** Python • pandas • scikit-learn • SQL • Plotly • Folium

📊 [View Full Presentation](./presentation/)
