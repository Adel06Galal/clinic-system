# 🏥 Smart Clinic Management System | Streamlit Web App

A lightweight and interactive **Clinic Management & Appointment Booking System** built with **Python** and **Streamlit**.

The application provides a complete digital clinic experience where patients can book appointments, submit feedback, request emergency services, while administrators can manage schedules, records, and clinic operations through a dedicated dashboard.

---

## ✨ Features

## 🏠 Patient Interface

### 📅 Appointment Booking
- Dynamic appointment booking system.
- Patients can choose:
  - Medical specialty
  - Available doctor
  - Available time slot

### 📋 Appointment Records
- View all successful appointments.
- Organized booking information.

### 📝 Feedback System
- Collect patient reviews and messages.
- Store user experiences.

### 🚑 Emergency Services
- Instant ambulance requests.
- Automatic location tracking.
- Admin receives emergency notifications.

---

# 🛠 Admin Dashboard

A protected admin panel that allows:

- 📊 Viewing appointments
- 📝 Managing feedback
- 👨‍⚕️ Managing doctor schedules
- ➕ Adding available slots
- ➖ Removing unavailable slots
- 🚑 Monitoring ambulance requests

---

# 🧰 Tech Stack

- 🐍 Python
- 🎈 Streamlit
- 📊 Pandas
- 🔄 Session State Management
- 🎨 Dynamic UI Components

---

# 🚀 Installation & Setup

## 1. Clone Repository

```bash
git clone <repository-url>
```

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run Application

```bash
streamlit run app.py
```

Open:

```bash
http://localhost:8501
```

---
```md
# 📁 Project Structure

```text
Clinic-Management-System/

│
├── app.py
│   └── Main Streamlit application

├── appointment_manager.py
│   └── Booking logic and data management

├── requirements.txt
│   └── Required Python packages

└── README.md
   └── Documentation
```
```
```
---

# 🔐 Admin Access

The project contains an admin dashboard for clinic management.

> Demo credentials are available inside the project configuration.

---

# ⚠️ Data Storage

Currently the application uses:

**Streamlit Session State**

Data is stored temporarily in memory and will reset when the session ends.

Future improvements:

* Database integration
* Authentication system
* Cloud deployment
* Real-time notifications

---

# 🎯 Project Purpose

This project was developed for educational and demonstration purposes to showcase:

* Streamlit web applications
* Python backend development
* Interactive UI design
* Healthcare system prototyping

---

# 👨‍💻 Author

**Adel Galal**

AI Student • C++ Developer • Creator
