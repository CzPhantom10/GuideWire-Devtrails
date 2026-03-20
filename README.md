# Smart Income Shield  
### AI-Powered Parametric Insurance for India’s Gig Economy

---

## Problem Statement

India’s gig economy, especially delivery partners, faces frequent income loss due to external disruptions such as heavy rainfall, extreme heat, high pollution levels, traffic congestion, and platform outages.

These disruptions reduce working hours and can lead to a 20–30% loss in weekly income. Currently, there is no insurance solution specifically designed to protect gig workers from such income loss.

---

## Solution

Smart Income Shield is an AI-powered parametric insurance platform that provides income protection to delivery partners.

The system:
- Monitors real-world conditions using APIs  
- Predicts risk using machine learning  
- Automatically triggers payouts when disruption thresholds are met  
- Uses a weekly pricing model aligned with gig workers’ earning cycle  

---

## System Workflow

1. **User Onboarding**
   - Collects user details such as city, platform, average income, and working hours  

2. **Risk Assessment (AI)**
   - Predicts probability of income disruption based on environmental factors  

3. **Premium Calculation**
   - Calculates weekly premium based on risk score  

4. **Event Monitoring**
   - Continuously tracks weather, AQI, traffic, and platform conditions  

5. **Parametric Trigger**
   - Detects disruption events when thresholds are exceeded  

6. **Fraud Detection (AI)**
   - Validates claims using anomaly detection  

7. **Payout Processing**
   - Automatically processes payouts (mock implementation)  

---

## AI Components

### 1. Risk Prediction Model
- Algorithm: Random Forest Classifier  
- Purpose: Predict likelihood of income disruption  
- Inputs:
  - Rainfall
  - AQI
  - Traffic level
  - City
  - Season  

### 2. Fraud Detection Model
- Algorithm: Isolation Forest  
- Purpose: Detect fraudulent or suspicious claims  
- Inputs:
  - Location match
  - Claim frequency
  - Event consistency  

---

## Dataset

A synthetic dataset is generated to simulate real-world conditions.

### Features:
- City  
- Rainfall (mm)  
- AQI  
- Traffic level  
- Average daily income  
- Season  
- Disruption (target variable)  

### Fraud Dataset:
- User ID  
- Claim count  
- Location match  
- Duplicate claim flag  
- Fraud label  

---

## Tech Stack

### Backend & AI
- Python  
- FastAPI  
- Scikit-learn  
- Pandas  
- NumPy  

### Frontend
- React.js  

### APIs
- Weather API (OpenWeather)  
- AQI API (AQICN)  
- Traffic data (optional / simulated)  

### Payments
- Razorpay Sandbox (or mock implementation)  

---

## Key Features

- AI-driven risk prediction  
- Weekly premium pricing model  
- Automated parametric claim triggering  
- Fraud detection using anomaly detection  
- Real-time disruption monitoring  
- Simple onboarding system  

---

## Installation

```bash
# Clone the repository
git clone https://github.com/your-repo/smart-income-shield.git

# Navigate to project folder
cd smart-income-shield

# Create virtual environment
python -m venv venv

# Activate environment
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt
```

Running the Backend
uvicorn main:app --reload
API Endpoints
Endpoint	Method	Description
/predict-risk	POST	Returns risk score
/calculate-premium	POST	Returns weekly premium
/detect-fraud	POST	Detects fraudulent claims
Project Structure
smart-income-shield/
│
├── data/                 # Synthetic datasets
├── models/               # Trained ML models
├── api/                  # FastAPI routes
├── utils/                # Helper functions
├── main.py               # Entry point
├── requirements.txt
└── README.md
Future Improvements

Integration with real delivery platforms

More advanced predictive models

Real-time geolocation validation

Expansion to other gig sectors

Team

AI/ML: Risk prediction and fraud detection

Backend: API development and integration

Frontend: Dashboard and UI

Data: Dataset generation and preprocessing

Conclusion

Smart Income Shield provides a scalable and practical solution to protect gig workers from income loss caused by external disruptions. By combining AI with parametric insurance, the platform enables automated, fast, and reliable financial protection.


---

If you want next, I can:
- Add **GitHub badges (very professional look)**
- Add **demo screenshots section**
- Or convert this into a **PPT pitch deck (super useful for judging round)**