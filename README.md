# Model Deployment with Docker & Flask

## Steps
1. Build image:
   docker build -t model_api .

2. Run container:
   docker run -p 5000:5000 model_api

## Features
- Flask API for ML model predictions
- Dockerized environment (portable & reproducible)
- TensorFlow + NumPy support
