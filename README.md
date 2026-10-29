# Student Academic Tracker

A Python-based web application for organizing student information, tracking attendance, managing assessment marks, and visualizing academic performance.

## Project Overview

The Student Academic Tracker provides an interactive dashboard that displays important academic statistics and visualizations. It uses Streamlit for the user interface and SQLite for database storage.

## Features

- Student record management
- Attendance tracking and percentage calculation
- Assessment marks and percentage calculation
- Dashboard with academic performance statistics
- Subject-wise performance visualization
- Attendance overview chart
- SQLite database connectivity
- Data validation and persistent local storage

## Technologies Used

- Python
- Streamlit
- SQLite
- Pandas
- Plotly

## Project Structure

- `app.py` — Main Streamlit application
- `database.py` — Database connection, table initialization, and database functions
- `academic_tracker.db` — SQLite database file, if included
- `requirements.txt` — Required Python packages
- `README.md` — Project documentation

## Installation and Setup

1. Install Python on your computer.
2. Download or clone this repository.
3. Open the project folder in VS Code.
4. Install the required packages:

   `py -m pip install -r requirements.txt`

5. Start the application:

   `py -m streamlit run app.py`

6. Open the local URL displayed in the terminal.

## Database

The application uses SQLite to store student information, attendance records, and assessment marks.

## Developed By

- Geetika — 251302121
- Ishika — 251302122

## Academic Project

B.Tech Computer Science and Engineering (Artificial Intelligence and Machine Learning)

SGT University, Gurugram, Haryana

## Future Enhancements

- User authentication and role-based access
- Downloadable academic reports
- Attendance alerts
- Advanced performance analytics
- Secure multi-user deployment
