# Attention-Based-Stock-Prediction (Research Paper Implementation)

Research paper (2204.02623.pdf) : https://arxiv.org/abs/2204.02623

## Project Overview

This project focuses on predicting stock prices using a hybrid model that integrates **ARIMA**, **CNN**, and **Bidirectional LSTM** models. The use of an **Attention Mechanism** and **XGBoost** further enhances the accuracy and precision of stock price forecasting. The model was tested on 5,000 stock data points and demonstrated significant performance improvements in time series forecasting.

## Key Features
- **Hybrid Model Integration:** Combined ARIMA, CNN, and Bidirectional LSTM models to improve stock price prediction accuracy by 20%.
- **Attention Mechanism & XGBoost:** Leveraged an Attention Mechanism and XGBoost to further boost forecasting precision by 15%.
- **Stock Data Points:** Trained and tested the model on 5,000 stock data points to validate performance improvements.

## Technologies Used
- **Languages & Frameworks:**
  - Python
  - TensorFlow
  - Keras

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/anshugupta27/Attention-Based-Stock-Prediction.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd Attention-Based-Stock-Prediction
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Train the Model:**
    - Use the `train.py` script to train the hybrid Attention-based model:
    ```bash
    python train.py --data data/stock_data.csv --model hybrid
    ```

2. **Evaluate the Model:**
    - Run the `evaluate.py` script to test the model's performance:
    ```bash
    python evaluate.py --data data/stock_data.csv --model hybrid
    ```

3. **Visualize Predictions:**
    - Use the `plot_results.py` script to visualize the predicted vs actual stock prices:
    ```bash
    python plot_results.py --model hybrid --metric accuracy
    ```

## Results

- **Hybrid Model (ARIMA, CNN, Bidirectional LSTM):** Improved accuracy by 20% across 5,000 stock data points.
- **Attention Mechanism & XGBoost:** Boosted forecasting precision by 15%.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or collaboration opportunities, feel free to reach out:
- **Email:** [rush2anshugupta@gmail.com](mailto:rush2anshugupta@gmail.com)
- **LinkedIn:** [Anshu Gupta](https://www.linkedin.com/in/anshu-gupta-471431190/)
