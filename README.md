# NYC Taxi Trip Prediction 🚖

## 📌 Project Overview

This project aims to predict NYC taxi trip data using machine learning. The system supports both real-time and batch predictions by leveraging a feature store for data consistency. The pipeline includes data ingestion, feature engineering, model training, and deployment using Streamlit.

## 📊 Data Source

The dataset is sourced from the NYC TLC Trip Record Data and contains:

- **Pickup/Dropoff locations** 🗺️
- **Trip duration** ⏳
- **Fare amount** 💲
- **Other relevant trip details**

## 🛠️ Tech Stack

- **Hopsworks.ai** – Feature Store for storing and retrieving features
- **Dagshub + MLflow** – Model tracking and experiment logging
- **GitHub** – Version control and code repository
- **Streamlit** – Deployment for an interactive user interface
![image](https://github.com/user-attachments/assets/b47ab273-03e5-447d-86d5-0a9ec6d70cc7)


## ⚙️ Architecture

The workflow is structured as follows:

1. **Data Collection**: NYC taxi trip data is collected and processed.
2. **Feature Engineering**: Features are created and stored in Hopsworks Feature Store.
3. **Model Training**: A machine learning model is trained using historical data and logged via MLflow.
4. **Model Registry**: The trained model is stored in the Model Registry for production use.
5. **Inference Pipeline**: The model retrieves features from Hopsworks and performs predictions.
6. **Deployment**: The inference system is deployed via Streamlit, allowing users to predict taxi trip details.
7. **Monitoring**: Model performance is continuously monitored to track drift and anomalies.

## 🔧 Installation & Setup

### 📍 Prerequisites

Ensure you have the following installed:

- **Python 3.x**
- **Hopsworks API Key**
- **Streamlit**
- **MLflow**
- **DVC (for version control)**
- **Required Python Libraries** (listed in `requirements.txt`)

### 📥 Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/nyc-taxi-prediction.git
   cd nyc-taxi-prediction
   ```
2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Setup Hopsworks API Key**:
   - Create an `.env` file and add your Hopsworks API key:
     ```env
     HOPSWORKS_API_KEY=your_api_key_here
     ```
5. **Run the Streamlit App**:
   ```bash
   streamlit run app.py
   ```

## 📈 Model Performance & Monitoring

- Predictions are logged back to **Hopsworks** for tracking.
- **MLflow** provides versioning and performance metrics.
- Data drift and anomalies are continuously monitored to maintain model reliability.

## 🚀 Application Deployment

Access the deployed application using the following links:

- 🌍 [Streamlit App Instance 1](https://nyctaxi-main-skcus3sd3atk2uynxcc2ba.streamlit.app/)
- 🌍 [Streamlit App Instance 2](https://nyctaxi-main-lezapp8cckencmhp8ydaas6.streamlit.app/)

## 🤝 Contribution

We welcome contributions! Feel free to open a **pull request** or raise **issues** for improvements.



---

🚀 Happy Coding! 🚖
