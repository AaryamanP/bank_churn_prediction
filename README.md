# Churn Prediction Model

This repository contains a machine learning project for predicting customer churn using a sample dataset. The goal is to build, train, and evaluate a model that can identify customers likely to leave a service.

## Dataset

- **File:** `data.csv`
- **Description:** Contains customer features and a target column indicating churn status.
- **Columns:**
  - Features such as demographics, account information, usage metrics, etc.
  - Target column (e.g., `Churn` or `Exited`)

## Project Structure

- `churn_model.ipynb`: Main Jupyter notebook for data analysis, model training, and evaluation.
- `data.csv`: Dataset used for training and testing the model.
- `requirements.txt`: List of required Python packages.

## Setup

1. **Clone the repository:**
   ```powershell
   git clone https://github.com/AaryamanP/churn_prediction.git
   cd churn_prediction
   ```
2. **Install dependencies:**
   ```powershell
   pip install -r requirements.txt
   ```
3. **Open the notebook:**
   - Use Jupyter Lab or VS Code to open `churn_model.ipynb`.

## Usage

1. **Load the data:**
   - The notebook reads `data.csv` and performs exploratory data analysis.
2. **Preprocess the data:**
   - Handles missing values, encodes categorical variables, and scales features.
3. **Train the model:**
   - Multiple algorithms can be tested (e.g., Logistic Regression, Random Forest, XGBoost).
4. **Evaluate performance:**
   - Metrics such as accuracy, precision, recall, F1-score, and ROC-AUC are reported.
5. **Make predictions:**
   - Use the trained model to predict churn on new data.

## Example Results

- Confusion matrix, classification report, and ROC curve are generated in the notebook.
- Feature importance analysis helps understand key drivers of churn.

## Next Steps

- Tune hyperparameters for better performance.
- Try additional algorithms or ensemble methods.
- Deploy the model as an API or web app.
- Add more data or features for improved accuracy.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
