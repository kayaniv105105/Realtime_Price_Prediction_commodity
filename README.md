
# **Real-Time Price Prediction for Precious Metals and Crude Oil HYBRID Model (ARIMA & XGBOOST)- 98-99% Accuracy**

## **Overview**
This repository contains a system for predicting the prices of precious metals (gold and silver) and crude oil using hybrid machine learning models. The project consists of two components:

1. **Training the Models**: Historical data is used to train predictive models, which are then saved for future use.
2. **Real-Time Prediction**: A real-time system that loads the pre-trained models and applies them to live data for price predictions.

The project is implemented in Python and requires Jupyter Notebook for training and prediction workflows.

---

## **Directory Structure**
Here’s an overview of the files and their purposes:

### **Training Notebooks**
- **`Train_Historical_Gold_model.ipynb`**: Trains a hybrid model for gold price prediction using historical data and saves the trained model.
- **`Train_Historical_Silver_Model.ipynb`**: Trains a hybrid model for silver price prediction and saves the trained model.
- **`Train_Historical_Crude_Oil_Model.ipynb`**: Trains a hybrid model for crude oil price prediction and saves the trained model.

### **Real-Time Prediction Notebooks**
- **`Real-Time-Price-Prediction_GOLD_v2.ipynb`**: Loads the pre-trained gold model and predicts real-time prices.
- **`Real-Time-Price-Prediction_SILVER_v2.ipynb`**: Loads the pre-trained silver model and predicts real-time prices.
- **`Real-Time-Price-Prediction_CRUDE_OIL_v2.ipynb`**: Loads the pre-trained crude oil model and predicts real-time prices.

### **Data Files**
- **`Historical_Gold_data.csv`**: Historical data used for training the gold price prediction model.
- **`Historical_silver_data.csv`**: Historical data used for training the silver price prediction model.
- **`Historical_Crude_oil_data.csv`**: Historical data used for training the Crude oil price prediction model.

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
1. Open the training notebooks (`Hybrid_Gold_Model_v2.ipynb`, `Hybrid_Silver_Model_v2.ipynb`, and `Hybrid_Crude_Oil_Model_v2.ipynb`) in Jupyter Notebook.
2. Run the notebooks to train the models on the respective historical data files.
3. The trained models will be saved in your `C:` drive.

### **Step 2: Real-Time Predictions**
1. Open the real-time prediction notebooks (`Real-Time-Price-Prediction_GOLD_v2.ipynb`, `Real-Time-Price-Prediction_SILVER_v2.ipynb`, and `Real-Time-Price-Prediction_CRUDE_OIL_v2.ipynb`) in Jupyter Notebook.
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
