# AI-Based Smart Crop Recommendation System

## 1. Project Overview

The AI-Based Smart Crop Recommendation System helps farmers select suitable crops based on soil and weather conditions.

The system uses Machine Learning to recommend suitable crops from the given agricultural parameters.

## 2. Team Modules

### Member 1
Dataset + Exploratory Data Analysis

### Member 2
Machine Learning + AI Recommendation

### Member 3
Flask Backend + APIs

### Member 4
Frontend + User Interface

### Member 5
MySQL + Dashboard + Weather

### Member 6
Integration + Testing + Deployment + Presentation

## 3. System Architecture

Frontend
    |
    v
Flask Backend
    |
    +----------> ML Model
    |                |
    |                v
    |          Crop Prediction
    |
    +----------> MySQL Database
                     |
                     v
              Prediction History
                     |
                     v
                 Dashboard

## 4. Prediction Flow

Farmer
  |
  v
Enter Soil and Weather Details
  |
  v
Frontend
  |
  v
Flask /predict API
  |
  v
Machine Learning Model
  |
  v
Crop Recommendation
  |
  v
Save Prediction
  |
  v
MySQL Database
  |
  v
Prediction History / Dashboard

## 5. ML Input Features

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

## 6. Main Backend APIs

- POST /predict
- POST /save-prediction
- GET /history

## 7. Integration Responsibilities

Member 6 will integrate:

- Frontend with Flask backend
- Flask backend with ML model
- Flask backend with MySQL
- Prediction system with dashboard
- Weather information with the application

## 8. Testing

The final application will be tested for:

- Valid inputs
- Empty inputs
- Invalid inputs
- Incorrect data types
- Extreme values
- ML prediction
- API responses
- Database operations
- Frontend functionality
- Mobile responsiveness
- Weather API failures

## 9. Deployment

After successful integration and testing, the complete application will be deployed.

## 10. Final Goal

The final system should provide a simple and farmer-friendly interface for crop recommendation using Machine Learning.## 3. System Architecture

The system follows a modular architecture consisting of:

1. Dataset and EDA
2. Machine Learning and AI Recommendation
3. Flask Backend and APIs
4. Frontend and User Interface
5. MySQL Database, Dashboard and Weather
6. Integration, Testing and Deployment

The frontend sends user inputs to the Flask backend through APIs.
The backend processes the input using the trained ML model and returns the recommended crop.
Database and weather modules provide additional information required by the system.

## 4. Integration Flow

User → Frontend → Flask API → ML Model → Crop Recommendation → Frontend

Additional data:
Weather API → Backend
MySQL Database → Backend

## 5. Integration Checklist

- [ ] Dataset module integrated
- [ ] ML model integrated
- [ ] Flask APIs connected
- [ ] Frontend connected with backend
- [ ] MySQL database connected
- [ ] Weather API integrated
- [ ] Complete system tested
- [ ] Final deployment completed