# Workload Classification for Resource-Aware Scheduling in Superclouds

## Overview
Built a machine learning framework to classify workloads in supercloud environments using scheduler logs and GPU telemetry data. The system enables intelligent, resource-aware scheduling decisions to improve cloud efficiency and reduce contention.

## Tech Stack
- Python
- Machine Learning (Random Forest, SVM, ANN)
- Pandas, NumPy, Scikit-learn
- Data Visualization (Matplotlib, Seaborn)

## Key Features
- Integrated scheduler logs with GPU telemetry (DCGM)
- Feature engineering: CPU, Memory, GPU usage, job duration
- Compared multiple ML models
- Achieved highest performance with Random Forest (F1-score ~0.97)

## Results
- Random Forest outperformed other models
- Improved workload prediction accuracy significantly
- Enabled proactive scheduling decisions

## Dataset
- Kaggle cloud workload dataset
- GPU telemetry (DCGM metrics)

## Future Improvements
- Real-time model deployment
- Integration with Kubernetes scheduler
- Reinforcement learning-based scheduling
