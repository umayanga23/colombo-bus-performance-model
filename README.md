# colombo-bus-performance-model
# 🚍 Colombo City Bus Network Performance Modeling and Simulation

## 📘 Project Overview
This project presents a **Performance Modeling and Evaluation** of the **Colombo City Bus Network**, a real-world public transportation system.  
The goal is to analyze passenger flow, identify bottlenecks, and evaluate key performance metrics such as **waiting time**, **bus occupancy**, and **route throughput** using both **Queueing Theory** and **Discrete Event Simulation (DES)**.

---

## 🎯 Objectives
- Analyze passenger waiting times and queue lengths at major Colombo bus stops.  
- Evaluate bus service performance using analytical and simulation models.  
- Identify congestion points and potential improvements in route scheduling.  
- Model the system under different traffic conditions and passenger loads.  

---

## ⚙️ Methodology

### **1. Queueing Theory**
Used for analytical modeling of passenger flow.
- **Model Type:** M/M/1 and M/M/c Queues  
- **Parameters:**
  - λ (Passenger Arrival Rate)
  - μ (Service Rate / Bus Boarding Rate)
- **Formulas:**
  - Average Waiting Time:  `Wq = λ / (μ * (μ - λ))`
  - Average Queue Length:  `Lq = λ² / (μ * (μ - λ))`

### **2. Discrete Event Simulation (DES)**
Simulates real-time operations of buses and passenger arrivals using PHP.
- Models bus arrivals, delays, and passenger boarding dynamically.
- Generates key outputs:
  - Average waiting time per stop
  - Total throughput per route
  - Average bus occupancy

---

## 📂 Project Structure
├── bus_dataset.csv # Dataset file
