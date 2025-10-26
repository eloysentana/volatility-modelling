# Volatility Modelling and Regime Classification

This project is an understanding exercise on modern approaches to **volatility estimation and regime classification** in financial markets, focusing on:

* **GARCH(1,1) models** for volatility clustering
* **Hypothesis testing** for return distributions
* **Volatility forecasting** (blind forecasts, daily retraining, train-and-run approaches)
* **Comparison with VIX**
* **Regime classification methods**: Hidden Markov Models (HMM) and Markov Switching Autoregressive Models (MSAR)

The PDF file containing the explanations, plots and results is this [Volatility Modelling and Regime Classification Methods.pdf](Volatility%20Modelling%20and%20Regime%20Classification%20Methods.pdf)


The project is designed as a **learning notebook**, combining implementation, testing, and reflection on the practical behavior of these models with real financial data (S&P 500, Yahoo Finance).

## 📊 Key Results

* **Returns are not normally distributed** (heavy tails, skewness, high kurtosis).
* **GARCH(1,1)** captures volatility clustering but performs poorly for long-term forecasting.
* **Daily retraining** improves short-term forecasts but is computationally expensive.
* **Regime classification** with HMM/MSAR successfully identifies volatility regimes around key crises (2008, COVID-19, inflation shocks).


## ⚠️ Disclaimer

This project is a **personal learning exercise**. It has not been supervised, checked, or commented on by anyone but me.

If you have any questions, suggestions, or feedback, please feel free to reach out to me at **esentanasegui@gmail.com**.
