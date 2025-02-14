# Flask System Monitoring App

## Overview
This is a **Flask-based System Monitoring App** that provides real-time CPU and Memory utilization of your server. The app utilizes **psutil** to fetch system metrics and displays them using an interactive web interface with **Plotly graphs**.

## Features
✅ Real-time CPU and Memory monitoring  
✅ User-friendly web interface  
✅ Alerts when usage exceeds 80%  
✅ Graphical representation of system metrics  
✅ Lightweight and easy to deploy  

## Technologies Used
- **Flask** - Backend framework for handling requests
- **psutil** - Fetch system resource usage
- **Plotly.js** - Interactive graphs for visualization
- **HTML/CSS** - Frontend for UI design

## Installation & Usage

### Prerequisites
Ensure you have **Python 3** installed on your system.

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/flask-monitoring-app.git
cd flask-monitoring-app
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```sh
python app.py
```

### 4️⃣ Access the Web Interface
Open your browser and go to:  
➡ **http://127.0.0.1:8000/**

## Deployment
You can deploy this app using **Docker, Kubernetes, or cloud platforms like AWS/GCP/Azure**.

### Docker Deployment
```sh
docker build -t flask-monitoring-app .
docker run -p 8000:8000 flask-monitoring-app
```

### Kubernetes Deployment
Refer to the `deployment.yaml` and `service.yaml` files in this repo.

## Contributing
Feel free to contribute! Open an issue or submit a pull request.

## License
This project is licensed under the **MIT License**.

---
### 📌 Created by: Your Name

Sarthak
