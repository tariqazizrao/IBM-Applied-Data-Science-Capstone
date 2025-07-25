# IBM-Applied-Data-Science-Capstone

## Predicting SpaceX Falcon 9 First-Stage Landing Success Using Machine Learning

This capstone project, part of the IBM Data Science Professional Certificate on Coursera, demonstrates the practical application of data science skills through a real-world scenario. The objective is to **predict the success of SpaceX Falcon 9 first-stage landings**, which directly impacts launch costs and operational planning.

---

## 🔍 Problem Statement

SpaceX has significantly reduced launch costs by reusing its Falcon 9 boosters. This project aims to:
- Identify factors influencing landing success (e.g., payload mass, orbit type, launch site, booster reuse).
- Track landing success trends over time.
- Develop a **binary classification model** to predict landing outcomes.

---

## 📂 Project Structure

This repository is organized by the following notebooks:

| # | Notebook | Description |
|--|----------|-------------|
| 1 | [`Data Collection API`](./1.%20Data%20Collection%20-jupyter-labs-spacex-data-collection-api.ipynb) | Extract launch data from the SpaceX REST API |
| 2 | [`Web Scraping`](./2.%20Web%20Scrapping%20-%20jupyter-labs-webscraping.ipynb) | Scrape launch details from Wikipedia |
| 3 | [`Data Wrangling`](./3.%20Data%20Wrangling%20-labs-jupyter-spacex-Data%20wrangling.ipynb) | Merge, clean, and prepare data for analysis |
| 4 | [`EDA with Visualization`](./4.EDA%20with%20data%20visualization%20-edadataviz.ipynb) | Explore data through graphs and trends |
| 5 | [`EDA with SQL`](./5.%20EDA%20with%20SQL%20-%20jupyter-labs-eda-sql-coursera_sqllite.ipynb) | Query data using SQLite and SQL skills |
| 6 | [`Interactive Map (Folium)`](./6.%20Interactive%20Visual%20Analytics%20with%20Folium%20-lab_jupyter_launch_site_location.ipynb) | Visualize launch sites and outcomes on a map |
| 7 | [`Dashboard (Plotly Dash)`](./7.%20Machine%20Learning%20Prediction%20-%20SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb) | Build a dynamic dashboard to filter and analyze launch success |
| 8 | [`Machine Learning Prediction`](./7.%20Machine%20Learning%20Prediction%20-%20SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb) | Apply and evaluate classification models (Logistic Regression, SVM, Decision Tree, KNN) |

---

## 📊 Tools & Technologies

- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Plotly Dash, Folium, BeautifulSoup  
- **Databases**: SQLite  
- **APIs**: SpaceX REST API  
- **Jupyter Notebooks**

---

## 🤖 Machine Learning Approach

- Feature Engineering: One-Hot Encoding, Labeling Success/Failure  
- Models: Logistic Regression, SVM, Decision Tree, KNN  
- Evaluation Metrics: Accuracy, F1 Score, Jaccard Index, Confusion Matrix  
- Best Model: Decision Tree (based on F1 Score and interpretability)

---

## 🗺️ Key Insights

- Launch success has improved significantly since 2013.
- KSC LC-39A has the **highest success rate** among all launch sites.
- Heavy payloads **reduce success rates** in GTO orbits but **increase success** in LEO or Polar orbits.
- Success rates vary significantly with orbit type and launch site.

---

## 📎 Report

View the detailed [Project Report PDF](./ds-capstone-template-coursera.pdf) containing summaries, screenshots, visualizations, and results.

---

## 📌 Author

**Tariq Aziz Rao**  
*IBM Certified Data Analyst & Machine Learning Enthusiast*  
[GitHub Profile](https://github.com/tariqazizrao)

---

## 📜 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

- [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science)
- [SpaceX API](https://github.com/r-spacex/SpaceX-API)
- [Wikipedia](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)

