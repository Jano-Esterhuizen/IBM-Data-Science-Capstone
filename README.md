# 🚀 IBM Data Science Capstone: SpaceX Falcon 9 Landing Prediction

## 📌 Project Overview
This project is part of the **IBM Data Science Capstone** course and focuses on **predicting the successful landing of the SpaceX Falcon 9 first stage booster**. The goal is to analyze past launch data and build a predictive model to estimate the likelihood of a booster landing successfully.

## 🛠 Technologies & Tools Used
- **Python**
- **Jupyter Notebooks**
- **Pandas, NumPy** (Data Wrangling & Processing)
- **BeautifulSoup, Requests** (Web Scraping)
- **SQL** (Database Queries for Exploratory Data Analysis)
- **Folium** (Interactive Maps)
- **Plotly Dash** (Dashboard for Data Visualization)
- **Machine Learning** (Supervised Learning Models)

## 📂 Repository Structure
```
IBM-Data-Science-Capstone/
│── Capstone Presentation.pdf                # Project presentation slides
│── Week 1 - Data Collection API Lab.ipynb   # Collecting SpaceX launch data using APIs
│── Week 1 - Falcon9_Data_Collection_with_Web_Scraping.ipynb  # Web scraping launch data
│── Week 1 - SpaceX_Falcon9_DataWrangling.ipynb  # Cleaning and preprocessing data
│── Week 2 - SpaceX_Falcon9_EDA_SQL.ipynb   # Exploratory Data Analysis using SQL
│── Week 2 - SpaceX_Falcon9_EDA_VizLab.ipynb  # Data visualization of launch data
│── Week 3 - SpaceX_Falcon9_Interactive_Viz_Folium.ipynb  # Mapping launch sites using Folium
│── Week 3 - SpaceX_Falcon9_Plotly_Dashboard.py  # Interactive dashboard with Plotly Dash
│── Week 4 - SpaceX_Falcon9_ML_PredictiveAnalysis.ipynb  # ML model for landing prediction
└── README.md  # Project documentation
```

## 📊 Key Project Steps
1. **Data Collection**  
   - Scraped Falcon 9 launch data from Wikipedia.
   - Retrieved historical launch records via API.
   - Stored data in Pandas DataFrames.

2. **Data Wrangling & Cleaning**  
   - Removed missing values and handled inconsistent data.
   - Extracted and formatted key information such as payload mass, launch site, and landing status.

3. **Exploratory Data Analysis (EDA)**  
   - Used SQL queries to analyze launch success rates.
   - Created visualizations to understand patterns in launch outcomes.

4. **Interactive Visualizations**
   - **Folium Maps**: Mapped launch sites and success rates.
   - **Plotly Dash Dashboard**: Built an interactive web dashboard for real-time data exploration.

5. **Machine Learning Model**
   - Developed classification models (Logistic Regression, Decision Trees, etc.).
   - Predicted the likelihood of a Falcon 9 booster successfully landing.

## 📈 Results & Insights
- Analyzed past launch data to identify factors influencing landing success.
- Built a dashboard to visually explore trends in SpaceX launch history.
- Developed an ML model to predict future landings with reasonable accuracy.
