# 🛰️ E-Transit – Dynamic Trip/Route Assigner

This is the **Dynamic Trip & Route Assigner** backend service, written in **Python**, and is a critical part of the **E-Transit** system.

It dynamically allocates trips and routes based on incoming GPS data or pre-scheduled information, and provides a real-time API for integration with the frontend app.

---

## ⚙️ Tech Stack

- Python 3.x
- Flask (or FastAPI, depending on your implementation)
- GTFS/GeoJSON
- REST API

---

## 📦 Prerequisites

- Python 3.x installed
- `requirements.txt` file available in the repo

---

### 🛠️ Setup Instructions
##1. Clone the Repository
```bash
git clone https://github.com/your-username/trip-route-assigner.git
cd trip-route-assigner
```

## 2. Install Dependencies
```bash
pip install -r requirements.txt
```
## 3. Run the API Server
```bash
python main.py
```
## API will be available at: http://127.0.0.1:3000/

### U Need to add this API in frontend .env.
