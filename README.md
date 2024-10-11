# DeepCraft_Stock_Prediction

## Stock Price Prediction Using LSTM

This project aims to predict stock prices using Long Short-Term Memory (LSTM) neural networks. It utilizes historical stock price data to train the model and provides predictions based on time series analysis.

### Overview

The program is built using Python and leverages popular libraries such as TensorFlow, Keras, and Scikit-learn for data preprocessing, model building, and evaluation. The main steps involved in this project are:

1. **Data Preparation**: Loading the dataset and preprocessing it for analysis.
2. **Exploratory Data Analysis (EDA)**: Understanding the data trends and visualizing important metrics.
3. **Feature Engineering**: Creating useful features, including lagged values and moving averages.
4. **Model Selection and Training**: Implementing an LSTM model to learn from the data.
5. **Model Evaluation**: Assessing the model's performance using evaluation metrics such as RMSE.

### Requirements

Before running the program, ensure you have the following libraries installed:

- numpy
- pandas
- scikit-learn
- tensorflow
- keras

You can install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn tensorflow
```
### Getting Started
#### Clone the repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/Aayushstrom/DeepCraft_Stock_Prediction
cd stock-price-prediction
```
### Prepare the Dataset
Place your stock price dataset (CSV format) in the same directory as the script. Ensure the dataset contains the columns required for the analysis, such as:

    終値 (end price)
    始値 (open price)
    高値 (high price)
    安値 (low price)
    出来高 (trading volume)
    変化率 % (percentage change)

### Run the Program
To execute the program, run the following command in your terminal:
```bash
python stock_price_prediction.py
```
### View Results
After running the program, you will see the RMSE of the LSTM model printed in the terminal. You can modify the code to visualize the predictions versus actual values if desired.

### Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements
TensorFlow and Keras for the deep learning framework.
Scikit-learn for data preprocessing and evaluation metrics.
Pandas and Numpy for Data Cleaning and Feature engineering
Seaborn and Matplotlib for data visualization
