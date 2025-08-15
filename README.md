# Road Accident Analysis Dashboard 📊🚗

This repository contains a comprehensive dashboard for analyzing road accident data, providing insights into various key trends, geographical factors, and environmental influences. The dashboard is designed to be interactive, allowing users to filter and explore data based on different parameters.

---

## 🗒️ Table of Contents
* [🚀 Features](#features)
* [📊 Data Overview](#data-overview)
* [📈 Dashboard Components](#dashboard-components)
    * [📋 Cards (Key Performance Indicators - KPIs)](#cards-key-performance-indicators---kpis)
    * [📉 Graphs and Charts](#graphs-and-charts)
    * [🎚️ Slicers / Filters](#slicers--filters)
    * [🖱️ Buttons / Navigation](#buttons--navigation)
* [🤝 Contribution](#contribution)
* [📄 License](#license)
* [📧 Contact](#contact)

---

## 🚀 Features

- **Key Trends Overview**: Get a quick summary of total accidents, casualties, accidents per day, average speed limit, and total vehicles.
- **Detailed Accident Analysis**: Dive deeper into accident distribution by speed limit, day of the week, and junction control.
- **Geographical & Environmental Factors**: Understand how weather conditions, road surfaces, lighting, and hazards contribute to accidents.
- **Accident Hotspot Map**: Visualize accident severity across different locations.
- **Interactive Slicers**: Filter data by accident date, junction details, accident severity, and urban vs. rural areas.

---

## 📊 Data Overview

The dashboard is powered by a dataset containing detailed records of road accidents. Key attributes within the dataset include:

- `Accident_Index`: Unique identifier for each accident.
- `Accident Date`: The date when the accident occurred.
- `Day_of_Week`: The day of the week the accident occurred (e.g., Wednesday).
- `Junction_Control`: Type of control at the junction.
- `Junction_Detail`: Further detail about the junction.
- `Accident_Severity`: The severity of the accident (e.g., Slight, Serious, Fatal).
- `Latitude` / `Longitude`: Geographical coordinates for the accident location.
- `Light_Conditions`: The lighting conditions at the time of the accident.
- `Local Authority (District)`: The local administrative district where the accident took place.
- `Carriageway_Hazards`: Any hazards present on the carriageway.
- `Number_of_Casualties`: Total number of casualties in the accident.
- `Number_of_Vehicles`: Total number of vehicles involved in the accident.
- `Police_Force`: The police force that recorded the accident.
- `Road_Surface_Conditions`: Conditions of the road surface.
- `Road_Type`: Type of road.
- `Speed_limit`: Speed limit on the road where the accident occurred.
- `Time`: The time of the accident.
- `Urban_or_Rural_Area`: Indicates if the accident occurred in an urban or rural setting.
- `Weather_Conditions`: Weather conditions at the time of the accident.
- `Vehicle_Type`: Type of vehicle involved.

---

## 📈 Dashboard Components

### 📋 Cards (Key Performance Indicators - KPIs)

The top section of the dashboard features several KPI cards that provide a high-level overview of critical metrics:

- **Total Accidents**: Overall number of recorded accidents.
- **Number of Casualties**: Total count of injuries or fatalities.
- **Accidents Per Day**: Average number of accidents occurring daily.
- **Average Speed Limit (km/h)**: Average recorded speed limit at accident locations.
- **Total Vehicles**: Total count of vehicles involved in accidents.

### 📉 Graphs and Charts

The dashboard utilizes various chart types to visualize accident data effectively:

- **No of Accidents by Speed_limit (Bar Chart)**: Bar chart illustrating the distribution of accidents across different speed limit ranges.
- **Accident Trends Per Month (Line and Bar Chart Combo)**: Combined chart displaying the count of accidents (bars) and the sum of casualties (line) over each month.
- **Count of Accident_Index by Day_of_Week (Donut Chart)**: Donut chart showing the percentage breakdown of accidents by the day of the week.
- **No of Accidents by Junction_Control (Bar Chart)**: Bar chart detailing the number of accidents based on the type of junction control.
- **Number of Accidents on Various Road Surfaces in Different Weather Conditions (Stacked Bar Chart)**: Stacked bar chart visualizing accident occurrences by road surface and weather conditions.
- **Accidents Hotspot By Severity (Map Visualization)**: Map visually representing accident hotspots, color-coded by severity (Fatal, Serious, Slight).
- **Top 5 Most Prone Vehicles As Per Road Type (Area Chart)**: Area chart showing the top 5 vehicle types involved in accidents on different road types.
- **Number of Accidents in Various Lighting Conditions (Donut Chart)**: Donut chart breaking down accidents by lighting conditions.
- **Number of Accidents Due to Various Hazards (Bar Chart)**: Bar chart displaying the count of accidents attributed to various hazards.

### 🎚️ Slicers / Filters

The dashboard includes several interactive slicers on the left sidebar for data filtering:

- **Accident Date (Date Range Slider)**: Allows users to select a specific date range.
- **Junction Details (Dropdown)**: Filters data based on specific junction types.
- **Accident Severity (Dropdown)**: Filters accidents by their severity level.
- **Urban vs Rural (Dropdown)**: Differentiates accidents occurring in urban or rural areas.

### 🖱️ Buttons / Navigation

The dashboard includes distinct navigation buttons to switch between analytical views:

- **"Road Accident Analysis Key Trends"**: Displays primary accident statistics and trends.
- **"Geographical and Environment Factors"**: Shows analyses related to environmental and locational impacts on accidents.
<img width="885" height="495" alt="image" src="https://github.com/user-attachments/assets/273bc3bf-264a-4995-bb1f-6f97cfbeca8f" />
<img width="880" height="495" alt="image" src="https://github.com/user-attachments/assets/ebf2c05f-3720-476f-aef8-06263d78ff9f" />

---

## 🤝 Contribution

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📧 Contact

For any inquiries or further information, please feel free to connect with me:

- **Name**: [Your Name]
- **Email**: your.email@example.com
- **GitHub**: github.com/your-username

