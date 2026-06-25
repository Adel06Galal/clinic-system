# 🏥 Clinic Management System (Streamlit Web App)

A lightweight, interactive Clinic Management and Appointment Booking System built using **Python** and **Streamlit**. This application allows patients to book slots, submit feedback, and request emergency services, while providing an administrative dashboard for clinic management.

---

## ✨ Features

* **🏠 Home Page:** A welcoming dashboard for patients introducing the clinic's premium medical services.
* **📅 Book Appointment:** Real-time appointment booking where patients can select specialties, available doctors, and open time slots dynamically.
* **📋 Appointment Records:** A transparent overview displaying all successfully booked appointment records.
* **📝 Feedback Form:** A section dedicated to collecting patient experiences, reviews, and messages.
* **🚑 Emergency Services:** An urgent care feature allowing instant ambulance requests with automated location tracking and admin notification.
* **🛠 Admin Dashboard:** A secure panel protected by an access password (`123456`) that enables administrators to:
    * View comprehensive appointment spreadsheets and feedback logs.
    * Dynamically manage doctor schedules by adding or removing time slots.
    * Monitor active ambulance dispatch logs in real-time.

---

## 🚀 Installation & Setup

Follow these simple steps to get the project up and running locally on your machine:

### 1. Install Dependencies

Install all the required Python libraries using the provided `requirements.txt` file:
```bash
pip install -r requirements.txt

2. Run the Application
Launch the Streamlit server by running the main entry file app.py:

streamlit run app.py
Once executed, the local web server will automatically open the app in your browser at http://localhost:8501.

📁 Project Structure
The project consists of the following core files:

Plaintext
├── app.py                  # The main application entry point handling UI components and pages (Streamlit).
├── appointment_manager.py  # The backend logic handling data management, state manipulation, and booking rules.
└── requirements.txt        # The dependencies file specifying packages required for execution.
