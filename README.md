
---

## 🧠 What I Did

- Collected and cleaned over **100,000+ rows** of crime records from the Chicago crime dataset
- Removed outliers, handled categorical and boolean features, and extracted temporal features
- Trained two **Random Forest Regressors**:
  - One for predicting **latitude**
  - One for predicting **longitude**
- Evaluated model performance using **MAE** and **RMSE**
- Built an **interactive map** with `folium` showing true vs predicted crime locations

---

## 📊 Example: Map Output

An interactive HTML map was generated showing predicted crime locations (🔴) vs actual (🔵).  
Open [`crime_predictions_map.html`](crime_predictions_map.html) to explore!

---

## 💡 Tech Stack

- `Python`
- `Pandas`, `NumPy`
- `Scikit-learn`
- `Matplotlib`, `Seaborn`, `Folium`

---

## 📈 Evaluation Metrics

| Target     | MAE (avg error) | RMSE (penalized error) |
|------------|-----------------|-------------------------|
| Latitude   |0.002009         |0.002764                  |
| Longitude  |0.002926         |0.004101                  |

(*Model showed strong spatial accuracy across city boundaries*)

---

## 🔥 Future Improvements

- Build a **Streamlit app** for real-time prediction and map rendering
- Include external datasets (weather, events) to enrich feature set
- Explore zone-based predictions using clustering

---

## 🙋‍♂️ Author

Anish Reddy Yellakonda 
[LinkedIn](www.linkedin.com/in/
anishreddy09
) • [GitHub](https://github.com/reddyanish311)

---

## 📎 Acknowledgments

- Data Source: [Chicago Data Portal – Crimes 2001 to Present](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2)
