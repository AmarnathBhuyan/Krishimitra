# 🌾 Krishimitra – AI-Powered Agricultural Assistance

Krishimitra is an AI-based platform that provides smart solutions for farming through crop recommendation, fertilizer suggestion, and plant disease detection.

## 🔧 Features

- **Crop Recommendation**  
  ML-based prediction using soil and weather data.  
  Model: Random Forest (Scikit-learn)

- **Fertilizer Suggestion**  
  AI-driven suggestions based on NPK levels and crop type.  
  Tech: Python, Pandas, Flask

- **Disease Detection**  
  Image-based plant disease diagnosis using deep learning.  
  Model: ResNet9 (PyTorch)

## 🌐 Technologies

- Python, Flask, Pandas  
- Scikit-learn, PyTorch, TorchVision  
- OpenWeatherMap API  
- PIL for image handling

## 📊 Inputs

- Soil data: N, P, K, pH  
- Weather: Temp & Humidity (API)  
- Leaf images for disease detection  
- Crop type for fertilizer suggestion

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/krishimitra.git
cd krishimitra
pip install -r requirements.txt
python app.py

📁 Structure
krishimitra/
├── crop_recommendation/
├── fertilizer_suggestion/
├── disease_detection/
├── templates/
├── static/
└── app.py

✅ Benefits
+30% yield | -20% cost | -15% water use
Promotes sustainability
Real-time, mobile-friendly AI assistance

📌 Use Cases
Smart farming for farmers
Precision agri-tech solutions
Research and policy-making

