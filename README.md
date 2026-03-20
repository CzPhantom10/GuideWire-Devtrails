# ShieldPay AI  
### AI-Powered Parametric Insurance for India’s Gig Economy  

## TL;DR

1. A small amount (₹2–₹3) from each delivery is added to a shared insurance pool  
2. AI analyzes real-time data (weather, AQI, traffic) to determine payout based on disruption severity  
3. After payouts, remaining funds contribute to platform revenue and reserve  


## Problem

Delivery partners in India’s gig economy face unpredictable income loss due to external disruptions such as heavy rainfall, extreme heat, high pollution, traffic congestion, and platform outages.

These disruptions reduce working hours and can lead to a 20–30% loss in weekly income. Existing insurance systems are not suitable due to slow claim processes, rigid pricing models, and lack of real-time responsiveness.


## Solution

ShieldPay AI is an AI-powered parametric insurance platform that provides income protection through a micro-contribution model.

Instead of fixed premiums, delivery partners contribute a small amount per delivery into a shared insurance pool maintained at a regional or national level.

The system automatically detects disruptions and triggers payouts without requiring manual claims.

## Core Model

### Insurance Pool
- ₹2–₹3 contribution per delivery  
- Pool maintained regionally or nationally  
- Ensures scalability and risk distribution  


### AI-Driven Payout Engine

The platform integrates real-time data from:
- Weather APIs  
- AQI APIs  
- Traffic data  
- Platform status (simulated)  

AI evaluates:
- Disruption severity  
- Estimated income loss  


### Parametric Trigger System

- Continuous monitoring of real-world conditions  
- Disruption detected when thresholds are exceeded  
- No manual claims required  


### Automated Payouts

- AI calculates compensation based on severity  
- Instant payout from pooled fund  


### Fraud Detection

- Detects anomalies such as:
  - Location mismatch  
  - Duplicate claims  
  - Invalid disruption events  


## AI Components

### Risk & Payout Model
- Algorithm: Random Forest  
- Predicts disruption impact and payout  

### Fraud Detection Model
- Algorithm: Isolation Forest  
- Detects anomalous claim patterns  


## System Workflow

1. Drivers contribute per delivery into a regional pool  
2. System monitors environmental and operational data  
3. AI evaluates disruption severity  
4. Eligible drivers receive automated payouts  
5. Fraud detection validates claims  
6. Remaining funds are allocated to:
   - Platform revenue  
   - Reserve buffer  


## Revenue Model

- Residual pool margin after payouts  
- Reserve fund management  
- Future data insights for platform optimization  


## Dataset Strategy

Synthetic dataset combining:
- Environmental data (rainfall, AQI, traffic)  
- Worker attributes (income, work hours)  
- Disruption labels  
- Claim behavior  

Used for training:
- Risk & payout model  
- Fraud detection model  


## Tech Stack

### AI & Backend
- Python  
- Scikit-learn  
- Pandas, NumPy  
- FastAPI  

### Data Sources
- Weather APIs  
- AQI APIs  
- Simulated traffic and platform data  

### Frontend
- React.js  

### Payments
- Razorpay Sandbox / simulated UPI  

## Key Features

- Micro-contribution insurance model  
- Regional pooled risk system  
- AI-driven payout calculation  
- Automated parametric triggers  
- Fraud detection using anomaly detection  
- Real-time disruption monitoring  

## Impact

- Provides financial stability for gig workers  
- Eliminates manual claim processes  
- Enables fast and transparent payouts  
- Scales efficiently across regions  

## Future Scope

- Integration with real delivery platforms  
- Personalized pricing models  
- Expansion to other gig sectors  
- Real-time geolocation validation  

## Conclusion

ShieldPay AI delivers a scalable and intelligent approach to income protection by combining AI with a pooled parametric insurance model.

It ensures fast, automated, and fair compensation for gig workers facing real-world disruptions while maintaining a sustainable financial system.