# Lab7 flask

Flask Sign Up/Sign In Interface

Project Overview

This project implements a Sign Up/Sign In interface using Flask and SQLite. The application includes basic and required features of a simple login/signup page. Additional functionalities and aesthetic improvements have also been made.

Features

Sign In Page

	•	Users can enter their username and password to sign in.
	•	Upon successful sign-in, users are redirected to the secret page.
	•	The username and password are saved in the SQLite database.

Sign Up Page

	•	Users can register by providing their first name, last name, email address, password, and confirm password.
	•	Passwords are validated to meet the criteria:
	•	Must contain a lowercase letter.
	•	Must contain an uppercase letter.
	•	Must end in a number.
	•	Must be at least 8 characters long.
	•	Passwords are hashed using SHA-256 before storing in the database.
	•	Email addresses are checked to ensure they are unique.
	•	Upon successful registration, users are redirected to the thank you page.

 Project Structure 
 lab7_flask_app/
│
|--users.db
├── app.py
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── secretpage.html
│   └── thankyou.html

Prerequisites

	•	Python 3.7+
	•	Flask
	•	Flask-SQLAlchemy
	•	Werkzeug

Running the Application

python app.py

Open your browser and navigate to:
http://127.0.0.1:5000 



Lab08 React To-Do List Application
Project Overview
This project extends a basic React To-Do List application with additional features including task prioritization, completion, filtering, and a visual background. The application allows users to manage tasks with various priorities, mark them as completed or incomplete, and filter them based on their status. The design includes a background image, a header with a logo, and a footer with contact information.

Features
To-Do List Management
Add New Tasks:

Users can enter a new task and select a priority level (High, Medium, Low).
Tasks are added to the list with the selected priority.
Edit Tasks:

Users can edit existing tasks by clicking an "Edit" button.
The task text can be updated and saved.
Delete Tasks:

Users can delete tasks by clicking a "Delete" button.
Toggle Task Completion:

Users can mark tasks as completed or incomplete by clicking on the task.
Filter Tasks:

Users can filter tasks by All, Completed, or Incomplete.
Visual Enhancements
Background Image:

The application uses a background image to enhance visual appeal.
Header and Footer:

The header includes a logo and the application title.
The footer displays contact information and a copyright notice.
Project Structure
java
Copy code
todofinal/
│
├── public/
│   ├── index.html
│
├── src/
│   ├── App.js
│   ├── App.css
│
├── package.json
├── package-lock.json
Prerequisites
Node.js
npm (Node Package Manager)
Running the Application
Navigate to the project directory:

bash
Copy code
cd ~/Desktop/todofinal
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
npm start
Open your browser and navigate to:

arduino
Copy code
http://localhost:3000
Usage
Add New Task: Enter a new task and select a priority level, then click "Add Task."
Edit Task: Click the "Edit" button next to a task to modify its text.
Delete Task: Click the "Delete" button next to a task to remove it from the list.
Toggle Completion: Click on the task to mark it as completed or incomplete.
Filter Tasks: Use the filter buttons to view all tasks, only completed tasks, or only incomplete tasks.


Usage

	•	Sign In: Enter your username and password to access the secret page.
	•	Sign Up: Register a new account by filling in the required fields. Ensure that your password meets the specified criteria.

