## Flipkart Gridlock Hackthon

## Problem statement : 
Urban areas frequently experience congestion due to illegal on-street parking and spillover parking near commercial areas, metro stations, hospitals, markets, and event venues.
Traditional enforcement systems are largely patrol-based and reactive, resulting in:
- Lack of visibility into parking violation hotspots.
- No understanding of congestion impact caused by illegal parking.
- Inefficient deployment of enforcement personnel.
- Delayed response to high-priority obstruction zones.

## Solution
ParkWise AI addresses this challenge using machine learning, geospatial analytics, and hotspot intelligence to detect parking hotspots, predict violation severity, and enable targeted enforcement actions for smarter urban traffic management.ParkWise AI addresses this challenge using machine learning, geospatial analytics, and hotspot intelligence.

## Demo
Live Demo: https://park-wise-ai.vercel.app/

## 🎯 Objectives
- Detect illegal parking hotspots
- Predict violation severity
- Generate enforcement priorities
- Provide actionable recommendations
- Improve traffic flow and road efficiency

## 🏗 System Architecture
Frontend
- React 18
- TypeScript
- Tailwind CSS
- Leaflet.js

Backend
- FastAPI
- REST APIs
- Authentication layer
- Response caching

Machine Learning
- Gradient Boosting Classifier
- Feature Engineering Pipeline
- Priority Engine

Data Layer
- Violation Corpus
- Hotspot Index
- Station Registry
- Model Artifacts

## 📊 Dataset
- 298,450 Bengaluru violation records
- Geo-tagged hotspot coordinates
- Police station jurisdictions
- Historical enforcement outcomes

## 🧠 Machine Learning Pipeline
Raw Dataset
→ Feature Engineering
→ Model Training
→ Severity Prediction
→ Priority Scoring
→ Enforcement Recommendation

## ✨ Features
- Interactive hotspot map
- Severity prediction engine
- Confidence scoring
- Priority engine
- Vehicle violation lookup
- Analytics dashboard
- Enforcement recommendations
  
## 📈 Model Performance
| Metric | Score |
|--------|-------|
| Accuracy | 99.22% |
| Precision | 99.12% |
| Recall | 99.22% |
| F1 Score | 99.11% |

## 🚦 Severity Classes
- Low
- Medium
- High
- Critical

## 📍 Prototype Modules
- Analytics Dashboard
- Hotspot Map
- Prediction Panel
- Vehicle Search Module

## Future Scope
ParkWise AI can be extended with ANPR, CCTV-based detection, automated e-challans, smart towing, and smart city integrations to enable fully automated and intelligent parking enforcement.

## Conclusion
ParkWise AI leverages AI and geospatial intelligence to identify parking hotspots, predict violation severity, and enable targeted enforcement, contributing to reduced congestion and smarter city traffic management.
