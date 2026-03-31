# smartenergy-ai-optimization-platform
AI-powered Smart Energy Optimization platform that simulates enterprise IoT building data, predicts energy consumption using machine learning, and applies GWO/PSO optimization to reduce peak load and costs. Features a Streamlit dashboard with real-time insights, explainability, and decision support.
# SmartEnergy AI  
### Enterprise AI-Powered Energy Optimization Platform

---

## Overview

SmartEnergy AI is an end-to-end **AI-driven energy optimization platform** designed to simulate real-world smart building environments and optimize energy consumption using machine learning and swarm-based optimization techniques.

Unlike traditional ML projects that stop at prediction, this system integrates **prediction + optimization + decision intelligence**, making it closer to a real-world enterprise AI application.

---

## Key Capabilities

- Multi-building, multi-floor, multi-zone simulation  
- Machine Learning-based energy prediction (Gradient Boosting)  
- Optimization using **GWO (Grey Wolf Optimization)** and **PSO (Particle Swarm Optimization)**  
- Interactive SaaS-style dashboard using Streamlit  
- Model explainability (feature importance)  
- Model performance tracking (R² score ~0.93)  
- Energy savings, cost analysis & sustainability insights  

---

##  System Architecture
IoT Data Simulation → Feature Engineering → ML Model → Optimization Engine → AI Insights Dashboard

---

## Optimization Strategy

The system uses **metaheuristic optimization algorithms**:

- **GWO (Grey Wolf Optimization)**  
- **PSO (Particle Swarm Optimization)**  

These algorithms identify optimal time slots to:

- Reduce peak energy consumption  
- Shift load intelligently  
- Improve operational efficiency  

---

## Sample Results

- ⚡ Energy Reduction: ~3–5% (realistic optimization)  
- 📈 Model Accuracy: R² ≈ 0.93  
- 🔻 Peak Load Reduction achieved through scheduling  

---

## AI Insights

The system automatically identifies:

- Peak energy demand hours  
- Low consumption periods  
- Key drivers of energy usage (occupancy, time, etc.)  
- Optimization impact on system behavior  

---

## Business Impact

- Enables **data-driven decision making**  
- Reduces operational energy costs  
- Supports **sustainability and carbon reduction goals**  
- Demonstrates real-world applicability of AI in smart infrastructure  

---

## Tech Stack

- Python  
- Streamlit  
- Scikit-learn  
- NumPy / Pandas  
- Matplotlib  
- Mealpy (GWO + PSO)  

---

## Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py

