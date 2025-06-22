# spacex-capstone
# 🚀 SpaceX Falcon 9 Launch Analysis & Success Prediction

This project was created as part of the **IBM Data Science Capstone Course** on Coursera.  
It performs an end-to-end data science workflow including **data collection, SQL analytics, geospatial visualization, dashboard creation**, and **machine learning classification** to predict the success of SpaceX Falcon 9 rocket landings.

---

## 📌 Project Structure
📁 spacex-capstone/
├── API_Collection.ipynb # Collected SpaceX data using REST API
├── WebScraping_Wiki.ipynb # Scraped Falcon 9 table from Wikipedia
├── SQL_Queries.ipynb # Performed SQL-based analysis using SQLite
├── Folium_Map.ipynb # Created interactive map of launch sites
├── Plotly_Dashboard.py # Dash app for interactive visualization
├── ML_Classification.ipynb # Built SVM, Decision Tree, and KNN models
├── spacex_launch.csv # Final cleaned dataset
├── README.md # Project overview (this file)


---

## 📊 Technologies Used

- Python (Pandas, NumPy)
- APIs (SpaceX REST API)
- Web Scraping (BeautifulSoup)
- SQLite + SQL magic in Jupyter
- Data Visualization: Matplotlib, Seaborn, Folium, Plotly
- Interactive Dashboards: Dash (by Plotly)
- Machine Learning: scikit-learn

---

## 📂 Data Sources

- 🚀 [SpaceX Launches API](https://api.spacexdata.com/v4/launches)
- 📄 [Wikipedia: Falcon 9 Launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)

---

## 📈 Key Insights

- Landing success rates have improved significantly since 2017.
- Drone ship landings are more successful for high-mass and GTO missions.
- Orbit and launch pad type have a notable influence on mission success.
- The best-performing ML model was a **Decision Tree Classifier (~93% accuracy)**.

---

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/spacex-capstone.git
   cd spacex-capstone
2. Install dependencies:
pip install -r requirements.txt
3. Launch the dashboard (optional):
python Plotly_Dashboard.py
Open Jupyter and run .ipynb notebooks step by step.

Model Summary
Model	Test Accuracy
Decision Tree	93%
SVM (RBF)	89%
KNN (k=5)	86%

🏁 Final Outcome
This project showcases the full data science lifecycle applied to a real-world dataset. The integration of API data, web scraping, SQL, mapping, dashboards, and classification models demonstrates practical skills valuable for roles in Data Science and Analytics.

🙋‍♀️ Author
Vartika Jain
GitHub Profile
Data Science Capstone – Coursera x IBM

Let me know if:
- You want a `requirements.txt` auto-generated
- You want a version that includes Colab links
- You want this in a downloadable `.md` file

Happy coding!

