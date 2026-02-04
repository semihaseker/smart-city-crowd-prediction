# 🌍 Smart City Crowd Prediction (NYC)

An AI-powered smart city analytics system that predicts pedestrian crowd levels in New York City using real-world open data and machine learning techniques.

This project demonstrates a complete data science workflow, from raw data processing to model deployment and interactive visualization.

---

## 📌 Project Motivation

Urban mobility and pedestrian congestion are major challenges in modern cities.

This project aims to:
- Analyze historical pedestrian traffic patterns
- Predict future crowd levels
- Support smart city planning and decision-making

using real public datasets and artificial intelligence.

---

## 🚀 Key Features

✔️ Real NYC pedestrian dataset (NYC Open Data)  
✔️ Data cleaning and preprocessing  
✔️ Spatial and temporal feature engineering  
✔️ Machine Learning classification (Random Forest)  
✔️ Multi-class prediction (Low / Medium / High)  
✔️ Interactive map visualization (Folium)  
✔️ End-to-end ML pipeline

---

## 🛠 Technology Stack

| Category | Tools |
|----------|--------|
| Language | Python |
| Data | Pandas, NumPy |
| ML | Scikit-learn |
| Visualization | Folium, Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 📊 Model Performance

- Algorithm: Random Forest Classifier  
- Accuracy: **76%**  
- Classes: Low / Medium / High  

Classification Summary:

```

Low     → 84% precision
Medium  → 69% precision
High    → 74% precision

```

---

## 🗺 Interactive Demo

An interactive map is generated to visualize predicted crowd levels.

### How to view:

1. Download the repository
2. Open the file below in your browser:

```

crowd_prediction_map.html

```

3. Zoom and click markers to explore predictions

---

## 📁 Project Structure

```

smart-city-crowd-prediction/
│
├── data/                     # Raw dataset
├── notebooks/                # Analysis notebook
│   └── analysis.ipynb
├── crowd_prediction_map.html # Interactive visualization
├── README.md
└── requirements.txt

````

---

## ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/semihaseker/smart-city-crowd-prediction.git
cd smart-city-crowd-prediction
````

Install dependencies:

```bash
pip install -r requirements.txt
```

Run analysis:

```bash
jupyter notebook notebooks/analysis.ipynb
```

---

## 📌 Dataset Information

Source:
NYC Open Data – Bi-Annual Pedestrian Counts

The dataset contains pedestrian volume measurements collected across multiple boroughs and time periods.

---

## 🔮 Future Improvements

* Deep Learning models (LSTM / Neural Networks)
* Real-time prediction API
* Web dashboard deployment
* Integration with traffic data
* Automated data updates

---

## ⭐ Acknowledgments

* NYC Open Data Portal
* OpenStreetMap
* Folium & Scikit-learn community

```
