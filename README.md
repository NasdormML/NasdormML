<h1 align="center">Hi, I’m Herman 👋</h1>

<p align="center">
  <strong>Data Scientist focused on time-series forecasting, financial analytics, and production-oriented ML.</strong>
</p>

<p align="center">
  <a href="mailto:nasdorm.ml@inbox.ru"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Email" /></a>
  <a href="https://t.me/Nasdorm"><img src="https://img.shields.io/badge/Telegram-@Nasdorm-26A5E4?style=flat-square&amp;logo=telegram&amp;logoColor=white" alt="Telegram" /></a>
  <a href="https://github.com/NasdormML"><img src="https://img.shields.io/badge/GitHub-NasdormML-181717?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub" /></a>
</p>

I build forecasting systems end to end—from reliable data collection and time-aware preprocessing to model training, experiment tracking, APIs, and containers. My main interests are **financial time series**, **demand forecasting**, and **reproducible MLOps**.

---

## 🚀 Featured Project — [Moex_predict](https://github.com/NasdormML/Moex_predict)

**Moex_predict** is a modular, five-step closing-price forecasting system for Moscow Exchange equities such as **SBER, GAZP, and ROSN**.

> **In plain English:** it turns market history and external context into a short-term price outlook, then makes the forecast available through a REST API.

### 📈 Published result

**Best published SBER result: 0.90% MAPE**, improved from **1.20%**—a **25% relative reduction in average percentage error** in the [v1.5 experiment](https://github.com/NasdormML/Moex_predict/releases/tag/v1.5.0).

<details>
<summary><strong>Technical highlights</strong></summary>

<br>

| Area | Implementation |
|---|---|
| **Data pipeline** | MOEX ISS pagination, retries, local caching, market-index data, and USD/RUB context |
| **Feature engineering** | Returns, volatility, lag features, RSI, MACD, Bollinger Bands, and ATR |
| **Models** | Attention-LSTM, TCN, and Transformer encoder models for multi-step forecasting |
| **Training** | Hydra experiment configs, Optuna tuning, Huber loss, AdamW, early stopping, pruning, and gradient clipping |
| **Experiment tracking** | MLflow runs plus versioned model, scaler, and metadata artifacts |
| **Model lifecycle** | Performance monitoring and staleness-based retraining logic |
| **Serving** | FastAPI endpoints for training, prediction, model inventory, and health checks |
| **Delivery** | Docker Compose plus unit and integration tests |

</details>

**Why it matters:** this is not only a forecasting notebook. It covers the full ML lifecycle—from raw market data to a reproducible, API-served prediction system.

[View repository →](https://github.com/NasdormML/Moex_predict)

---

## 🧩 Other Project

### [Store Sales Forecasting](https://github.com/NasdormML/Store_Sales_Forecasting)

End-to-end retail demand forecasting with **XGBoost**, **Optuna**, and time-aware validation.

- Achieved **RMSLE 0.75094** on the Kaggle test set
- Improved over moving-average and linear-regression baselines by **15%**
- Used lag, rolling, seasonal, and holiday features with `TimeSeriesSplit`
- Added Pytest coverage, Docker packaging, and CI/CD automation

[View repository →](https://github.com/NasdormML/Store_Sales_Forecasting)

---

## 🛠 Core Toolkit

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-0064A5?style=flat-square&logo=xgboost&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Hydra](https://img.shields.io/badge/Hydra-89B8CD?style=flat-square&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-3F4F75?style=flat-square&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## 🔭 Current Focus

Probabilistic forecasting, uncertainty estimation, and reinforcement learning for data-driven decision systems.

---

## 📬 Contact

- **Email:** [nasdorm.ml@inbox.ru](mailto:nasdorm.ml@inbox.ru)
- **Telegram:** [@Nasdorm](https://t.me/Nasdorm)

[![Codewars](https://www.codewars.com/users/Nasdorm/badges/small)](https://www.codewars.com/users/Nasdorm)
