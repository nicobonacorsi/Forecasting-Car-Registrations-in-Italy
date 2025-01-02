# 🚗 Forecasting Car Registrations in Italy

![Banner](https://example.com/car_forecasting_banner.png)

## 🔍 Project Overview

This repository focuses on forecasting monthly **car registrations in Italy** using a **SARIMAX model**. The project explores the impact of external factors such as COVID-19, government incentives, and working days on car registration trends.

### Key Highlights:
- Time series analysis with SARIMAX.
- Incorporation of external regressors for enhanced forecasting accuracy.
- Forecast for March 2024.

---

## 📂 Project Structure

- `data/`: Contains raw datasets and processed data files.
- `R CODE/`: R scripts for data analysis and forecasting.
- `results/`: Visualization outputs and the final report.

---

## 📊 Methodology

1. **Data Collection**:
   - Historical car registration data (`ITALIARIDOTTA.txt`).
   - Dummy variables (`covid` and `incentive`) for key events.
   - Monthly working days (`lavorativi.csv`).

2. **Model Training**:
   - SARIMAX model implemented in R.
   - Inclusion of regressors:
     - **`covid`**: Impact of COVID-19 (1 for affected months, 0 otherwise).
     - **`incentive`**: Effect of government incentives (1 for incentivized months, 0 otherwise).
     - **`working_days`**: Number of working days each month.

3. **Forecasting**:
   - Predict car registrations for March 2024.
   - Evaluate model performance with metrics (e.g., RMSE).

---

## 📈 Results

![Forecast Plot](https://example.com/forecast_plot.png)

The forecast indicates a potential increase in car registrations in March 2024, driven by:
- A recovery from COVID-19 disruptions.
- Seasonal patterns observed in historical data.
- Influence of working days and incentives.

---

## 🛠 How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/nicobonacorsi/Forecasting-Car-Registrations-in-Italy.git
   ```

2. **Navigate to the R code folder**:
   ```bash
   cd Forecasting-Car-Registrations-in-Italy/R\ CODE
   ```

3. **Run the forecasting script in R**:
   ```R
   source('forecasting_script.R')
   ```

---

## 📝 Examples

### Example: Effect of Incentives
![Incentives Effect](https://example.com/incentives_effect_plot.png)

---

## 🤝 Contributing

We welcome contributions! Feel free to:
- Open issues for discussions.
- Submit pull requests to improve the code or documentation.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 📫 Contact

For questions or collaboration opportunities, contact **Nicolò Bonacorsi**:
- 📧 [nicolobonacorsi@gmail.com](mailto:nicolobonacorsi@gmail.com)
- 🌐 [LinkedIn](https://linkedin.com/in/nicolobonacorsi)

---

Thank you for exploring this project! 🌟
