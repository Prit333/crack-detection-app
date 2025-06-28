# Crack Detection in Buildings

This is a web-based application designed to detect and localize cracks in concrete surfaces. It features image upload, prediction analysis, history tracking, and a clear history option. This README provides instructions to set up and run the application from the shared GitHub repository.


## Installation

### 1. Clone the Repository
Clone the project from GitHub:
```bash
git clone https://github.com/Prit333/crack-detection-app.git
cd crack-detection-app

### 2. Install Dependencies
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install --upgrade pip
pip install flask flask-sqlalchemy torch torchvision opencv-python pillow

### 3.
Model File: Download or place the pre-trained model file crack_model_final.pth (approx. 89.99 MB) in the webapp/backend/ directory.

### 4. Run the Application
cd webapp/backend
python app.py