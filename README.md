# Time Series Methods

This project compares a diverse set of popular time series forecasting methods on air quality data to evaluate their performance and determine which approach yields the most accurate predictions.

## Objective

To analyze and forecast air quality trends using various time series models, and compare their effectiveness in terms of accuracy, interpretability, and computational efficiency.

## Methods Compared

- **Prophet**: A robust additive model for time series forecasting.
- **Lasso Regression**: A linear model with L1 regularization for feature selection.
- **LightGBM**: A gradient boosting framework that uses tree-based learning algorithms.
- **LSTM (Long Short-Term Memory)**: A type of recurrent neural network well-suited for sequential data.

## Dataset

The dataset used includes air quality measurements over time, such as pollutant concentrations. It is preprocessed and formatted for compatibility with each model.

## File Structure

- `STAT412_Final.ipynb`: Main notebook containing data preprocessing, model training, evaluation, and visualizations [2](https://github.com/PPratt04/Time_Series_Methods/blob/main/STAT412_Final.ipynb).
- `delhi_air_quality.csv`: Air quality dataset.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/PPratt04/Time_Series_Methods.git
   cd Time_Series_Methods
   ```

2. Install dependencies:
   ```bash
   pip install prophet
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook STAT412_Final.ipynb
   ```

## Results

Each model is evaluated using metrics such as MSE, R^2, and MAE. Visualizations are provided to compare predicted vs. actual values and highlight strengths and weaknesses of each method.

## Author

**Parker Pratt**  
For questions or contributions, feel free to open an issue, pull request, or contact me through GitHub, Handshake, LinkedIn, or email.
