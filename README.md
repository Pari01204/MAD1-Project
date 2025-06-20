# MAD1-Project
# 🚗 Vehicle Parking App - V1

A multi-user vehicle parking management system for 4-wheelers, built using **Flask**, **SQLite**, and **Bootstrap**.

## 🔧 Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML, CSS, Bootstrap, Jinja2
* **Database:** SQLite (programmatically created)

## 👥 Roles

### Admin

* No registration required (default superuser)
* Can add/edit/delete parking lots
* Each lot can have multiple parking spots and custom pricing
* Can view all users and spot statuses

### User

* Can register and log in
* Can book and release parking spots
* Parking spot allocation is automatic (first available)
* Parking duration and cost is tracked

## 🏗️ Features

* Admin/User login and dashboards
* Automated creation of parking spots
* Real-time spot availability status
* Timestamps for parking check-in and check-out
* Responsive UI with Bootstrap
* Optional: Chart.js for visual summaries

## ⚙️ How to Run

1. **Install dependencies**

   ```bash
   pip install flask flask_sqlalchemy flask_login
   ```

2. **Initialize the database**

   ```bash
   python db_init.py
   ```

3. **Run the app**

   ```bash
   python app.py
   ```

4. **Visit in browser**

   ```
   http://localhost:5000
   ```

## 🧑‍💻 Admin Credentials

* **Username:** `admin`
* **Password:** `admin123` *(change in `db_init.py` if needed)*

## 📊 Database Models

Includes models for:

* User
* ParkingLot
* ParkingSpot
* Reservation


