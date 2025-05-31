# AI-Driven 5G Network QoS and Resource Prediction

Efficient management of network resources and Quality of Service (QoS) is essential to meet the stringent demands of 5G networks. This project leverages Artificial Intelligence (AI), machine learning, and deep learning techniques to predict key QoS parameters and resource allocation needs based on network data.

Using the [5G Quality of Service dataset](https://www.kaggle.com/datasets/omarsobhy14/5g-quality-of-service), the models analyze network parameters such as bandwidth requirements, latency, and signal strength to forecast resource demands accurately. This predictive capability can assist network operators in optimizing planning and enhancing overall user experience.

---

## Features

- Comprehensive data preprocessing including unit normalization and timestamp handling
- Exploration and visualization of 5G network QoS data
- Implementation and comparison of multiple machine learning classifiers:
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Extra Trees
  - AdaBoost
  - K-Nearest Neighbors (KNN)
  - Decision Trees
- Implementation of a Deep Learning model using Keras (fully connected feedforward neural network)
- Model training with cross-validation and performance evaluation
- Confusion matrix generation for classification insights
- Automated prediction pipeline for resource allocation classes

---

## Dataset

The dataset utilized in this project is the [5G Quality of Service dataset](https://www.kaggle.com/datasets/omarsobhy14/5g-quality-of-service), containing network performance metrics including:

- Required Bandwidth (Mbps/Kbps)
- Allocated Bandwidth (Mbps/Kbps)
- Latency (ms)
- Signal Strength (dBm)
- Resource Allocation (%)
- Timestamp of records

---

## Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy for data manipulation
- scikit-learn for machine learning modeling and evaluation
- TensorFlow/Keras for deep learning model
- Matplotlib and Seaborn for data visualization
- XGBoost for advanced gradient boosting classification

---

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/AI-Driven-5G-Network-QoS-and-Resource-Prediction.git
   cd AI-Driven-5G-Network-QoS-and-Resource-Prediction

2. Install Dependencies
    ```bash
    pip install -r requirements.txt

3. Launch the notebook
    ```bash
    jupyter notebook
