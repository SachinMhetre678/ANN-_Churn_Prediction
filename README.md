
# ANN_Churn_Prediction

Welcome to the `ANN_Churn_Prediction` project! This repository contains the code and resources for predicting customer churn using an Artificial Neural Network (ANN). 

**Live Demo**: [ANN Churn Prediction Live](https://annchurnprediction-hceg4tq6uph2dsykjju5jf.streamlit.app)

## Project Structure

```
ANN_Churn_Prediction
 ┣ 📂logs
 ┃ ┗ 📂fit20240726-152124
 ┃ ┃ ┣ 📂train
 ┃ ┃ ┃ ┣ 📜events.out.tfevents.1721987750.DESKTOP-99O7HEK.9276.0.v2
 ┃ ┃ ┃ ┗ 📜events.out.tfevents.1721987795.DESKTOP-99O7HEK.9276.2.v2
 ┃ ┃ ┗ 📂validation
 ┃ ┃ ┃ ┣ 📜events.out.tfevents.1721987752.DESKTOP-99O7HEK.9276.1.v2
 ┃ ┃ ┃ ┗ 📜events.out.tfevents.1721987795.DESKTOP-99O7HEK.9276.3.v2
 ┣ 📜.gitignore
 ┣ 📜app.py
 ┣ 📜Churn_Modelling.csv
 ┣ 📜experiments.ipynb
 ┣ 📜label_encoder_gender.pkl
 ┣ 📜model.h5
 ┣ 📜onehot_encoder_geo.pkl
 ┣ 📜prediction.ipynb
 ┣ 📜requirements.txt
 ┗ 📜scaler.pkl
```

## Features

### 1. Data Preprocessing
- **Label Encoding**: Gender column encoding using `label_encoder_gender.pkl`.
- **One-Hot Encoding**: Geography column encoding using `onehot_encoder_geo.pkl`.
- **Feature Scaling**: StandardScaler applied using `scaler.pkl`.

### 2. Model Training
- **Neural Network**: The ANN model is defined, compiled, and trained.
- **Training Logs**: Training and validation logs stored under the `logs` directory.

### 3. Predictions
- **Interactive Predictions**: Use `app.py` to predict churn for new data points.
- **Jupyter Notebooks**: Explore model training and predictions in `experiments.ipynb` and `prediction.ipynb`.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/SachinMhetre678/ANN_Churn_Prediction.git
   cd ANN_Churn_Prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

2. **Explore the Notebooks**:
   - `experiments.ipynb`: Contains the model training workflow.
   - `prediction.ipynb`: Demonstrates how to use the trained model to make predictions.

## Model Performance

Check out the logs directory for detailed training and validation logs:
- Training logs: `logs/fit20240726-152124/train`
- Validation logs: `logs/fit20240726-152124/validation`

