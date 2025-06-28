# 🚧 Traffic Accident Pattern & Hotspot Analysis

This project analyzes traffic accident data to identify **patterns** related to **weather conditions**, **road surface**, and **time of day**, and uses **spatial clustering** to detect accident **hotspots** using the `DBSCAN` algorithm.

---

## 🎯 Objective

- Explore how accidents vary by **hour of the day**, **weather**, and **road conditions**
- Use **geospatial clustering** (DBSCAN) to detect **accident-prone areas**
- Summarize **contributing factors** to these clusters such as time, road, and weather conditions

---

## 📂 Dataset

- File: `accident_data.csv`
- Key columns:
  - `datetime`: Timestamp of accident
  - `latitude`, `longitude`: GPS coordinates
  - `weather`: Weather at time of accident
  - `road_conditions`: Road condition description
  - `severity`: Numeric severity score

---

## 🧰 Technologies Used

- Python 3.x
- `pandas` – Data manipulation
- `seaborn` & `matplotlib` – Visualization
- `geopandas` – Spatial operations
- `contextily` – Basemap tiling
- `scikit-learn` – Clustering (DBSCAN)

---



