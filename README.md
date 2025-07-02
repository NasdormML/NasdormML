# 👋 Hi, I’m Herman
![CodeWarsBagde](https://www.codewars.com/users/Nasdorm/badges/large)

I’m a **Junior Data Scientist** passionate about time series forecasting and financial market analytics. I build end‑to‑end ML pipelines—from data ingestion and feature engineering to model deployment—for real‑world problems on MOEX.

---

## 🌟 Spotlight: Moex\_predict

[**Moex_predict**](https://github.com/NasdormML/Moex_predict) is my flagship project, forecasting Moscow Exchange blue‑chip stocks (SBER, GAZP, LKOH) with cutting‑edge Transformer architectures and rigorous hyperparameter tuning.

* **Performance:** MAPE **0.90%**, MaxErr **24.7 RUB** on hold‑out SBER data
* **Features engineered:** RSI, MACD, Bollinger Bands, ATR, log‑returns, volatility, SMA
* **Modeling:** Encoder‑only Transformer with positional embeddings, ensemble strategies
* **Optimization:** Optuna study targeting 95th percentile error
* **Data handling:** Robust MOEX API pagination, caching, and preprocessing
* **Deployment-ready:** FastAPI endpoint serving live predictions

---

## 🔧 Tech Stack & Badges

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-EE4C2C?logo=pytorch\&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-3.0-000000?logo=optuna\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.2-F7931E?logo=scikit-learn\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458?logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.2.5-013243?logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10-11557C?logo=matplotlib\&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-2.31-000000?logo=python-requests\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-009688?logo=fastapi\&logoColor=white)

---

## 🏆 Key Projects

### 🎯 Moex_predict

**Forecasting MOEX blue-chip stocks** (SBER, GAZP, ROSN) using Transformer models with advanced feature engineering and hyperparameter tuning.

* **Performance:** MAPE **0.90%**, MaxErr **24.7 RUB** (SBER)
* **Features:** RSI, MACD, Bollinger Bands, ATR, log-returns, volatility, SMA
* **Model & Optimization:** Encoder-only Transformer, Optuna tuning on 95th percentile error, ensembling
* **Deployment:** FastAPI service with Docker

### 🔢 Store Sales Forecasting

**Retail sales forecasting** for a major retailer using XGBoost and Optuna.

* **Performance:** RMSLE **0.7509** (Top 450 on Kaggle)
* **Tech:** Python, XGBoost, Optuna, TimeSeriesSplit
* **Impact:** Improved demand planning and inventory management

---

## 🚀 My Workflow

1. **Data Ingestion & Cleaning**: MOEX API pagination, missing‑value handling, caching raw data
2. **Feature Engineering**: Technical indicators and statistical metrics for robust signal extraction
3. **Model Development**: Transformer encoder with attention, custom positional encoding, fine‑tuned via Optuna
4. **Ensembling & Calibration**: Combine multiple model seeds and architectures, quantile‑based aggregation
5. **Evaluation & Monitoring**: Time‑series cross‑validation, custom loss for tail‑error minimization
6. **Deployment**: FastAPI microservice for real‑time inference, Dockerized for scalability

---

## 🎯 Next Steps

* Dive into **Temporal Fusion Transformers (TFT)** for multi‑horizon forecasting
* Experiment with **Informer** and **Reformer** for long sequence efficiency
* Integrate **real‑time market data streams** and sentiment features
* Expand ensemble with **Gaussian Process** and **Bayesian Neural Nets** for uncertainty quantification

---

## 📬 Let’s Connect

* ✉️ Email: [nasdorm.ml@inbox.ru](mailto:nasdorm.ml@inbox.ru)
* 💬 Telegram: [@Nasdorm](https://t.me/Nasdorm)
* 🐙 GitHub: [github.com/NasdormML](https://github.com/NasdormML)

---

> “Perfection is not attainable, but if we chase perfection we can catch excellence.” – Vince Lombardi
