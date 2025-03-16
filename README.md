# PAYKRYPT - AI-Powered Fraud Detection System

## Overview
PAYKRYPT is an AI-powered fraud detection system that leverages **synthetic data generation, generative AI, deep learning models, and federated learning** to detect fraudulent transactions in real-time while preserving user privacy.


## Problem Statement
We are addressing the issue of financial fraud detection. Traditional fraud detection systems often struggle with accuracy due to imbalanced datasets and limited real-world fraud examples. Our project aims to improve fraud detection using generative AI, synthetic data, and federated learning while preserving data privacy.


## Solution
Our solution leverages **synthetic data generation, generative AI, and federated learning** to enhance fraud detection. We utilize **Duo-GAN with diffusion models** to create realistic synthetic transaction datasets. A combination of **CNNs, LSTMs, and GANs** is employed to detect fraud patterns in transactions. Furthermore, **federated AI with homomorphic encryption** ensures secure, collaborative fraud detection across multiple financial institutions.


## Technologies Used
- **Generative AI**: GANs, Duo-GAN, Diffusion Models for synthetic data generation.
- **Deep Learning**: CNNs, LSTMs for sequential fraud pattern detection.
- **Explainability Techniques**: SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations) for making fraud predictions interpretable.
- **Federated Learning with Homomorphic Encryption** for privacy-preserving fraud detection.
- **Backend**: Flask for developing the backend API to serve fraud detection results.
- **Frontend**: Jinja for rendering dynamic web pages and visualizing fraud detection insights.
- **Database**: PostgreSQL (or any suitable database for transaction logging).
- **Deployment**: Docker, FastAPI (optional).


## Why Our Solution Stands Out
Our solution stands out from existing alternatives due to the following reasons:
1. **Duo-GAN with diffusion models** improves synthetic data quality and reduces mode collapse issues.
2. **Integration of CNNs, LSTMs, and GANs** ensures more accurate and real-time fraud detection.
3. **Federated AI with homomorphic encryption** guarantees privacy-preserving fraud detection.
4. **Explainability using SHAP & LIME** ensures compliance with regulatory requirements.
5. **Cross-entity collaboration** through federated AI enables fraud detection without data exposure.
6. **Low Latency & High Accuracy**: Our system is optimized for real-time fraud detection with minimal delays and high fraud detection rates.


## Installation & Setup
### Clone the repository
```bash
git clone https://github.com/your-username/paykrypt.git
cd paykrypt
```

### Create a virtual environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Run the application
```bash
flask run
```
The application will be available at: **http://127.0.0.1:5000**


## Security & Privacy
- **Federated Learning** ensures no transaction data is shared between banks.  
- **Homomorphic Encryption** allows secure cross-institution fraud detection.  
- **Real-time monitoring** halts high-risk transactions before completion.  


## 👥 Contributors
- Krish Bansal  
- Mayank Jangid  
- Aditya Jha  
- Mauray Jain  
