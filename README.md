# # 🚀 Simple Flask App 

This is a basic **Flask web app** running inside a **Docker container**, built for practice with Flask, Docker, Git, and virtual environments.

---

## 🛠 How to Run Locally

1. **Clone the repository**
```bash
git clone git@github.com:Xhukri/Dockerfile.git
cd Dockerfile
```

2. **Set up a Python virtual environment**
```bash
python3 -m venv venv
source venv/bin/activate  # On Linux/macOS/WSL
```

3. **Install Flask**
```bash
pip install flask
```

4. **Run the Flask app**
```bash
python3 app.py
```
Visit [http://127.0.0.1:5002](http://127.0.0.1:5002) in your browser.

---

## 🐳 How to Run with Docker

1. **Build the Docker image**
```bash
docker build -t simple-flask-app .
```

2. **Run the Docker container**
```bash
docker run -p 5002:5002 simple-flask-app
```
Visit [http://localhost:5002](http://localhost:5002) in your browser.

---

## 📖 What Was Learned

- Flask basics
- Managing Python virtual environments
- Dockerizing Flask apps
- Git and GitHub SSH setup

---
