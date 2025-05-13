
# **Real-Time Price Prediction for Precious Metals and Crude Oil HYBRID Model - 99% Accuracy**

## **Overview**
This repository contains a system for predicting the prices of precious metals (gold and silver) and crude oil using hybrid machine learning models. The project consists of two components:

1. **Training the Models**: Historical data is used to train predictive models, which are then saved for future use.
2. **Real-Time Prediction**: A real-time system that loads the pre-trained models and applies them to live data for price predictions.

The project is implemented in Python and requires Jupyter Notebook for training and prediction workflows.

---

## **Directory Structure**
Here’s an overview of the files and their purposes:


## **CODE Directory**


### **Training Notebooks in Historical_Training folder**
- **`Historical_training_commodity-GOLD.ipynb`**: Trains a hybrid model for gold price prediction using historical data and saves the trained model.
- **`Historical_training_commodity-SILVER.ipynb`**: Trains a hybrid model for silver price prediction and saves the trained model.
- **`Historical_training_commodity-CRUDE_OIL.ipynb`**: Trains a hybrid model for crude oil price prediction and saves the trained model.

### **Real-Time Prediction Notebooks in Real_time folder**
- **`Realtime-prediction_GOLD.ipynb`**: Loads the pre-trained gold model and predicts real-time daily prices.
- **`Realtime-prediction_GOLD_Hourly.ipynb`**: Loads the pre-trained gold model and predicts real-time hourly prices.
- **`Realtime-prediction_SILVER.ipynb`**: Loads the pre-trained silver model and predicts real-time daily prices.
- **`Realtime-prediction_SILVER_Hourly.ipynb`**: Loads the pre-trained silver model and predicts real-time hourly prices.
- **`Realtime-prediction_CRUDE_OIL.ipynb`**: Loads the pre-trained Crude Oil model and predicts real-time daily prices.
- **`Realtime-prediction_CRUDE_OIL_Hourly.ipynb`**: Loads the pre-trained Crude Oil model and predicts real-time hourly prices.

### **Back testing Notebooks in Backtesting folder**
- **`Backtesting_GOLD-2015-2025.ipynb`**: Loads the pre-trained gold model and predicts  prices in back dates.
- **`Backtesting_GOLD-2003-2025.ipynb`**: Loads the pre-trained gold model and predicts real-time hourly prices.
- **`Backtsting_SILVER-2003-2025.ipynb`**: Loads the pre-trained silver  model and predicts  prices in back dates.
- **`Backtsting_SILVER-2015-2025.ipynb`**: Loads the pre-trained silver  model and predicts  prices in back dates.
- **`Backtesting_CRUDE_OIL-2015-2025.ipynb`**: Loads the pre-trained Crude Oil  model and predicts  prices in back dates.
- **`Backtesting_CRUDE_OIL-2003-2025.ipynb`**: Loads the pre-trained Crude Oil model and predicts  prices in back dates.

- ## **DATA Directory**
### **Data Files**
- **`Historical_Gold_data.csv`**: Historical data used for training the gold price prediction model.
- **`Historical_silver_data.csv`**: Historical data used for training the silver price prediction model.
- **`Historical_Crude_oil_data.csv`**: Historical data used for training the Crude oil price prediction model.
- **`Historical_Gold_data-2003-2025.csv`**: Historical data used for training the gold price prediction model.
- **`Historical_silver_data-2003-2025.csv`**: Historical data used for training the silver price prediction model.
- **`Historical_Crude_oil_data-2003-2025.csv`**: Historical data used for training the Crude oil price prediction model.
- **`Historical_Gold_data-2015-2025.csv`**: Historical data used for training the gold price prediction model.
- **`Historical_silver_data-2015-2025.csv`**: Historical data used for training the silver price prediction model.
- **`Historical_Crude_oil_data-2015-2025.csv`**: Historical data used for training the Crude oil price prediction model.

-  ## **Sentiments Directory**
-  ### **GOLD SENTIMENTS Data Files in every COMMODITY folders**
- **`GOLD\Historical_Sentiments.csv`**: Historical setiment data - GOLD.
- **`SILVER\Historical_Sentiments.csvv`**: Historical setiment data - SILVER.
- **`CRUDE_OIL\Historical_Sentiments.csvv`**:  Historical setiment data - CRUDE OIL.

- 
### **Configuration File**
- **`requirements.txt`**: Contains the Python dependencies required to run the notebooks.

---

## **Prerequisites**
To run this project, you'll need:
1. **Python 3.11**: Ensure Python 3.11 is installed on your system.
2. **Jupyter Notebook**: Install Jupyter Notebook for running `.ipynb` files.

---

## **Installation**
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/your-repo-name.git](https://github.com/kayaniv105105/Realtime_Price_Prediction.git)
   cd Realtime_Price_Prediction
   ```
2. Install the required Python dependencies:
   ```bash
   pip install jupyter
   pip install -r requirements.txt
   ```

---

## **Usage**
### **Step 1: Train the Models**
1. Open the training notebooks (`Historical_training_commodity-GOLD.ipynb`, `Historical_training_commodity-SILVER.ipynb`, and `Historical_training_commodity-CRUDE_OIL.ipynb`) in Jupyter Notebook.
2. Run the notebooks to train the models on the respective historical data files.
3. The trained models will be saved in your `C:` drive.

### **Step 2: Real-Time Predictions**
1. Open the real-time prediction notebooks (`Realtime-prediction_GOLD.ipynb`, `Realtime-prediction_SILVER.ipynb`, and `Realtime-prediction_CRUDE_OIL.ipynb`) in Jupyter Notebook.
2. Run the notebooks to predict real-time prices using the pre-trained models.

---

## **File Paths**
Ensure the following file paths are set correctly in the notebooks:
- Historical data files Data Folder.
- Pre-trained model files (saved in the Model folder).

---

## **Key Features**
- **Hybrid Models**: Combines advanced machine learning techniques for improved accuracy.
- **Real-Time Predictions**: Predicts prices in real-time using pre-trained models.
- **Versatile Application**: Supports gold, silver, and crude oil price prediction.

---

## **Contributing**
Contributions are welcome! Feel free to submit issues or pull requests for improvements or new features.

---

## **License**


---

## **Contact**
For questions or support, please contact:  
- **Name**: Vinayak rane
- **Email**: ranevinayak2@gmail.com

--- 
