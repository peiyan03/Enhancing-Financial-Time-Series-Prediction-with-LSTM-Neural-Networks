# Enhancing Financial Time Series Prediction with LSTM Neural Networks

**Authors:** Peiyan Zou, Xi Zheng, Guanhao Chen  
**Instructors:** Antoine Jacquier, Lukas Gonon  
**Date:** September 26, 2024

## Overview
This project examines the use of ensemble Long Short-Term Memory (LSTM) networks to predict stock price movements, specifically within the Dow Jones Industrial Average (DJIA) constituent stocks, from January 1996 to August 2024. The goal is to refine the ensemble bidirectional LSTM model to improve prediction accuracy and to evaluate the profitability of an investment strategy based on these predictions.

## Key Contributions
- **LSTM Architecture:** We utilized a bidirectional LSTM model, leveraging its ability to capture long-term dependencies in time series data.
- **Ensemble Model:** An ensemble of LSTM models with different initializations was implemented to improve generalization and reduce overfitting.
- **Data:** Historical stock data from the DJIA, sourced from Yahoo Finance, was processed for daily returns and classified for binary prediction.
- **Portfolio Strategy:** A dynamic trading strategy was applied, where stocks with positive predictions were added to the portfolio and held for 10 days.

## Results
- **Prediction Accuracy:** The ensemble LSTM model achieved a prediction accuracy near 50%, consistent with previous studies.
- **Profitability:** The model demonstrated consistent growth in cumulative returns, particularly from 2012-2022, although fluctuations were observed in recent years.
- **Limitations:** The study highlights the need for further refinement in feature selection and the incorporation of additional data sources.

## Future Work
Further research will focus on improving feature selection, exploring higher-frequency data, and refining hyperparameters to enhance predictive accuracy and profitability.

## Report
For more detailed information, you can view the full report [here](./Team_1_Report.pdf).

## References
Key references include studies by Fjellström (2022), Fischer & Krauss (2018), and Hochreiter & Schmidhuber (1997), among others. A full list of references is provided in the report.
