# Winning the Space Race with Data Science
IBM Data Science Capstone Project

This project analyzes SpaceX Falcon 9 launch records to explore launch success factors, geographic patterns, and machine learning models that can predict landing outcomes. It includes data collection, wrangling, visualization, geospatial mapping, dashboard creation, and predictive modeling.

---

## Project Structure
```text
SpaceX-Project/
|
├── SpaceX Project Presentation.pdf
├── SpaceX_Machine Learning Prediction_Part.ipynb
├── spacex-dash-app.py
├── spacex_launch_dash.csv
├── Spacex.csv
|
├── dataset_part_1.csv
├── dataset_part_2.csv
├── dataset_part_3.csv
|
├── edadataviz.ipynb
├── lab_jupyter_launch_site_location.ipynb
├── jupyter-labs-webscraping.ipynb
├── jupyter-labs-spacex-data-collection-api.ipynb
├── labs-jupyter-Spacex-Data wrangling.ipynb
|
└── spacex_web_scraped.csv
```

---

## Project Objectives

- Collect SpaceX launch data using API, web scraping, and CSV files  
- Explore launch trends with SQL + Pandas  
- Visualize insights using Matplotlib, Seaborn, Plotly  
- Map launch sites and landing outcomes using Folium  
- Build machine learning models to predict landing success  
- Develop an interactive analytics dashboard with Dash  

---

## Key Insights from Analysis

- Landing success rates increased dramatically after 2015  
- All SpaceX launch sites are located near coastlines for safe eastward launches  
- KSC LC-39A shows the highest overall success ratio  
- Payload mass does not strongly correlate with landing outcome  
- Booster Version 5 (B5) appears most reliable in the dataset  

---

## Machine Learning Model Performance

| Model | Train Accuracy | Test Accuracy |
|-------|---------------|----------------|
| Logistic Regression | ~0.84 | ~0.83 |
| KNN | ~0.85 | ~0.83 |
| SVM | ~0.85 | ~0.83 |
| **Decision Tree** | **~0.89** | **~0.84** |

**Top Performer:** Decision Tree Classifier

---

## Geospatial Findings (Folium Mapping)

- All launch sites are near the coastline to avoid flying over populated regions  
- Launch sites maintain safe distances from major cities  
- Sites are positioned close to highways and railways for logistical transport  
- Marker clusters reveal which locations have the most successful launches  

---

## Interactive Dashboard

The dashboard includes:

- Successful launches by site (pie chart)  
- Success vs. failure distribution  
- Payload vs. outcome scatterplots  
- Booster version filters  
- Payload range slider  


---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Plotly, Dash  
- Folium  
- Scikit-learn  
- SQLite  
- BeautifulSoup, Requests  
- Jupyter Notebook  

---

## Conclusions

- Falcon 9 landing success has improved steadily over time  
- Launch site location and booster version play major roles in success  
- Machine learning models can predict landing outcomes with ~84% accuracy  
- Geospatial patterns show why SpaceX chooses coastal launch facilities  
- Dashboard visualizations support interactive exploration of mission history  

---

## Author

**Peter Cheng**  
IBM Data Science Capstone (2025)




