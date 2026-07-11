# Urban Time Series Comparison

A benchmark project comparing machine learning and deep learning models for urban time series forecasting.

This repository evaluates the performance of **Random Forest**, **XGBoost**, **LSTM**, and **Transformer** models on multiple urban datasets, including **traffic flow**, **energy consumption**, and **temperature**. The goal is to provide a fair and reproducible comparison of traditional machine learning and deep learning approaches for forecasting urban metrics.

---

## Objectives

- Compare the predictive performance of different forecasting models.
- Evaluate models across multiple types of urban time series.
- Analyze prediction accuracy and computational cost.
- Provide reproducible experiments for research purposes.

---

## Models

The following algorithms are evaluated:

- Random Forest
- XGBoost
- LSTM (Long Short-Term Memory)
- Transformer

---

## Datasets

The experiments are conducted on publicly available datasets representing different urban domains:

- 🚗 Traffic Flow
- ⚡ Energy Consumption
- 🌡️ Temperature

Additional datasets may be added in future versions.

---

## Evaluation Metrics

Models are compared using standard regression metrics:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)
- R² Score

Computational performance is also analyzed through:

- Training time
- Inference time

---

## Project Structure

```
urban-time-series-comparison/
│
├── data/
│   ├── traffic/
│   ├── energy/
│   └── temperature/
│
├── notebooks/
│
├── src/
│   ├── preprocessing/
│   ├── models/
│   ├── evaluation/
│   └── visualization/
│
├── experiments/
│
├── results/
│   ├── figures/
│   ├── metrics/
│   └── tables/
│
├── paper/
│
├── requirements.txt
└── README.md
```

---

## Technologies

- Python 3.12
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- TensorFlow / Keras or PyTorch
- Matplotlib
- Seaborn

---

## Research Questions

This project aims to answer the following questions:

- Which model achieves the highest forecasting accuracy?
- Does model performance depend on the type of urban data?
- Are deep learning models worth their computational cost?
- Which approach provides the best balance between accuracy and efficiency?

---

## Citation

If you use this repository in your research, please cite the corresponding paper (coming soon).
