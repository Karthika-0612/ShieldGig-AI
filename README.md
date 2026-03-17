# ShieldGig AI
### Predictive Income Protection Ecosystem for Gig Workers

ShieldGig AI is an AI-powered parametric insurance platform designed to protect gig economy workers from income loss caused by environmental and urban disruptions.

Unlike traditional insurance systems that require manual claim submissions, ShieldGig AI automatically detects disruptions using real-time environmental data and triggers instant payouts.

Beyond compensation, the platform predicts risks, recommends safer work zones, and helps gig workers maintain stable income even during uncertain conditions.

---

# Vision

To build the world's first **AI-driven income protection ecosystem for gig workers**, ensuring financial stability even during unpredictable environmental disruptions.

---

# Problem Statement

Gig workers such as food delivery partners rely heavily on daily earnings to sustain their livelihood. However, external disruptions like heavy rainfall, extreme heat, air pollution, floods, or unexpected road closures can significantly reduce their working hours and delivery opportunities.

Studies suggest that gig workers may lose **20–30% of their weekly income** due to environmental disruptions.

Existing insurance systems mainly cover:

- Health
- Accidents
- Vehicle damage

However, **income loss caused by environmental disruptions remains unprotected**.

ShieldGig AI aims to solve this problem by building an intelligent parametric insurance platform that predicts disruptions and automatically compensates gig workers when their earnings are affected.

---

# Solution Overview

ShieldGig AI introduces a powerful **Predict → Prevent → Protect → Compensate** model.

### Predict
AI models analyze environmental and urban data to forecast disruptions.

### Prevent
Workers receive alerts and safe-zone recommendations to avoid high-risk areas.

### Protect
Workers purchase affordable weekly parametric insurance coverage.

### Compensate
If disruption thresholds are crossed, payouts are automatically triggered.

This eliminates the need for manual claim filing and ensures fast compensation.

---

# Target Persona

### Primary Users

Gig delivery workers operating on platforms such as:

- Swiggy
- Zomato
- Dunzo
- Blinkit
- Uber Eats

### Example Persona

Name: Ravi Kumar  
City: Chennai  
Platform: Swiggy  
Average Daily Earnings: ₹600  
Average Weekly Earnings: ₹3500  

### Challenges Faced

- Heavy rainfall stopping deliveries
- Extreme heat reducing working hours
- Pollution causing health risks
- Traffic disruptions
- Unexpected curfews or strikes

---

# Core Features

### AI Dynamic Premium Calculation
Premiums are calculated based on worker location risk, environmental history, and disruption forecasts.

### Real-Time Disruption Monitoring
Continuous monitoring of weather, pollution, and traffic data using external APIs.

### Automated Parametric Claims
Claims are automatically triggered when predefined disruption thresholds are exceeded.

### Instant Digital Payouts
Compensation is transferred instantly through digital payment systems.

### Hyperlocal Risk Prediction
AI predicts disruption risks at city-zone level.

### Safe Zone Recommendation
Workers are guided to safer work zones with better delivery demand.

### Fraud Detection AI
Machine learning identifies abnormal claim patterns.

### Earnings Protection Dashboard
Workers can track coverage status, payouts, and disruption alerts.

---

# AI Components

### Risk Prediction Model
Predicts environmental disruption probability and calculates insurance premiums.

### Disruption Forecasting Model
Uses time-series analysis to forecast environmental events.

### Income Loss Prediction Model
Estimates potential income loss caused by disruptions.

### Fraud Detection Model
Uses anomaly detection to detect suspicious claim behavior.

---

# Parametric Triggers

Claims are triggered automatically when environmental thresholds are crossed.

| Trigger Type | Condition |
|--------------|-----------|
| Heavy Rain | Rainfall > 40 mm |
| Extreme Heat | Temperature > 42°C |
| Severe Pollution | AQI > 350 |
| Flood Alerts | Government disaster alerts |
| Traffic Disruptions | Major road closures |

---

# Weekly Premium Model

Affordable micro-insurance for gig workers.

| Risk Zone | Weekly Premium | Coverage |
|----------|---------------|----------|
| Low Risk | ₹15 | ₹300 |
| Medium Risk | ₹25 | ₹500 |
| High Risk | ₹40 | ₹800 |

Premium values dynamically adjust based on disruption forecasts.

---

# System Architecture

![System Architecture](architecture.png)

The system follows a **microservice architecture** integrated with AI-driven decision models.

### Key Components

Worker Mobile App  
Used by gig workers to register, purchase insurance, and monitor payouts.

API Gateway  
Acts as the central communication layer between services.

Authentication Service  
Handles login and user identity management.

Policy Service  
Manages insurance policies and premium calculations.

Claim Engine  
Automatically triggers claim payouts when disruption thresholds are reached.

Risk Prediction AI  
Calculates disruption probability and premium pricing.

Fraud Detection AI  
Detects abnormal claim patterns.

External Data Sources  
Weather, pollution, and traffic APIs.

Admin Dashboard  
Provides analytics and system monitoring.

---

# System Workflow

![Workflow Diagram](workflow.png)

1 Worker registers on the mobile application  
2 AI analyzes location risk profile  
3 Worker purchases weekly insurance coverage  
4 Platform continuously monitors environmental APIs  
5 Disruption threshold is exceeded  
6 Claim engine verifies worker activity  
7 Claim automatically approved  
8 Instant payout sent to worker

---

# Technology Stack

### Frontend
React

### Backend
Node.js / Python Flask

### Database
MongoDB

### Artificial Intelligence

Python  
Scikit-learn  
Time Series Forecasting

### APIs

OpenWeather API  
Air Quality Index API  
Traffic APIs

### Payment Integration

Razorpay Sandbox

---

# Development Roadmap

### Phase 1
Research, ideation, system architecture, and documentation.

### Phase 2
Development of core platform including authentication, policy management, and automated claim system.

### Phase 3
Advanced AI models, fraud detection, analytics dashboards, and real-time disruption prediction.

---

# Future Enhancements

### AI Disruption Forecast Engine
Predicts disruptions before they occur and warns workers.

### Earnings Stability Score
AI score representing financial stability of gig workers.

### Community Risk Reporting
Workers can report disruptions like flooded roads or protests.

### Hyperlocal Risk Heatmap
Interactive map showing safe zones and high-risk areas.

### Micro Emergency Savings Wallet
Optional emergency savings feature for gig workers.

---

# Expected Impact

ShieldGig AI aims to provide a **financial safety net for gig workers**.

Benefits include:

- Reduced income volatility
- Faster claim settlements
- Improved worker safety
- Data-driven insurance systems
- Scalable parametric insurance model

---

# Project Status

Prototype Development Phase

---

# Team

DEVTrails Hackathon 2026
