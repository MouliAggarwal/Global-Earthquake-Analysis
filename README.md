# 🌍 Global Earthquake Analysis Dashboard

An end-to-end data analytics project that analyzes global earthquake data using **Google Colab**, **Microsoft Excel**, and **Power BI**. This project focuses on data preprocessing, geographic mapping, and interactive visualization to uncover patterns in earthquake occurrences, magnitudes, depths, and tsunami events.

---

## 📊 Dashboard Preview

> *(Add your Power BI dashboard screenshot below)*

![Dashboard](Images/dashboard.png)

---

# 📌 Project Overview

Earthquakes are among the most destructive natural disasters, making it essential to understand their occurrence, severity, and geographical distribution. This project analyzes a global earthquake dataset to identify trends in earthquake magnitude, depth, tsunami occurrence, and regional distribution.

The dataset was preprocessed using **Google Colab**, refined in **Microsoft Excel**, and visualized using **Power BI** to build an interactive dashboard that provides meaningful insights into global seismic activity.

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
| Magnitude Type | Method used to calculate magnitude |
| Depth | Depth below the Earth's surface (km) |
| Latitude | North-South geographic coordinate |
| Longitude | East-West geographic coordinate |
| Location | Earthquake location |
| Country | Country where the earthquake occurred |
| Continent | Continent where the earthquake occurred |

---

# 📈 Dashboard Walkthrough

## 1. Key Performance Indicators (KPIs)

### What it shows

Summary cards displaying important earthquake statistics.

**KPIs Included**

- Average Magnitude
- Maximum Magnitude
- Average Depth
- Total Tsunami Events
- Countries Affected

### Insight

The KPI section provides a quick overview of the dataset by summarizing earthquake strength, average depth, tsunami occurrence, and the geographical coverage of recorded events.

---

## 2. Global Distribution of Earthquakes (Map)

### What it shows

A world map displaying earthquake locations using latitude and longitude coordinates.

### Findings

- Earthquakes are distributed across multiple continents.
- Most earthquake events are concentrated around tectonic plate boundaries.
- Regions along the Pacific Ring of Fire experience the highest seismic activity.

### Insight

The visualization clearly demonstrates that earthquakes are concentrated around active tectonic plate boundaries rather than being randomly distributed.

---

## 3. Earthquake Count by Continent

### What it shows

A comparison of earthquake occurrences across different continents.

### Findings

- Oceania recorded the highest number of earthquakes.
- Asia and South America also experienced considerable seismic activity.
- Europe and Africa recorded comparatively fewer earthquake events.

### Insight

The higher earthquake frequency in Oceania reflects its location within the Pacific Ring of Fire, one of the world's most active seismic zones.

---

## 4. Average Earthquake Depth by Continent

### What it shows

Comparison of the average depth of earthquakes across continents.

### Findings

- Average earthquake depth differs significantly between continents.
- Some regions experience predominantly shallow earthquakes, while others record deeper seismic events.

### Insight

Earthquake depth plays a major role in determining surface impact. Shallow earthquakes generally cause stronger ground shaking than deeper earthquakes of similar magnitude.

---

## 5. Relationship Between Depth and Magnitude (Scatter Plot)

### What it shows

A scatter plot illustrating the relationship between earthquake depth and magnitude.

### Findings

- Earthquakes of similar magnitudes occur at different depths.
- Strong earthquakes can occur at both shallow and deep depths.
- No clear linear relationship exists between depth and magnitude.

### Insight

Magnitude and depth represent different characteristics of an earthquake and do not necessarily increase together.

---

## 6. Tsunami Distribution

### What it shows

Distribution of earthquakes based on whether they generated tsunami warnings.

### Findings

- Most earthquakes did not generate tsunami warnings.
- Only a relatively small proportion resulted in tsunami events.

### Insight

Although earthquakes occur frequently, only certain underwater earthquakes with sufficient magnitude and vertical displacement generate tsunamis.

---

## 7. Earthquake Alert Level Distribution

### What it shows

Distribution of earthquake alert levels.

### Findings

- Most earthquakes fall under lower alert categories.
- Only a small number of earthquakes receive Orange or Red alerts.

### Insight

Higher alert levels are issued only when earthquakes are expected to cause significant damage or pose substantial risks to nearby populations.

---

# 🛠️ Tools & Technologies

- **Google Colab** — Data preprocessing and transformation
- **Microsoft Excel** — Data cleaning and formatting
- **Microsoft Power BI** — Interactive dashboard development

---

# 📌 Key Insights

- Oceania experienced the highest number of recorded earthquake events.
- Earthquakes are primarily concentrated along tectonic plate boundaries.
- Most recorded earthquakes did not generate tsunami warnings.
- Earthquake depth varies considerably across continents.
- No strong relationship exists between earthquake depth and magnitude.
- Interactive filters allow users to explore earthquakes by continent, country, and alert level.

---


⭐ **If you found this project helpful, consider giving the repository a star!**
