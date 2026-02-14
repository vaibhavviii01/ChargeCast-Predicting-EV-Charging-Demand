# ChargeCast-Predicting-EV-Charging-Demand

ChargeCast is an advanced time-series forecasting solution designed to optimize Electric Vehicle (EV) charging infrastructure and operations. By predicting when and where energy demand will spike, ChargeCast helps operators reduce station congestion and assists utilities in managing grid load uncertainty.

# 🚀 Project Overview
As EV adoption soars, existing charging infrastructure often struggles to keep pace, leading to long queues at some stations while others remain idle. ChargeCast addresses this by transforming unpredictable historical charging patterns into actionable foresight.

**Objective:** Build and evaluate forecasting models to predict daily EV-charging energy demand.

**Data Source:** 11 years (2011–2021) of real-world charging session data from Palo Alto’s open EV-station dataset.

**Key Impact:** Targeted a 35% increase in forecast accuracy over baseline models, potentially boosting station utilization from 65% to 90%.

# 🛠️ Tech Stack & Methodology

**Data Preprocessing:** Cleaned and aggregated ~260,000 charging records into daily total energy consumption (kWh).

**Exploratory Data Analysis (EDA):** Identified significant trends, including a 2100% growth in daily usage between 2011 and 2019.

**Forecasting Models:**

**ARIMA/SARIMAX:** Effective for capturing long-term trends and seasonality.

**XGBoost:** A machine learning approach used for complex demand shifts and high-volatility patterns.

**Validation:** Models were validated through rigorous backtesting to compare accuracy across different time horizons.

# 📊 Key Insights

**Volatility:** Average daily consumption was ~642 kWh but with high variance (~491 kWh), proving that static planning is ineffective for EV networks.

**Growth:** Daily energy usage rose from 54 kWh/day in 2011 to a peak of 1,198 kWh/day in 2019 before pandemic-related shifts occurred.

**SaaS Integration:** The project includes UI/UX wireframes for a dashboard featuring real-time peak alerts, geographic demand heatmaps, and maintenance scheduling tools.
