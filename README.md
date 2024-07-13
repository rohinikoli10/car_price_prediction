## Introduction

Predicting the price of used cars can help buyers and sellers make informed decisions. This project leverages machine learning techniques to create an accurate price prediction model.

## Data Preprocessing

Data preprocessing steps include:
- Handling missing values
- Removing duplicates
- Converting categorical variables to numerical values
- Feature scaling
- Handling outliers
- Feature engineering (e.g., calculating car age)

## Evaluation

The model was evaluated using the following metrics:
- R-squared
- Mean Squared Error (MSE)

## Results

- **Training R-squared:** 1.0
- **Testing R-squared:** 1.0
- **Cross-validation R-squared scores:** [1.0, 1.0, 1.0, 1.0, 1.0]
- **Mean Cross-validation MSE:** 8.189269170223442e-24

These results suggest that the model generalizes well to unseen data.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/rohinikoli10/car_price_prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd car_price_prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the data preprocessing script:
    ```bash
    python preprocess_data.py
    ```
2. Train the model:
    ```bash
    python train_model.py
    ```
3. Evaluate the model:
    ```bash
    python evaluate_model.py
    ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

