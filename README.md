# 🍲 Food Waste Management System

A web-based Food Waste Management System developed using **Python Flask and MySQL**. The application aims to reduce food waste by connecting food providers with people who need food.

## 📌 About the Project

Food waste is a major problem. This project provides a platform where food providers can manage food donations and people in need can find and book available food.

The application supports food donations, food requirements, and food bookings through a web-based interface.

## ✨ Features

- User registration and login
- Admin management
- Food donation management
- Food booking management
- Food requirement management
- Database-driven information management

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Backend | Python, Flask |
| Database | MySQL |
| Frontend | HTML, CSS, JavaScript |
| Libraries | NumPy, Scikit-learn, Folium, Geopy |

## 📂 Project Structure

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

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Revathi-Bandi/Food-Waste-Management-System.git
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

- Install and start MySQL Server.
- Create a database named `food_waste`.
- Import the project SQL database backup.
- Configure your database credentials using environment variables.

### 5. Configure environment variables

Set the following variables before running the application:

- `FLASK_SECRET_KEY`
- `DB_HOST`
- `DB_USER`
- `DB_PASSWORD`
- `DB_NAME`

Use your own local database credentials. Never upload passwords or secret keys to GitHub.

### 6. Run the application

```bash
python main.py
```

### 7. Open the application

Visit the following address in your browser:

```text
http://127.0.0.1:5000
```

## 🗄️ Database Tables

The project uses the following MySQL tables:

- `fo_admin`
- `fo_booking`
- `fo_donate`
- `fo_food`
- `fo_need`
- `fo_post`
- `fo_provider`
- `fo_user`

## 👩‍💻 Author

**Revathi Bandi**

Master's Student in Data Science  
Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU), Germany

[GitHub Profile](https://github.com/Revathi-Bandi)

## 📄 License

This project is available for educational and learning purposes.
