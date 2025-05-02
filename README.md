
# Climate Change Impact on Agriculture Dashboard and Presentation

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)](#)

A data-driven exploration of how climate change affects agricultural productivity across major farming regions using interactive Power BI dashboards and a comprehensive PowerPoint presentation.

---

## 📌 Table of Contents

- [🔍 Project Overview](#-project-overview)
- [🎯 Objectives](#-objectives)
- [📂 Repository Structure](#-repository-structure)
- [💾 Data](#-data)
- [⚙️ Technologies & Tools](#️-technologies--tools)
- [🚀 Getting Started](#-getting-started)
- [📊 Dashboard Walkthrough](#-dashboard-walkthrough)
- [📽 Presentation](#-presentation)
- [🛠 Methodology](#-methodology)
- [📈 Key Findings](#-key-findings)
- [⚠️ Limitations & Improvements](#️-limitations--improvements)
- [💡 Recommendations](#-recommendations)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📞 Contact](#-contact)

---

## 🔍 Project Overview

Climate change poses significant challenges to global food security. This project analyzes historical climate and agricultural data to quantify the impact of changing temperature and precipitation patterns on crop yields. An interactive Power BI dashboard enables stakeholders to explore regional trends, correlations, and economic implications, while a detailed PowerPoint presentation summarizes methodology, insights, and recommended strategies.

## 🎯 Objectives

- Examine how temperature and precipitation changes influence crop yields over time.
- Identify the most vulnerable regions and crop types.
- Quantify the economic impact of yield fluctuations.
- Provide actionable recommendations for sustainable agricultural practices.

## 📂 Repository Structure

```plaintext
├── data/
│   ├── climate_agri_data.csv       # Raw CSV dataset with climate and yield variables
│   └── README.md                   # Dataset description and schema
├── dashboard/
│   └── Climate_Change_Impact_on_Agriculture_Dashboard.pbix  # Power BI report file
├── presentation/
│   └── Presentation_Climate_Change_Impact_on_Agriculture.pptx  # PowerPoint slides
├── LICENSE
└── README.md                       # Project overview and instructions
```

## 💾 Data

- **Source**: Collected from global agricultural databases and climate monitoring agencies.
- **Contents**: 10 countries, 10 crop types, 5 adaptation strategies, and corresponding climate metrics (temperature, precipitation).
- **Format**: CSV files located in the `data/` folder.
- **Schema**:
  | Column               | Type    | Description                                  |
  |----------------------|---------|----------------------------------------------|
  | Country              | String  | Country name                                 |
  | Year                 | Integer | Observation year                             |
  | Crop_Type            | String  | Type of crop                                 |
  | Yield_MetricTons     | Float   | Crop yield (metric tons)                     |
  | Temperature_C        | Float   | Annual average temperature (°C)              |
  | Precipitation_mm     | Float   | Annual total precipitation (mm)              |
  | Economic_Value_USD   | Float   | Economic value of yield (USD)                |
  | Adaptation_Strategy  | String  | Applied agricultural adaptation strategy     |

## ⚙️ Technologies & Tools

- **Power BI**: Interactive dashboard creation and data visualization.
- **Microsoft PowerPoint**: Presentation of findings and recommendations.
- **Git & GitHub**: Version control and repository hosting.

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Ibnbuba-A360/Climate_Change_Impact_on_Agriculture.git
   cd Climate_Change_Impact_On_Agriculture
   ```
2. **Explore the data**:
   - Inspect CSV files in the `data/` folder.
3. **Open the dashboard**:
   - Launch Power BI Desktop and open `dashboard/Climate_Change_Impact_on_Agriculture_Dashboard.pbix`.
4. **View the presentation**:
   - Open `presentation/Presentation_Climate_Change_Impact_on_Agriculture.pptx` in PowerPoint.

## 📊 Dashboard Walkthrough

1. **Overview Page**: Key metrics and year-over-year trends.
2. **Regional Analysis**: Compare crop yields and climate variables by country.
3. **Crop-specific Insights**: Drill down into individual crop performance.
4. **Economic Impact**: Visualize financial losses or gains linked to yield changes.
5. **Correlation Analysis**: Scatterplots and heatmaps showing relationships between climate variables and yield.

## 📽 Presentation

The PowerPoint deck summarizes:
- Project background and problem statement
- Data sources and cleaning steps
- Analytical methodology
- Major insights with charts exported from Power BI
- Limitations, improvements, and strategic recommendations

## 🛠 Methodology

1. **Data Cleaning**: Handled missing values, outliers, and standardized units.
2. **Data Modeling**: Created relationships between climate and yield tables in Power BI.
3. **Visualization**: Designed interactive visuals (bar charts, line graphs, scatterplots).
4. **Statistical Analysis**: Computed correlation coefficients and trend lines.

## 📈 Key Findings

- Nigeria and China show the highest resilience in yield growth despite rising temperatures.
- Wheat and rice yields are most sensitive to precipitation variability.
- Regions without adaptation strategies suffer up to 20% greater yield loss.

## ⚠️ Limitations & Improvements

- **Limitations**:
  - Aggregate data may mask local seasonal effects.
  - Lack of soil quality and socio-economic variables.
- **Future Improvements**:
  - Incorporate finer-grained regional and seasonal data.
  - Integrate soil health and market access indicators.
  - Apply machine learning models for predictive forecasting.

## 💡 Recommendations

- Invest in drought-resistant seed varieties.
- Enhance water management infrastructure.
- Promote diversified cropping and organic farming methods.
- Support farmer training on climate-smart agriculture.

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## 📞 Contact

- **Ibrahim Abubakar Buba**
- Email: ibnbuba.ai@gmail.com
- GitHub: [Ibnbuba-A360](https://github.com/Ibnbuba-A360)

---

*Empowering resilient agriculture through data-driven insights.*
