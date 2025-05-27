# Demand Forecasting in the CPG Industry (Prophet vs ARIMA)

## 🔍 Problem Statement
In the CPG space, poor demand forecasting leads to inventory imbalances, stockouts, and missed sales opportunities. This project addresses a core business challenge: **predicting daily product demand for the next 90 days** to enable better inventory planning and operational decisions.

---

## 🧠 Objective
To simulate real-world CPG sales data and compare two time series forecasting models—**Facebook Prophet** and **ARIMA**—on their ability to predict future demand patterns and inform business decisions.

---

## 🛠️ Methodology

### 1. **Data Simulation**
- Generated 2 years of synthetic daily sales data (2023–2024) with built-in seasonality, noise, and trend shifts.

### 2. **Modeling Approaches**
| Model | Description | Strength |
|-------|-------------|----------|
| **Facebook Prophet** | Captures seasonality, trend shifts, and uncertainty bands | Best for planning during holidays, promotions, or seasonal shifts |
| **ARIMA** | A classic statistical model for short-term trend continuation | Best for stable products without volatile sales patterns |

### 3. **Forecast Horizon**
- Next 90 days (Jan–March 2025)

### 4. **Evaluation Approach**
- Visual comparison of model behavior
- Focus on interpretability and applicability to business use cases

---

## 📊 Key Insights

- **Prophet** accurately captured the seasonality and upward demand trend, suggesting rising demand in early 2025.
- **ARIMA**, by contrast, projected a flat forecast, indicating it may miss trend shifts if not tuned properly.
- For CPG use cases involving **promotions, seasonality, or launch cycles**, **Prophet is the better tool** for informing production and inventory strategies.

---

## 📈 Business Impact

- **Improved inventory planning**: Anticipate demand spikes and avoid costly overstocking or stockouts.
- **Better campaign timing**: Align promotions with forecasted demand surges.
- **Operational agility**: Empower supply chain and logistics teams with forward-looking insights.

---

## 📁 Output Files
- `prophet_forecast.csv`: Daily demand forecast with confidence intervals
- `arima_forecast.csv`: 90-day ARIMA forecast output

--

---

## 🚀 Next Steps
- Integrate real CPG data
- Layer in marketing spend or holidays
- Calculate error metrics (MAE, RMSE) to quantify model accuracy
