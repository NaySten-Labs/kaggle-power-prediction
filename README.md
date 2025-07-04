# Hill of Towie Wind Turbine Power Prediction

**Repository for a solution to the Kaggle competition: [Hill of Towie Wind Turbine Power Prediction](https://www.kaggle.com/competitions/hill-of-towie-wind-turbine-power-prediction/overview)**

## Competition Overview

The goal of this Kaggle challenge is to **predict the Active Power output of a target wind turbine at the Hill of Towie wind farm**, using historical data from nearby turbines. Accurate power prediction is crucial for optimizing wind farm operations and integrating renewable energy into the grid[^1][^2].

## Dataset

- The dataset is derived from the **Hill of Towie wind farm open dataset**, containing several years of operational data from multiple turbines[^3][^4].
- Features include turbine-level measurements (e.g., wind speed, direction, temperature) and timestamps.
- The target variable is the **Active Power** of a specific turbine[^2][^3].


## Solution Approach

- **Data Preprocessing:** Handling missing values, feature engineering, and normalization.
- **Modeling:** Machine learning regression models (e.g., Random Forest, Gradient Boosting, or Neural Networks) to predict turbine power output.
- **Evaluation:** Model performance is assessed using metrics such as RMSE, as per competition guidelines[^1][^2].


## Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/NaySten-Labs/kaggle-power-prediction
cd hill-of-towie-power-prediction
```

2. **Install dependencies:**

```bash
uv sync
```

3. **Download the competition data** from Kaggle and place it in the `data/` directory.
4. **Run the training script:**

```bash
python train.py
```

5. **Generate predictions for submission:**

```bash
python predict.py
```


## References

- [Kaggle Competition Page][^1]
- [Hill of Towie Open Dataset][^4]


## License

This project uses the **CC-BY-4.0** open data license as per the dataset terms[^4].

*For questions or contributions, please open an issue or submit a pull request.*

<div style="text-align: center">⁂</div>

[^1]: https://kaggle.com/competitions/hill-of-towie-wind-turbine-power-prediction

[^2]: https://www.kaggle.com/competitions/hill-of-towie-wind-turbine-power-prediction/rules

[^3]: https://www.kaggle.com/competitions/hill-of-towie-wind-turbine-power-prediction/data

[^4]: https://zenodo.org/records/14870023

[^5]: https://www.kaggle.com/competitions/hill-of-towie-wind-turbine-power-prediction

[^6]: https://www.kaggle.com/code/gabecalvo/hill-of-towie-power-prediction-getting-started/input

[^7]: https://www.wedowind.ch/blog/new-power-prediction-challenge-from-res

[^8]: https://www.linkedin.com/posts/conor-malone-07785843_hill-of-towie-wind-turbine-power-prediction-activity-7329150250122645504-tiUC

[^9]: https://openreview.net/pdf?id=bkfC3o2CiL

[^10]: https://arxiv.org/pdf/2307.14675.pdf

[^11]: https://www.gem.wiki/Hill_Of_Towie_wind_farm

[^12]: https://community.wedowind.ch/posts/83999924

[^13]: https://www.kaggle.com/c/predict-the-wind-speed-at-a-wind-turbine/

[^14]: https://arxiv.org/pdf/2502.14527.pdf

[^15]: https://github.com/SmartPracticeschool/SBSPS-Challenge-1090-Predicting-the-energy-output-of-wind-turbine-based-on-weather-condition

[^16]: https://www.nrel.gov/docs/fy20osti/76102.pdf

[^17]: https://arxiv.org/abs/2307.14675

[^18]: https://www.kaggle.com/competitions/wind-turbine-predictive-maintenance/data

[^19]: https://kaggle.com/competitions/mle-2023

[^20]: https://github.com/SmartPracticeschool/SBSPS-Challenge-4909-Predicting-the-energy-output-of-wind-turbine-based-on-weather-condition

[^21]: https://www.kaggle.com/datasets/mubashirrahim/wind-power-generation-data-forecasting/code

