
# 🏥 Smart Clinic Management System | Streamlit Web App

A lightweight and interactive **Clinic Management & Appointment Booking System** built with **Python** and **Streamlit**.

The application provides a complete digital clinic experience where patients can book appointments, send feedback, request emergency services, while administrators can manage schedules, records, and clinic operations through a dedicated dashboard.

---

## ✨ Features

### 🏠 Patient Interface

- **Home Dashboard**
  - Welcome page introducing the clinic services and available features.

- **📅 Appointment Booking**
  - Dynamic appointment system.
  - Patients can select:
    - Medical specialty
    - Available doctors
    - Available time slots

- **📋 Appointment Records**
  - Displays successfully booked appointments.
  - Provides a clear overview of clinic bookings.

- **📝 Feedback System**
  - Collect patient reviews, experiences, and messages.

- **🚑 Emergency Services**
  - Instant ambulance request system.
  - Automatic location tracking.
  - Emergency requests are sent to the admin dashboard.

---

## 🛠 Admin Dashboard

A protected management panel that allows administrators to:

- 📊 View appointment records
- 📝 Monitor patient feedback
- 👨‍⚕️ Manage doctors' schedules
- ➕ Add available time slots
- ➖ Remove unavailable slots
- 🚑 Track ambulance requests in real time

---

## 🧰 Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **Session State Management**
- **Dynamic UI Components**

---

## 🚀 Installation & Setup

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone <repository-url>
````

### 2. Install Dependencies

Install the required libraries:

```bash
pip install -r requirements.txt
```

### 3. Run the Application

Start the Streamlit server:

```bash
streamlit run app.py
```

The application will open automatically in your browser:

```
http://localhost:8501
```

---

## 📁 Project Structure

```text
Clinic-Management-System/
│
├── app.py                  # Main Streamlit application
│
├── appointment_manager.py  # Backend logic and booking management
│
├── requirements.txt        # Project dependencies
│
└── README.md               # Documentation
```

---

## 🔐 Admin Access

The project includes an admin dashboard for clinic management.

> Demo credentials are available inside the project configuration.

---

## ⚠️ Data Storage Note

Currently, the application uses **Streamlit Session State** for data management.

This means:

* Data is stored temporarily in memory.
* Information resets when the application session ends.

Future improvements may include:

* Database integration
* User authentication
* Cloud deployment
* Real-time notifications

---

## 🎯 Project Purpose

This project was created for **educational and demonstration purposes** to showcase:

* Streamlit web application development
* Python backend logic
* Interactive UI design
* Healthcare system prototyping

---

## 👨‍💻 Author

**Adel Galal**

AI Student • C++ Developer • Creator

```

