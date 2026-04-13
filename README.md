#  Energy Demand Forecasting using LSTM & Weather Data

##  Project Overview

This project focuses on **energy demand forecasting** using historical data and weather variables such as **temperature** and **solar irradiation**.

The workflow combines:

*  Data analysis and preprocessing
*  Machine Learning & Deep Learning (LSTM models)
*  Model evaluation and visualization

---

##  Project Structure

```
├── data/                         # CSV datasets (energy, weather, etc.)
├── temperature_irradiation.ipynb # Data analysis & feature exploration
├── prevision.ipynb               # Initial forecasting model
├── previsionV1.ipynb             # First improved version
├── previsionV2.ipynb             # Model tuning
├── prevision V3.ipynb            # Final LSTM model
└── README.md
```

---

##  Features & Methods

###  Data Analysis

* Data cleaning and preprocessing
* Feature scaling using **StandardScaler**
* Dimensionality reduction (**PCA**)
* Clustering evaluation (Silhouette, Davies-Bouldin, Calinski-Harabasz)

###  Weather Data Integration

* Temperature and irradiation used as input features
* Correlation analysis with energy demand

---

##  Models Used

###  LSTM Neural Network

* Bidirectional LSTM layers
* Dropout regularization
* Dense output layers

###  Training Techniques

* EarlyStopping
* ReduceLROnPlateau
* Huber Loss function

---

##  Evaluation Metrics

* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* R² Score

---

##  Technologies

* Python 
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* TensorFlow / Keras

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run notebooks:

```bash
jupyter notebook
```

---

##  Results

* Improved prediction accuracy using LSTM models
* Weather variables significantly impact energy demand
* Progressive improvement from V1 → V3 models

---

##  Future Improvements

* Hyperparameter optimization
* Add more weather features
* Deploy model (API or dashboard)
* Use advanced models (Transformers, XGBoost)

---

##  Author

**Mohamed**

---

##  License

This project is for academic and research purposes.
