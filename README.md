# FundMate – Startup & Investor Connector Platform

## Overview

**FundMate** is a web platform designed to connect **startup founders with potential investors**.
The system provides a digital space where entrepreneurs can present their business ideas and investors can explore promising opportunities to fund innovative projects.

The platform aims to simplify the early-stage funding process by enabling direct interaction between startups and investors.

---

## Key Features

### For Startups

* Create and manage startup profiles
* Present business ideas and investment opportunities
* Submit funding requests
* Upload supporting documents

### For Investors

* Browse available startup opportunities
* Review startup profiles and proposals
* Connect with startup founders
* Evaluate investment opportunities

### Platform Features

* User authentication and account management
* Startup and investor dashboards
* Database-backed storage of proposals
* Web interface for interaction between users

---

## Technologies Used

### Backend

* Python
* Django
* SQLite (development database)

### Frontend

* HTML
* CSS
* JavaScript

### Deployment

* Gunicorn
* Procfile configuration
* Environment variables (.env)

---

## Project Structure

```
FundMate
│
├── backend/               # Backend application logic
├── frontend/              # Frontend interface
├── investor_app/          # Investor-related functionality
├── jobs/                  # Job or opportunity related modules
│
├── app.py                 # Application entry point
├── manage.py              # Django management script
├── requirements.txt       # Project dependencies
├── Procfile               # Deployment configuration
├── runtime.txt            # Runtime environment specification
├── .env                   # Environment variables
├── db.sqlite3             # Development database
└── README.md              # Project documentation
```

---

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Abby966/FundMate.git
cd FundMate
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run database migrations

```bash
python manage.py migrate
```

### 5. Run the development server

```bash
python manage.py runserver
```

Open in browser:

```
http://127.0.0.1:8000
```

---

## Future Improvements

Possible future features include:

* Real-time messaging between startups and investors
* AI-based startup recommendation system for investors
* Startup pitch evaluation tools
* Payment and investment tracking system
* Advanced analytics dashboard

---

## Project Goal

The goal of **FundMate** is to help bridge the gap between **innovative entrepreneurs and potential investors**, making it easier for startups to access funding and for investors to discover promising ventures.

---

## Author

**Abegail Chanyalew**
Computer Science Student
Interested in entrepreneurship, software systems, and technology-driven innovation platforms.
