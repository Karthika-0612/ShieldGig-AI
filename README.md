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

---

# Core Features

- AI-based dynamic premium calculation  
- Real-time disruption monitoring  
- Automated parametric claim triggers  
- Instant payout system  
- Hyperlocal risk prediction  
- Safe zone recommendation system  
- Fraud detection using AI  
- Earnings protection dashboard  

---

# AI Components

### Risk Prediction Model  
Calculates disruption probability and premium pricing.

### Disruption Forecasting Model  
Predicts weather and environmental disruptions.

### Income Loss Prediction Model  
Estimates earnings loss due to disruptions.

### Fraud Detection Model  
Detects anomalies and suspicious claim behavior.

---

# Parametric Triggers

| Trigger Type | Condition |
|--------------|-----------|
| Heavy Rain | Rainfall > 40 mm |
| Extreme Heat | Temperature > 42°C |
| Severe Pollution | AQI > 350 |
| Flood Alerts | Government alerts |
| Traffic Disruptions | Road closures |

---

# Weekly Premium Model

| Risk Zone | Weekly Premium | Coverage |
|----------|---------------|----------|
| Low Risk | ₹15 | ₹300 |
| Medium Risk | ₹25 | ₹500 |
| High Risk | ₹40 | ₹800 |

---

# System Architecture

![System Architecture](architecture.png)

---

# System Workflow

![Workflow Diagram](workflow.png)

1 Worker registers  
2 AI calculates risk  
3 Worker purchases coverage  
4 System monitors APIs  
5 Disruption detected  
6 Claim triggered  
7 Claim verified  
8 Instant payout  

---

# 🚨 Adversarial Defense & Anti-Spoofing Strategy

## 1. Differentiation Strategy

ShieldGig AI uses a **multi-layer AI trust scoring system** instead of relying only on GPS.

### Genuine Worker Signals
- Continuous movement patterns  
- Active delivery logs  
- Location matches environmental data  

### Fraud Signals
- Static or unrealistic movement  
- No delivery activity  
- Location mismatch with real conditions  

Each claim is evaluated using a **Trust Score** before approval.

---

## 2. Multi-Dimensional Data Analysis

### Behavioral Data
- Delivery activity logs  
- Work duration  
- Movement patterns  

### Device Intelligence
- Device ID consistency  
- Sensor data (accelerometer, gyroscope)  
- App usage patterns  

### Environmental Validation
- Weather API vs user location  
- Nearby user consistency  
- Area-level disruption  

### Network Pattern Detection
- Multiple claims from same area  
- Sudden spikes  
- Coordinated timing patterns  

### Historical Trust Profile
- Past claims  
- Fraud history  
- Reliability score  

---

## 3. AI Fraud Detection Models

### Anomaly Detection
Detects:
- Impossible movement speeds  
- Static activity during claims  
- Abnormal claim frequency  

### Pattern Recognition
Identifies:
- Coordinated fraud groups  
- Similar timestamps  
- Clustered claims  

### Risk Scoring

Low Risk → Auto Approved  
Medium Risk → Additional Verification  
High Risk → Delayed / Manual Review  

---

## 4. UX Balance Strategy

### Soft Verification
Claims are not rejected immediately.

### Grace Approval
Trusted users get provisional approval.

### Delayed Validation
Verification continues without blocking payouts.

### Transparent Communication
Users are informed clearly about verification status.

---

## 5. System Resilience

- Multi-layer validation (not GPS dependent)  
- Real-time fraud monitoring  
- Adaptive AI models  
- Rate limiting for suspicious activity  

---

# Technology Stack

Frontend: React  
Backend: Node.js / Python Flask  
Database: MongoDB  
AI/ML: Python, Scikit-learn  

APIs:
- OpenWeather API  
- AQI API  

Payments:
- Razorpay Sandbox  

---

# Development Roadmap

### Phase 1
Research and design

### Phase 2
Core development

### Phase 3
AI + advanced analytics

---

# Future Enhancements

- AI disruption forecasting  
- Earnings stability score  
- Community risk reporting  
- Hyperlocal heatmaps  
- Emergency savings wallet  

---

# Expected Impact

- Reduced income volatility  
- Faster payouts  
- Fraud-resistant insurance  
- Better worker decision-making  

---

# Project Status

Prototype Phase

---

# Team

DEVTrails Hackathon 2026
