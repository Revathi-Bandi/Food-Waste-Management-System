# Food Waste Management System

## About the Project

The Food Waste Management System is a web-based application developed using Python Flask and MySQL. The main goal of this project is to reduce food waste by connecting food providers with people who need food.

The application provides a platform to manage food donations, food requirements, and food bookings.

## Technologies Used

- **Backend:** Python, Flask
- **Database:** MySQL
- **Frontend:** HTML, CSS, JavaScript
- **Libraries:** NumPy, Scikit-learn, Folium, Geopy

## Features

- User registration and login
- Admin management
- Food donation management
- Food booking management
- Food provider management
- Food requirement management

## Project Structure

```text
Food-Waste-Management-System/
│
├── main.py
├── requirements.txt
├── README.md
├── static/
├── templates/
└── .gitignore
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/RevathiBandi/Food-Waste-Management-System.git
```

### 2. Navigate to the project folder

```bash
cd Food-Waste-Management-System
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure MySQL

- Install and start MySQL.
- Create a database named `food_waste`.
- Import the project database backup (provided separately).
- Configure your database credentials using environment variables.

### 5. Configure environment variables

Set these variables before starting the application:

- `FLASK_SECRET_KEY`
- `DB_HOST`
- `DB_USER`
- `DB_PASSWORD`
- `DB_NAME`

### 6. Run the application

```bash
python main.py
```

### 7. Open in your browser

```text
http://127.0.0.1:5000
```

## Database Tables

The project uses the following MySQL tables:

- fo_admin
- fo_booking
- fo_donate
- fo_food
- fo_need
- fo_post
- fo_provider
- fo_user

## Author

**Revathi Bandi**