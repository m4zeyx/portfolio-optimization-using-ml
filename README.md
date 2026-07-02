# portfolio-optimization-using-ml
ML-based portfolio optimization: benchmarking SVR/Random Forest return forecasts against ARIMA, fed into a CVaR allocation engine across 7 futures markets (2013–2025).


Systematic portfolio strategy comparing machine learning return forecasts (SVR, Random Forest) against a linear time series baseline (ARIMA) for 7 liquid futures across equities, rates, and commodities. Forecasts feed a CVaR (90%) allocation engine with realistic constraints (no shorting, position caps, transaction costs). Evaluated via static and rolling-window retraining on 12 years of weekly data (2013–2025). Best strategy (RF-Rolling) achieved a 0.75 Sharpe ratio with 16% max drawdown, outperforming ARIMA and matching S&P 500 smoothness at lower risk.
