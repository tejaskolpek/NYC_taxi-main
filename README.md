🏙️ NYC Taxi Trip Prediction 🚖

📌 Project Overview

This project aims to predict NYC taxi trip data using machine learning. The system is designed to handle real-time and batch predictions by leveraging a feature store for data consistency. The pipeline includes data ingestion, feature engineering, model training, and deployment on Streamlit.
📊 Data Source

📍 The dataset is sourced from the NYC TLC Trip Record Data, containing:

Pickup/Dropoff locations 🗺️

Trip duration ⏳

Fare amount 💲

And more…

🛠️ Tech Stack

🔹 Hopsworks.ai – Feature Store for storing and retrieving features
🔹 Dagshub + MLflow – Model tracking and experiment logging
🔹 GitHub – Version control and code repository
🔹 Streamlit – Deployment for an interactive user interface

![image](https://github.com/user-attachments/assets/b47ab273-03e5-447d-86d5-0a9ec6d70cc7)

⚙️ Architecture

📌 The workflow is structured as follows:

1️⃣ Data Collection: NYC taxi trip data is collected and processed.
2️⃣ Feature Engineering: Features are created and stored in Hopsworks Feature Store.
3️⃣ Model Training: A machine learning model is trained using historical data and logged via MLflow.
4️⃣ Model Registry: The trained model is stored in the Model Registry for production use.
5️⃣ Inference Pipeline: The model retrieves features from Hopsworks and performs predictions.
6️⃣ Deployment: The inference system is deployed via Streamlit, allowing users to predict taxi trip details.
7️⃣ Monitoring: Model performance is continuously monitored to track drift and anomalies.
🔧 Installation & Setup

📍 Prerequisites

✅ Python 3.x
✅ Hopsworks API Key
✅ Streamlit
✅ MLflow
✅ DVC (for version control)
✅ Required Python Libraries (listed in requirements.txt)

📈 Model Performance & Monitoring

📊 Predictions are logged back to Hopsworks for tracking.
📊 MLflow provides versioning and performance metrics.
📊 Data drift and anomalies are monitored to maintain model reliability.

🚀 Application Deployment

🔗 You can access the deployed application using the following links:

🌍 [Streamlit App Instance 1](https://nyctaxi-main-skcus3sd3atk2uynxcc2ba.streamlit.app/)
🌍 [Streamlit App Instance 2](https://nyctaxi-main-lezapp8cckencmhp8ydaas6.streamlit.app/)

🤝 Contribution

Feel free to open a pull request or raise issues for improvements. Your contributions are welcome! 🚀

📝 License

📜 MIT License
