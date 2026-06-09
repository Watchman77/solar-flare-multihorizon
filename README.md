# solar-flare-multihorizon
# Evolution-Aware Solar Flare Prediction

This repository contains the code, notebooks, result tables, and reproducibility materials for a multi-horizon M/X-class solar flare prediction study. The project investigates evolution-aware temporal modelling of solar active regions using SHARP magnetic parameters, engineered magnetic-evolution features, and GOES-derived flare-history memory.

The study evaluates 3-hour, 24-hour, and 72-hour forecasting horizons using LSTM, BiLSTM, Decomposition-LSTM, Transformer-based models, physics-regularised DLSTM, and ensemble strategies. Model thresholds are selected using validation data only, and performance is assessed using TSS, HSS, ROC-AUC, PR-AUC, precision, recall, F1-score, bootstrap confidence intervals, and McNemar tests.

The repository is organised to support reproducibility of the final manuscript results, including cleaned notebooks for each forecasting horizon and harmonised cross-horizon analysis outputs.
