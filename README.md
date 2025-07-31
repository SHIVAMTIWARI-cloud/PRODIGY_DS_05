# PRODIGY_DS_05
# 🚧 Traffic Accident Analysis - Prodigy Infotech Internship (Task 5)

This project analyzes synthetic traffic accident data to uncover patterns related to time, weather, and location, simulating real-world US accident data. It was developed as part of the Data Science Internship by **Prodigy Infotech**.

---

## 📁 Task Objective

> **Analyze traffic accident data** to identify patterns associated with:
- Weather conditions
- Road/environmental features
- Time of day/week

---

## 📊 Dataset

- **Type**: Synthetic (10,000 records)
- **Features**: 
  - Accident ID, Severity
  - Start/End Time, Latitude/Longitude, State
  - Weather Condition, Temperature, Visibility, Precipitation
  - Infrastructure Flags: Crossing, Junction, Stop, Traffic Signal, Roundabout
  - Daylight info: Sunrise/Sunset

---

## ⚙️ Key Steps

- Generated synthetic data to simulate US accidents using NumPy, Pandas, and random distributions.
- Extracted temporal features (hour, weekday) from timestamps.
- Summarized data using `.describe()` and visual inspections.
- Visualized:
  - Accidents by **Hour of Day**
  - Accidents by **Day of Week**
- Verified dataset shape and consistency (`(10000, 17)`).

---

## 📈 Visual Outputs

| Time of Day | Day of Week |
|-------------|--------------|
| ![Hour](./images/hourly.png) | ![Week](./images/weekly.png) |

---

## 🔍 Insights

- **Midday (12–14 hrs)** showed peak accident rates.
- Accidents were relatively consistent throughout the week, with a slight peak on **Thursdays and Fridays**.
- All generated features (weather, visibility, etc.) can be extended for multivariate analysis.

---

## 📦 Libraries Used

- `numpy`, `pandas`, `matplotlib`, `seaborn`, `datetime`

---

## 🧑‍💻 Intern Info

**Intern Name**: Shivam Tiwari  
**Internship**: Data Science Internship @ Prodigy Infotech  
**Duration**: July 1 – July 31, 2025

---

## 📌 Note

This dataset is synthetic and used solely for academic and demonstration purposes.

---

