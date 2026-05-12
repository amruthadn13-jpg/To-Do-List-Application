# To-Do List Application

## Project Overview

The To-Do List Application is a web-based task management application built using Flask and SQLite. It allows users to create tasks, mark tasks as completed, and delete tasks. All tasks are stored in a local SQLite database, ensuring data is preserved between application runs.

This project demonstrates core backend development concepts such as CRUD operations, database integration, form handling, and dynamic template rendering.

---

## Features

- Add new tasks
- View all tasks
- Mark tasks as completed
- Delete tasks
- Store tasks persistently using SQLite

---

## Technologies Used

- Python
- Flask
- SQLite
- HTML (Jinja Templates)

---

## Project Structure

todo_app/
│
├── app.py
├── todo.db
├── requirements.txt
├── templates/
│   └── index.html
└── README.md

---

## Database Schema

### tasks Table

| Column     | Type    | Description |
|----------|----------|-------------|
| id       | INTEGER  | Primary key with auto-increment |
| title    | TEXT     | Task description |
| completed| INTEGER  | 0 = Pending, 1 = Completed |

---

## Installation

1. Clone the repository:

   git clone https://github.com/your-username/todo_app.git

2. Navigate to the project folder:

   cd todo_app

3. Install dependencies:

   pip install -r requirements.txt

---

## requirements.txt

flask

---

## Running the Application

Run the Flask application:

python app.py

Open your browser and visit:

http://127.0.0.1:5000/

---

## How to Use

1. Enter a task in the input field.
2. Click "Add Task".
3. Click "Complete" to mark a task as finished.
4. Click "Delete" to remove a task.

---

## Skills Demonstrated

- Python programming
- Flask web development
- SQLite database integration
- SQL CRUD operations
- Form handling
- Dynamic HTML rendering
- Jinja templating

---

## Concepts Used

- Flask routing
- POST and GET methods
- `request.form`
- `render_template()`
- `redirect()` and `url_for()`
- SQLite `CREATE`, `INSERT`, `SELECT`, `UPDATE`, and `DELETE`
- `sqlite3.Row` for dictionary-like row access

---

## Use Cases

- Personal task management
- Productivity applications
- Beginner CRUD project
- Database practice

---

## Future Enhancements

- User authentication
- Due dates and priorities
- Task categories
- Search and filtering
- Edit existing tasks
- Responsive UI with Bootstrap

---

## Interview Questions You Can Answer

1. What are CRUD operations?
2. Why did you use SQLite?
3. How does Flask connect to a database?
4. What is the purpose of `sqlite3.Row`?
5. How do you handle form submissions in Flask?
6. What is the difference between GET and POST methods?
7. How would you add task editing functionality?
8. How would you implement user-specific tasks?

---

## Resume Description

Developed a To-Do List web application using Flask and SQLite with features to add, complete, and delete tasks. Implemented database-backed CRUD operations, form handling, and dynamic HTML rendering using Jinja templates.

---

## Author

Amrutha D N
