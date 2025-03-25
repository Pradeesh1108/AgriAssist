# AgriAssist

## 🌱 Overview

AgriAssist is an AI-powered system designed for **plant disease prediction** and **pest detection** using weather data. This project utilizes machine learning models to analyze plant health and predict pest infestations based on environmental conditions.

## 🚀 Features

- **Plant Disease Prediction:** Uses a trained CNN model to detect plant diseases from images.
- **Pest Detection Based on Weather:** Analyzes weather data to predict potential pest infestations.
- **Pre-trained Models:** The models are saved for later use after training.
- **Dataset Handling:** Organizes datasets efficiently for easy access.

## 🛠️ Tech Stack

- **Python**
- **TensorFlow/Keras** (for training CNN models)
- **Scikit-learn** (for weather-based pest prediction)
- **Pandas & NumPy** (for data preprocessing)
- **Matplotlib & Seaborn** (for visualization)

## 📂 Project Structure

```plaintext
AgriAssist/
│── datasets/                      # Contains datasets for training and testing
│── models/                        # Trained models saved after training
│── plantDiseaseDetectionTraining.ipynb  # Training script for plant disease detection
│── plantDiseaseDetectionTesting.ipynb   # Testing script for plant disease detection
│── pest_prediction_based_on_weather.ipynb  # Training script for pest prediction
│── WeatherAnalysis.py              # Uses trained pest prediction model for analysis
│── README.md                       # Project documentation
```

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/AgriAssist.git
   cd AgriAssist
   ```
2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Prepare datasets:**
   - Place the plant disease dataset inside the `datasets/` folder.
   - Ensure weather data for pest prediction is available in `datasets/`.

## 🏋️‍♂️ Training & Testing

### 1️⃣ Train the Plant Disease Detection Model

   ```bash
   Open plantDiseaseDetectionTraining.ipynb and run all cells
   ```
   - The trained model will be saved in `models/`.

### 2️⃣ Test the Plant Disease Detection Model

   ```bash
   Open plantDiseaseDetectionTesting.ipynb and run all cells
   ```
   - This script loads the trained model and makes predictions.

### 3️⃣ Train the Pest Prediction Model

   ```bash
   Open pest_prediction_based_on_weather.ipynb and run all cells
   ```
   - The trained model will be saved in `models/`.

### 4️⃣ Analyze Pest Prediction Based on Weather

   ```bash
   python WeatherAnalysis.py
   ```
   - Uses the trained model to predict pest activity based on weather data.

## 🤝 Contributors

- **Pradeesh S**
- **Prakash Dass R**
- **Sai Dhinakar S**



