# Housing Price Prediction

This project predicts housing prices based on features such as house area, number of bedrooms, furnishing status, and additional amenities using various regression models.

---

## Project Overview
Housing price prediction is a critical task in the real estate industry, providing insights into property valuation and market trends. This project implements multiple regression techniques to model the relationship between housing features and their respective prices.

---

## Features
The dataset includes the following features:
- **Numerical Features**:
  - `area`: Size of the house (in square feet).
  - `bedrooms`, `bathrooms`: Number of bedrooms and bathrooms.
- **Binary Categorical Features**:
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`: Indicate presence (1) or absence (0).
- **Categorical Features**:
  - `furnishingstatus`: Indicates whether the house is furnished, semi-furnished, or unfurnished.
- **Target Variable**:
  - `price`: Price of the house.

---

## Models Implemented
1. **Simple Linear Regression**
2. **Multiple Linear Regression**
3. **Polynomial Regression**
4. **Random Forest Regression**
5. **Gradient Boosting Regression**

### Best Model:
Random Forest Regression achieved the highest accuracy with the following metrics:
- **R²**: 0.7562
- **Adjusted R²**: 0.6681
- **RMSE**: 924,032.93
- **MAE**: 702,105.80

---

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/KarthikKrishnadv/House-Price-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Housing-Price-Prediction
   ```


---

## Usage
1. Load the dataset into the project directory.
2. Run the Jupyter Notebook to train and evaluate models.
3. Modify hyperparameters or models in the code as needed.

---

## File Structure
- `Housing - Housing.csv`: Dataset file.
- `code.ipynb`: Main implementation notebook.
- `requirements.txt`: Required Python libraries.

---

## Evaluation Metrics
- **R²**: Coefficient of determination.
- **Adjusted R²**: Adjusted for the number of predictors.
- **RMSE**: Root Mean Squared Error.
- **MAE**: Mean Absolute Error.
- **MSE**: Mean Squared Error.

---

## Results
| Model                     | R²    | Adjusted R² | RMSE        | MAE         | MSE            |
|---------------------------|--------|-------------|-------------|-------------|----------------|
| Simple Linear Regression  | 0.2648 | 0.2495      | 1,604,554.46| 1,205,725.33| 2,574,595,014,383.65 |
| Multiple Linear Regression| 0.7498 | 0.6594      | 936,112.73  | 757,364.44  | 876,307,034,468.61 |
| Polynomial Regression     | 0.6287 | 1.3308      | 1,140,259.52| 815,491.74  | 1,300,191,768,217.60 |
| Random Forest Regression  | 0.7562 | 0.6681      | 924,032.93  | 702,105.80  | 853,836,849,172.09 |
| Gradient Boosting Regression | 0.7460 | 0.6543    | 943,176.47  | 783,566.18  | 889,581,847,840.14 |
| Ridge Regression          | 0.7498 | 0.6594      | 936,148.26  | 757,456.03  | 876,373,565,068.78 |
| Lasso Regression          | 0.7498 | 0.6594      | 936,112.54  | 757,364.26  | 876,306,690,051.90 |

---

## Future Improvements
- Add more features such as house age and location data.
- Hyperparameter tuning for Random Forest and Gradient Boosting models.
- Explore advanced models like XGBoost or CatBoost.
- Develop a web or mobile application for real-time predictions.

---

## License
This project is licensed under the [MIT License](LICENSE).

---


Feel free to contribute to this project by submitting issues or pull requests!
