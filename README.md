# house_price_prediction
Built a Linear Regression model using the California Housing dataset to predict median house prices. Trained and evaluated the model with scikit-learn using MSE and R² metrics, and generated predictions for new housing data based on key property and location features.


## Housing Price Prediction using Linear Regression

A machine learning project that predicts median house prices using the California Housing dataset and a Linear Regression model from scikit-learn. The project demonstrates the complete machine learning workflow, from data loading and preprocessing to model training, evaluation, and prediction.


## Features

- Uses the California Housing dataset from scikit-learn
- Implements Linear Regression for price prediction
- Splits data into training and testing sets
- Evaluates model performance using:
  - Mean Squared Error (MSE)
  - R² Score
- Displays feature coefficients
- Predicts house prices for new input data


## Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn


## Project Structure

```
├── california_housing.py
├── README.md
```


## Dataset

The project uses the **California Housing Dataset** provided by scikit-learn.

### Features

| Feature | Description |
|----------|-------------|
| MedInc | Median income |
| HouseAge | Median house age |
| AveRooms | Average rooms per household |
| AveBedrms | Average bedrooms per household |
| Population | Population of the block |
| AveOccup | Average occupants per household |
| Latitude | Latitude |
| Longitude | Longitude |

**Target Variable**

- **MedHouseVal** – Median House Value (in hundreds of thousands of dollars)


## Installation

Clone the repository :

```bash
git clone https://github.com/Abhinav-cloud482/housing-price-prediction.git
```

Navigate to the project folder :

```bash
cd housing-price-prediction
```

Install the required packages :

```bash
pip install pandas numpy scikit-learn
```


## Usage

Run the Python script :

```bash
python house_price_prediction.py
```

The program will :

- Load the dataset
- Train the Linear Regression model
- Evaluate model performance
- Display model coefficients
- Predict the price for a sample house


## Sample Output

```
Mean Squared Error: 0.5559
R² Score: 0.5758

Model Coefficients:
Intercept: -37.02

Predicted house price: $265,000.00
```

*Actual values may vary slightly depending on the library version.*


## Machine Learning Workflow

1. Load the California Housing dataset
2. Prepare features and target variable
3. Split the dataset into training and testing sets
4. Train a Linear Regression model
5. Make predictions
6. Evaluate using MSE and R² Score
7. Predict house prices for new data


## Evaluation Metrics

### Mean Squared Error (MSE)

Measures the average squared difference between predicted and actual values.

Lower values indicate better performance.

### R² Score

Measures how well the model explains the variance in the target variable.

- **1.0** = Perfect prediction
- **0.0** = Model performs no better than predicting the mean


## Future Improvements

- Feature Scaling
- Data Visualization
- Multiple Regression Models Comparison
- Cross Validation
- Hyperparameter Tuning
- Model Serialization using Pickle
- Interactive Prediction Interface using Streamlit


## License

This project is open source and available under the MIT License.


## Author

**Abhinav Dixit**

GitHub: https://github.com/Abhinav-cloud482
