# SmartEnergy AI

### AI-Powered Smart Energy Optimization Platform

---

##Live Demo

**Try the App:**
https://smartenergy-ai-optimization-platform-5pt7svmrpgr8uwpwjjgsvy.streamlit.app/

---

## Overview

**SmartEnergy AI** is an end-to-end intelligent system that simulates real-world smart building environments and optimizes energy consumption using **Machine Learning + Swarm Intelligence (GWO & PSO)**.

Unlike traditional ML projects that stop at prediction, this platform delivers:

> **Prediction + Optimization + Decision Intelligence**

This makes it a **production-style AI system**, not just a model.

---

##Problem Statement

Commercial buildings waste **20–30% of energy** due to inefficient usage patterns, poor scheduling, and lack of intelligent optimization.

This system addresses that by:

* Predicting energy consumption patterns
* Identifying inefficiencies
* Optimizing usage dynamically

---

## Key Features

* Multi-building, multi-floor, multi-zone simulation
* ML-based energy prediction (Gradient Boosting)
* Optimization using:

  * Grey Wolf Optimization (GWO)
  * Particle Swarm Optimization (PSO)
* Peak load reduction strategies
* Model performance tracking (R² ≈ 0.93)
* Interactive Streamlit dashboard
* AI-driven insights & explainability

---

##System Architecture

```
IoT Data Simulation 
        ↓
Feature Engineering 
        ↓
ML Prediction Model 
        ↓
Optimization Engine (GWO / PSO) 
        ↓
AI Insights Dashboard
```

---

## Results & Performance

* Energy Reduction: **~3–5% (realistic optimization scenario)**
* Model Accuracy: **R² ≈ 0.93**
* Peak Load Reduction achieved via intelligent scheduling

---

##AI Insights Generated

The system automatically identifies:

* Peak energy demand periods
* Low consumption windows
* Key drivers (occupancy, time, zone usage)
* Optimization impact on system performance

---

##Business Impact

* Reduces operational energy costs
* Supports sustainability & carbon reduction
* Enables data-driven energy decisions
* Applicable to smart buildings, campuses, and enterprises

---

##Tech Stack

* **Python**
* **Scikit-learn**
* **Streamlit**
* **Pandas / NumPy**
* **Matplotlib**
* **Mealpy (GWO + PSO)**

---

##Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

##Future Improvements

* Integration with real IoT sensor data
* Real-time streaming (Kafka / MQTT)
* Reinforcement Learning for dynamic optimization
* Cloud deployment (AWS / Azure)
