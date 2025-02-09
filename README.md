# Credit Card Fraud Detection

This project implements a credit card fraud detection system using Logistic Regression. It balances the dataset using undersampling and provides a Streamlit-based web interface for users to input transaction details and predict whether a transaction is legitimate or fraudulent.

## Features
- Machine learning model using Logistic Regression
- Real-time fraud prediction with user input
- Web-based interface using Streamlit
- Undersampling method to balance the dataset

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit

## Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/credit-fraud-detection.git
   cd credit-fraud-detection
   ```

2. **Install dependencies**
   ```sh
   pip install numpy pandas scikit-learn streamlit
   ```

3. **Download the dataset**
   - Place `creditcard.csv` in the project directory.

## Usage
1. **Run the Streamlit app**
   ```sh
   streamlit run app.py
   ```
2. **Enter transaction details**
   - Input all required feature values as a comma-separated string.
   - Click the "Submit" button to get a prediction.

## Model Training
- The dataset is split into training and testing sets.
- Logistic Regression is used for fraud detection.
- Model accuracy is evaluated on both training and testing sets.

## Notes
- The model is trained with undersampling, which may affect real-world performance.
- Ensure that all input features are provided correctly for accurate predictions.

## License
This project is open-source and available for modification and distribution.

## Contact
For any questions or contributions, reach out via GitHub or email.

