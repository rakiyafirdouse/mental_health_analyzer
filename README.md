# 🧠 Mental Health Analyzer  

A simple web-based application that analyzes user text and predicts mental health states using **Flask** and **Machine Learning**.  

## 🚀 Features  
- 🌐 Web interface built with **Flask**  
- 📊 Machine Learning model trained to classify text into:  
  - Stress  
  - Depression  
  - Bipolar  
  - Normal  
- 🎨 Simple styled UI for easy use  
- 🔍 REST API endpoint (`/predict`) for external integration  

## 🛠️ Tech Stack  
- **Python 3**  
- **Flask** (for backend & API)  
- **Scikit-learn** (for ML model)  
- **HTML/CSS/JS** (frontend)  

## 📂 Project Structure
mental_health_analyzer/
│── models/ # Trained ML model (best_model.pkl)
│── src/
│ ├── app.py # Flask backend
│ ├── templates/
│ │ └── index.html # Frontend UI
│── requirements.txt # Python dependencies
│── README.md # Project documentation
│── assets/
│   ├── home_page.jpg
│   ├── bipolar_pred.jpg
│   └── normal_pred.jpg
## 📸 Screenshots

### Home Page
![Home Page](assets/home_page.jpg)

### Prediction Result - Bipolar
![Bipolar Prediction](assets/bipolar_pred.jpg)

### Prediction Result - Normal
![Normal Prediction](assets/normal_pred.jpg)

