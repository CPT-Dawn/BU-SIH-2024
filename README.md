# AI-Driven Traffic Light Simulation 🚦

This repository contains the project developed for **Smart India Hackathon (SIH)**, where we created a traffic simulation using **AI/ML models** to dynamically adjust traffic lights based on real-time traffic conditions. The system aims to optimize traffic flow and reduce congestion at intersections by adjusting red light durations according to traffic density and patterns.

## 🚀 Project Overview

In urban areas, traffic congestion is a major problem. Conventional traffic light systems work on a fixed time-based schedule, leading to inefficiencies. Our AI-driven solution leverages machine learning to analyze traffic data and adjust the timing of red lights dynamically, thereby improving traffic flow and reducing waiting time at intersections.

### Key Features
- **Dynamic Traffic Light Control**: Red light timing is adjusted in real-time based on traffic conditions.
- **Machine Learning Integration**: Our AI model predicts traffic flow and optimizes signal times.
- **Simulation Visualization**: A traffic simulation was developed to showcase the effectiveness of our solution.
- **Scalable Design**: The solution is scalable and can be adapted for any number of intersections.
  
## 🧠 AI/ML Approach

Our solution leverages **traffic pattern analysis** through AI and ML algorithms:
- **Traffic Density Prediction**: Using historical and real-time traffic data, the model predicts the expected density at each intersection.
- **Dynamic Signal Control**: Based on predictions, red light durations are dynamically updated to optimize flow.
  
### Technologies Used:
- **Python** for backend AI/ML model development.
- **TensorFlow/Keras** for building and training the machine learning models.
- **OpenCV** for traffic detection in simulation.
- **Pygame** for traffic simulation and visualization.
- **Flask** for integrating the AI/ML models with the simulation interface.

## 📊 How It Works

1. **Traffic Detection**: The simulation detects traffic flow using visual inputs.
2. **Model Prediction**: AI/ML model processes the input data to predict congestion levels.
3. **Traffic Light Adjustment**: Based on the prediction, the signal timing is dynamically updated.
4. **Simulation Visualization**: A visual representation of traffic flow and the corresponding red light adjustments is provided.

## 🎮 Simulation

To demonstrate how the solution works, we created a **traffic simulation** using Pygame that displays vehicles moving across intersections and how the AI updates red light durations in real-time.
