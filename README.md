# Energy-Efficiency-Optimization

**📜 Project Overview**  
The **Energy Efficiency Optimization Tool** is a Python-based program designed to **analyze past energy consumption patterns** and **predict the next 100 days of energy usage** using **LSTM (Long Short-Term Memory) neural networks**.  

This tool helps in understanding **energy consumption trends**, **detecting inefficiencies**, and **forecasting future usage**, making it useful for industrial and grid energy management.  

---

## **🚀 Features**
✔ **Loads energy data from CSV files**  
✔ **Performs exploratory data analysis (EDA)**  
✔ **Visualizes energy usage trends with graphs**  
✔ **Uses LSTM (Machine Learning) to predict 100 future energy values**  
✔ **Detects anomalies and peak consumption periods**  
✔ **Provides structured output in a Pandas DataFrame**  

---

## **🛠️ Technologies Used**
- **Python** – Core programming language  
- **Pandas & NumPy** – Data handling and processing  
- **Matplotlib & Seaborn** – Data visualization  
- **TensorFlow/Keras** – LSTM model for future energy prediction  
- **Scikit-learn** – Data normalization  

---

## **📂 Project Structure**
```
📁 Energy_Efficiency_Optimization
│── energyeffopt.py        # Main script for energy analysis and prediction
│── AEP_hourly.csv         # Sample dataset (hourly energy consumption)
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
```

---

## **🔹 How to Install & Run**
### **1️⃣ Install Dependencies**
Run the following command to install required libraries:
```bash
pip install pandas numpy matplotlib seaborn tensorflow scikit-learn
```

### **2️⃣ Run the Python Script**
Execute the main script to perform analysis and predict energy consumption:
```bash
python energyeffopt.py
```

---

## **📊 Sample Output**
After running the script, the tool will:
- Display **initial dataset statistics**
- Generate **graphs showing past energy trends**
- Output **predicted energy consumption for the next 100 days**

### **Example Output (Predictions)**
```
           Date  TrueMegaWatt  PredictedMegaWatt
0  2024-06-01       12550.0            12645.2
1  2024-06-02       12700.0            12820.5
2  2024-06-03       12850.0            12950.1
...
```
- **TrueMegaWatt** → Actual energy consumption from the dataset  
- **PredictedMegaWatt** → Forecasted energy consumption using the trained LSTM model  

---

