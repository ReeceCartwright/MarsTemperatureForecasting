# Martian Surface Temperature Forecasting

Predicting Martian surface temperature using machine learning and environmental data collected by NASA's Curiosity Rover.

---

## Overview

This project investigates the effectiveness of supervised machine learning models for forecasting short-term Martian surface temperature using historical weather observations from NASA's Rover Environmental Monitoring Station (REMS).

The complete machine learning workflow includes:

- Data preprocessing and cleaning
- Feature engineering using lagged temperature values
- Chronological train/test splitting for time-series prediction
- Model training and comparison
- Performance evaluation using multiple regression metrics
- Residual analysis and visualization

The objective was to determine which regression algorithm provides the most accurate predictions while maintaining a reproducible machine learning pipeline.

---

## Dataset

The dataset consists of approximately **17,500** environmental observations collected by the **Rover Environmental Monitoring Station (REMS)** aboard NASA's Curiosity rover.

The project focuses on predicting future surface temperature measurements using previous observations while preserving the chronological nature of the data.

---

## Machine Learning Models

Three supervised regression models were evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Each model was trained using identical preprocessing steps and evaluated using the same testing dataset for a fair comparison.

---

## Results

Model performance was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Coefficient of Determination (R²)
- Residual Analysis

Among the evaluated models, **Linear Regression produced the strongest overall performance**, demonstrating that recent Martian temperature observations contain significant predictive information for short-term forecasting.

---

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- Matplotlib

---

## Repository Structure

```
MarsTemperatureForecasting/
│
├── docs/
│   └── MLFinalReport.docx
│
├── notebook/
│   └── mars_temperature_forecasting.ipynb
│
├── data/
│
├── images/
│
├── README.md
└── .gitignore
```

---

## Repository Contents

| File | Description |
|------|-------------|
| `notebook/mars_temperature_forecasting.ipynb` | Complete machine learning workflow |
| `docs/MLFinalReport.docx` | Final technical report |
| `README.md` | Project overview and documentation |

---

## Project Context

This project was originally developed as the final project for the **Machine Learning** course in the Electrical Engineering program at **Texas State University**.

The repository has been expanded and organized as a professional portfolio project to demonstrate practical machine learning workflows, technical documentation, and software development practices.

---

## Future Improvements

Potential future enhancements include:

- Walk-forward time-series validation
- Hyperparameter optimization
- Additional feature engineering
- Baseline persistence model comparison
- Support Vector Regression (SVR)
- XGBoost regression
- Automated model comparison pipeline
- Interactive data visualizations
- Exporting figures for publication-quality documentation

---

## Authors

**Reece Cartwright**

Electrical Engineering Student  
Texas State University

Project completed in collaboration with **Leigh Dubcak**.

---

## License

This repository is currently provided for educational and portfolio purposes.
