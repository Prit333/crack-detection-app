# Crack Detection in Buildings

This is a web-based application designed to detect and localize cracks in concrete surfaces. It features image upload, prediction analysis, history tracking, and a clear history option. This README provides instructions to set up and run the application from the shared GitHub repository.

## Installation

Clone the Repository

```bash
git clone https://github.com/Prit333/crack-detection-app.git
cd crack-detection-app
```

Install Dependencies

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install --upgrade pip
pip install flask flask-sqlalchemy torch torchvision opencv-python pillow
```

Run the Application

```bash
cd webapp/backend
python app.py
```
    
