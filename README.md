# 📊 Analyzing Agricultural Productivity Across Indian States

## 🧭 Project Overview

This Power BI project offers a comprehensive visualization and analysis of agricultural productivity across Indian states. The dashboard utilizes variables such as rainfall, fertilizer usage, pesticide application, and cultivation area to identify productivity patterns and uncover actionable insights that support better agricultural decision-making.

## 🎯 Objectives

- Visualize agricultural performance metrics across Indian states.
- Analyze the influence of rainfall, fertilizer, and pesticide usage on crop production and yield.
- Understand seasonal trends and regional disparities.
- Enable dynamic and interactive exploration through intuitive slicers and filters.

## 📂 Dataset Description

The dataset provided in CSV format includes details on crop production, area, rainfall, fertilizer and pesticide usage, and yield. Each record represents a crop-season-state-year combination with its corresponding metrics.

### 🧾 Column Descriptions

- **Crop**: Name of the crop (e.g., Rice, Wheat, Maize)
- **Crop_Year**: Year of cultivation
- **Season**: Cropping season (e.g., Kharif, Rabi, Whole Year)
- **State**: Indian state where the crop is cultivated
- **Area**: Area under cultivation (in hectares)
- **Production**: Crop production output (in metric tons)
- **Annual_Rainfall**: Annual rainfall received (in mm)
- **Fertilizer**: Fertilizer used (in kg)
- **Pesticide**: Pesticide used (in kg)
- **Yield**: Productivity per hectare (Production ÷ Area)

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** – Dashboard creation and report development
- **Power Query Editor** – Data transformation and modeling
- **DAX (Data Analysis Expressions)** – Custom measures and KPIs
- **Microsoft Excel** – Dataset validation and basic preprocessing

## 📈 Dashboard Structure

1. **Overview Page**
   - Cards for key metrics: Avg Rainfall, Area, Fertilizer, and Pesticide
   - Stacked bar chart: Average Production by State
   - Stacked column chart: Average Yield by State

2. **Crop Production Page**
   - Line charts: Relationship between Rainfall and Production
   - Slicers for Crop and State to enable comparative trend analysis

3. **Fertilizer Page**
   - Pie chart: Fertilizer usage by State
   - Donut chart: Fertilizer usage by Crop
   - Key Influencers visual: Factors impacting productivity
   - Table: Season-wise, crop-wise detailed data

## 🧠 Key Insights

- Rainfall and pesticide usage significantly influence crop yield.
- Northern states report higher wheat productivity during Rabi.
- Fertilizer usage does not always correlate with higher yields—highlighting inefficiencies.

## 🚀 Getting Started

1. Clone or download the repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Use interactive visuals and filters to explore the data and discover insights.

## 📌 Future Enhancements

- Integrate real-time weather data through APIs.
- Add drill-down to district-level granularity.
- Implement forecasting features for crop production.
- Publish and share insights via Power BI Service.

## 🤝 Contributing

Got ideas to improve the dashboard? Feel free to fork the repo, raise a pull request, or suggest enhancements via Issues!
