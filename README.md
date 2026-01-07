# 🚦 CityFlow: Sense Predict Move

Traffic is something we all deal with every day — waiting at signals, getting stuck in jams, or trying to figure out the fastest route. **CityFlow** is my attempt to make sense of that chaos.  

This project uses data and machine learning to predict traffic flow patterns and present them in a simple, interactive web app. The idea is to help cities (and people like us!) move smarter, not just faster.

---

## ✨ What this project does
- 📊 **Predicts traffic flow** using real-world datasets
- 🌍 **Visualizes maps** with hotspots and routes
- 🖥️ **Web interface** built with Flask, so anyone can interact with it
- 🗂️ **Database** for storing and analyzing traffic data
- 🎨 **Clean design** with templates and static assets

---

## 🗂️ Project Structure
cityflow/
│── app.py                 # Main Flask application
│── static/               # CSS, JS, and map HTML files
│── templates/            # Jinja2 HTML templates
│── merged_dataset.xlsx   # Traffic dataset
│── traffic_flow.db       # Database file
│── venv/                 # Virtual environment (ignored in Git)


---

## 🛠️ Tech Stack
- **Python** (Flask, Pandas, NumPy)
- **HTML/CSS/JavaScript** for frontend
- **SQLite** for database storage
- **Excel datasets** for training and analysis

---

## 🚀 How to run it
1. Clone the repo:
    ```bash
    git clone https://github.com/GaminiPraveena/CityFlow-Sense-Predict-Move.git
   cd CityFlow-Sense-Predict-Move
    
2. Create a virtual environment:
    python -m venv venv
    venv\Scripts\activate   # On Windows
    source venv/bin/activate # On Linux/Mac
   
3.Install dependencies:
    pip install -r requirements.txt
    
4.Run the app:
    python app.py
    
5.Open your browser at http://127.0.0.1:5000/
  
