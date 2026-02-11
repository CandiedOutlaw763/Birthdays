# Birthdays 🎂

This repository contains my solution for the **Birthdays** problem set from [CS50: Introduction to Computer Science](https://cs50.harvard.edu/x/). It is a simple web application that allows users to track and manage a list of birthdays using a SQLite database.

## 📝 Description

The goal of this project was to build a web application using **Flask** (a Python microframework) to enable users to:
1.  **View** a list of people and their birthdays.
2.  **Add** new entries to the database via a web form.
3.  Ensure data persistence using a **SQLite** database.

## 🛠️ Built With

* **Python** (Backend logic)
* **Flask** (Web framework)
* **SQL** (SQLite database for storage)
* **HTML/CSS** (Frontend structure and styling)

## 📂 Project Structure

* `app.py`: The main controller application. It handles the web routes (`/`) and interacts with the SQL database using the CS50 library.
* `birthdays.db`: A SQLite database containing the `birthdays` table (columns: `id`, `name`, `month`, `day`).
* `index.html`: The HTML template that renders the form and the table of birthdays.
* `styles.css`: CSS file for styling the application.

