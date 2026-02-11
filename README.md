Birthdays
A web-based application to track and manage birthdays, developed as a solution for the CS50 "Birthdays" problem set. This application allows users to view a list of saved birthdays and add new ones to a database.

Description
This project uses Flask (a Python microframework) to serve a dynamic web page where users can interact with a SQLite database. The application features a simple frontend built with HTML and CSS, and a backend that handles data insertion and retrieval.

Tech Stack
Backend: Python, Flask

Database: SQLite (managed via the CS50 SQL library)

Frontend: HTML, CSS

Project Structure
app.py: The main controller script. It handles routing (/) and methods (GET to display birthdays, POST to add new ones).

birthdays.db: A SQLite database containing a birthdays table with columns for id, name, month, and day.

index.html: The HTML template that provides the form for inputting data and a table for displaying the list of birthdays.

styles.css: Custom CSS to style the table and form elements.
