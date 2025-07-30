# 2025-EY-Open-Science-AI-and-Data-Challenge

This project uses machine learning techniques to predict Urban Heat Island (UHI) intensity with high spatial resolution, supporting urban sustainability and climate resilience planning.

## 🧠 Overview
- Built a Random Forest regression model in **Jupyter Notebook**
- Achieved **R² = 0.8112** on the validation set
- Used over **5 geospatial datasets** including:
  - **Sentinel-2**
  - **Landsat**
  - **Ground-based temperature readings**
- Feature engineered from:
  - Building footprints
  - Vegetation indices (e.g., NDVI)
  - Weather/climate data

## 🌍 Key Features
- **Spatial generalization**: Models do **not** rely on latitude/longitude features, ensuring robustness across regions.
- **Scalable approach**: Designed for potential integration into urban planning tools or smart city platforms.
- **Collaboration**: Built with a team of 3, combining geospatial analysis, machine learning, and real-world application strategies.

## 📁 Project Structure
- `notebooks/` – Jupyter notebooks for exploration and modeling
- `data/` – Raw and processed datasets (or links)
- `src/` – Custom Python scripts (if any)
- `README.md` – Project overview and documentation

## 📌 Goals
To support sustainable city planning through predictive modeling of heat risk zones and inform mitigation efforts (e.g., green space allocation, building material use).

---

## 🔧 Future Work
- Add hyperparameter tuning with `GridSearchCV`
- Incorporate time-series data
- Deploy as a web-based visualization tool

---

## 🤝 Acknowledgements
Thanks to EY Open Science AI & Data Challenge 2025 and our data providers.
