# Human Activity Recognition

End-to-end pipeline for human activity recognition using smartphone sensor data (UCI HAR Dataset).

## Problem Statement
Smartphone sensors (accelerometer, gyroscope) provide time-series data that can be used to classify human activities. Accurate recognition can improve usability in medtech, fitness, and context-aware applications

## Dataset

This project uses the [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones).

**License note:**
The dataset is distributed for non-commercial use only.
If you use it in publications, please cite:
Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz.
"A Public Domain Dataset for Human Activity Recognition Using Smartphones."
ESANN 2013, Bruges, Belgium, April 24-26, 2013.

## Proposed solution

- Data cleaning & normalization
- Exploratory Data Analysis (EDA) with visualization
- Feature engineering (statistical + frequency domain features)
- Baseline ML models (RandomForest, SVM)
- Deep Learning models (LSTM/GRU, CNN)
- Model evaluation (precision, recall, F1, confusion matrix)
- Deployment with FastAPI + Docker

## Installation & Usage
### Requirements:
- Python >= 3.11
### Installation
```bash
pip install -r .\requirements.txt
```
### Usage

## Resources
- https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones - Dataset

## Contributing

Contributions available after previous contact.

## License

MIT License
“Code in this repository is licensed under MIT. The dataset has its own license and is not covered by MIT.”
