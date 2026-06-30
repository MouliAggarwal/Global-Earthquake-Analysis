# 🌍 Global Earthquake Analysis Dashboard

An end-to-end data analytics project that analyzes global earthquake data using **Python (Google Colab)**, **Microsoft Excel**, and **Power BI**. The project focuses on data preprocessing, geographic enrichment, and interactive visualization to uncover patterns in earthquake occurrences, magnitudes, depths, tsunami events, and their global distribution.

---

## 📊 Dashboard Preview

![Dashboard Preview](Earthquake%20Analysis%20Dashboard.png)

---

# 📌 Project Overview

Earthquakes are among the most destructive natural disasters, making it essential to understand their occurrence, severity, and geographical distribution. This project analyzes a global earthquake dataset to identify trends in earthquake magnitude, depth, tsunami occurrence, and regional distribution.

The dataset was preprocessed using **Python in Google Colab**, where the **Country** and **Continent** for each earthquake were derived from its **latitude and longitude coordinates using reverse geocoding**. The enriched dataset was then cleaned and formatted in **Microsoft Excel** before being visualized in **Power BI** through an interactive dashboard.

---

# 🔄 Data Preprocessing

Before creating the dashboard, the dataset underwent several preprocessing steps:

- Cleaned and formatted the earthquake dataset.
- Derived **Country** and **Continent** information from **Latitude** and **Longitude** using **reverse geocoding in Python (Google Colab)**.
- Standardized categorical values for better visualization.
- Prepared the final dataset in Microsoft Excel for analysis in Power BI.

---

# 📂 Dataset Description

The dataset contains earthquake records along with their seismic and geographical characteristics.

| Column | Description |
|---------|-------------|
| Magnitude | Strength of the earthquake |
| Date & Time | Date and time when the earthquake occurred |
| Community Determined Intensity (CDI) | Intensity reported by people who experienced the earthquake |
| Alert | Earthquake alert level (Green, Yellow, Orange, Red) |
| Tsunami | Indicates whether the earthquake generated a tsunami warning |
| Significance Score | Overall significance assigned to the earthquake |
| Magnitude Type | Method used to calculate earthquake magnitude |
| Depth | Depth below the Earth's surface (km) |
| Latitude | North-South geographic coordinate |
| Longitude | East-West geographic coordinate |
| Location | Earthquake location |
| Country | Country where the earthquake occurred (derived using reverse geocoding) |
| Continent | Continent where the earthquake occurred (derived using reverse geocoding) |

---

# 📈 Dashboard Walkthrough

## 1. Key Performance Indicators (KPIs)

### What it shows

Summary cards displaying key earthquake statistics.

**KPIs Included**

- Average Magnitude
- Maximum Magnitude
- Average Depth
- Total Tsunami Events
- Countries Affected

### Insight

The KPI section provides a quick overview of the dataset by summarizing earthquake strength, depth, tsunami occurrence, and geographical coverage.

---

## 2. Global Distribution of Earthquakes (Map)

### What it shows

A world map displaying earthquake locations using latitude and longitude.

### Findings

- Earthquakes are distributed across multiple continents.
- The highest concentration of earthquakes occurs along tectonic plate boundaries.
- Regions within the Pacific Ring of Fire experience the greatest seismic activity.

### Insight

The visualization demonstrates that earthquake occurrences are closely linked to tectonic plate boundaries rather than being randomly distributed.

---

## 3. Earthquake Count by Continent

### What it shows

A comparison of earthquake occurrences across continents.

### Findings

- Oceania recorded the highest number of earthquakes.
- Asia and South America also experienced significant seismic activity.
- Europe and Africa recorded comparatively fewer earthquake events.

### Insight

The higher earthquake frequency in Oceania reflects its location within the Pacific Ring of Fire, one of the world's most active seismic regions.

---

## 4. Average Earthquake Depth by Continent

### What it shows

Comparison of the average depth of earthquakes across continents.

### Findings

- Earthquake depths vary considerably between continents.
- Some continents experience predominantly shallow earthquakes, while others record deeper seismic events.

### Insight

Earthquake depth significantly influences surface impact, with shallow earthquakes generally causing stronger ground shaking.

---

## 5. Relationship Between Depth and Magnitude (Scatter Plot)

### What it shows

A scatter plot comparing earthquake depth and magnitude.

### Findings

- Earthquakes of similar magnitudes occur at varying depths.
- High-magnitude earthquakes can occur at both shallow and deep depths.
- No strong linear relationship exists between depth and magnitude.

### Insight

Earthquake magnitude and depth represent different characteristics of seismic events and do not necessarily increase together.

---

## 6. Tsunami Distribution

### What it shows

Distribution of earthquakes based on whether they generated tsunami warnings.

### Findings

- Most earthquakes did not generate tsunami warnings.
- Only a small proportion of earthquakes resulted in tsunami events.

### Insight

Although earthquakes occur frequently, only certain underwater earthquakes with sufficient magnitude and displacement generate tsunamis.

---

## 7. Earthquake Alert Level Distribution

### What it shows

Distribution of earthquake alert levels.

### Findings

- Most earthquakes fall under lower alert categories.
- Only a few earthquakes receive Orange or Red alerts.

### Insight

Higher alert levels are issued only for earthquakes expected to cause significant damage or pose serious risks to nearby populations.

---

# 🛠️ Tools & Technologies

- **Python (Google Colab)** – Data preprocessing and reverse geocoding
- **Microsoft Excel** – Data cleaning and formatting
- **Microsoft Power BI** – Interactive dashboard development and visualization

---

⭐ **If you found this project helpful, consider giving this repository a star!**
