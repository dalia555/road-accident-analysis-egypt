# Road Accident Analysis in Egypt

## Overview

This project analyzes road accident data in Egypt to identify patterns and trends in deaths and injuries across different governorates and years.

The project combines **Power Query, Power BI, Python, and Figma** to transform raw accident data into meaningful insights and interactive visualizations.

Time-series forecasting models were developed in Python and compared to forecast deaths and injuries for 2026. The resulting forecast charts were then integrated into the Power BI dashboard.

> Every data point represents a real life, a family, and a story. Through better data analysis, we can better understand road accident patterns and support efforts toward safer roads.

---

## Project Objectives

The main objectives of this project are to:

- Clean and transform road accident data
- Analyze accident patterns across Egyptian governorates
- Compare accident trends across different years
- Analyze deaths and injuries
- Build an interactive Power BI dashboard
- Create meaningful visualizations from the data
- Develop and compare time-series forecasting models
- Forecast deaths and injuries for 2026
- Present the results through an interactive dashboard

---

## Data Preparation

The raw accident data was prepared using **Power Query**.

The data preparation process included:

- Data cleaning
- Data transformation
- Organizing and restructuring data
- Preparing data for analysis
- Creating a suitable dataset for visualization and forecasting

Power Query was used to ensure that the data was properly structured before being analyzed in Power BI and Python.

---

## Data Analysis

The project explores road accident data across Egypt with a focus on:

- Deaths
- Injuries
- Accident trends over time
- Governorate-level comparisons
- Yearly comparisons
- Historical patterns

The analysis was designed to make large amounts of accident data easier to understand through visualizations and interactive dashboard elements.

---

# Power BI Dashboard

The interactive dashboard was developed using **Microsoft Power BI**.

The dashboard allows users to explore accident data and interact with different views of the analysis.

## Dashboard Features

- 🎨 Customized Figma background
- 🌙 Dark and light mode
- 🔖 Bookmarks
- 🔍 Drill-through
- 📊 Drill-down
- 💬 Tooltips
- 🎛️ Slicers for interactive filtering
- 🧭 Navigation buttons
- 🗺️ Custom map
- 📐 DAX measures
- 📈 Forecast visualizations

---

## Dashboard Design

The dashboard uses a customized visual design created with **Figma** and integrated into Power BI.

Both dark and light dashboard themes were implemented to provide different viewing experiences.

Navigation buttons and bookmarks allow users to move between different dashboard views.

---

## Interactive Analysis

Power BI interactive features allow users to explore the data at different levels of detail.

### Slicers

Slicers allow users to filter the dashboard based on available dimensions such as:

- Year
- Governorate
- Accident-related categories

### Drill-down

Drill-down allows users to explore data at different levels of the available hierarchy.

### Drill-through

Drill-through provides access to more detailed information from selected data points.

### Tooltips

Tooltips provide additional information when users interact with dashboard visuals.

### Bookmarks

Bookmarks allow predefined dashboard views and states to be saved and accessed easily.

---

# Forecasting

Time-series forecasting was performed using **Python**.

Three forecasting models were developed and compared:

1. **ETS (Exponential Smoothing)**
2. **Seasonal Naïve**
3. **SARIMA**

The models were evaluated using forecasting performance metrics.

In this experiment, **ETS produced the lowest error** and was selected for forecasting deaths and injuries for 2026.

---

## Forecasting Workflow

The forecasting process followed these steps:

```text
Historical Accident Data
          ↓
     Data Cleaning
          ↓
    Data Preparation
          ↓
     Python Analysis
          ↓
   Model Development
          ↓
 ┌────────┼─────────┐
 ↓        ↓         ↓
 ETS   Seasonal   SARIMA
       Naïve
 └────────┼─────────┘
          ↓
   Model Comparison
          ↓
      ETS Selected
          ↓
    2026 Forecast
          ↓
 Forecast Charts
          ↓
    Power BI Dashboard
