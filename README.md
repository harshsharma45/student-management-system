# 🎓 Student Management System

A web-based **Student Management System** developed using Python and Django as part of an educational and industrial training project.

The system provides a centralized platform for managing students, staff, courses, subjects, attendance, academic results, leave applications, and feedback. It includes separate dashboards and functionalities for administrators, teachers, and students.

## 📌 Project Overview

The Student Management System is designed to simplify academic administration by organizing student records and educational activities in one place.

**Project Details**

* **Project Name:** Student Management System
* **Technology:** Python, Django
* **Database:** SQLite (default, if configured in the project)
* **Frontend:** HTML, CSS, JavaScript, Bootstrap (as used in the project)
* **Project Type:** Web Application
* **Purpose:** Educational and Industrial Training Project
* **Developer:** Harsh Sharma

## ✨ Features

### 👨‍💼 Administrator (HOD)

* View dashboard summaries and academic statistics.
* Add, update, view, and delete staff records.
* Manage student records.
* Manage courses and subjects.
* Manage academic sessions.
* View student attendance records.
* Review and respond to feedback.
* Approve or reject leave applications.

### 👨‍🏫 Staff / Teachers

* View a dashboard containing relevant academic information.
* Record and update student attendance.
* Add and update student results.
* Apply for leave.
* Submit feedback to the administration.

### 👨‍🎓 Students

* View a personalized dashboard.
* Check attendance records.
* View academic results.
* Submit leave applications.
* Send feedback to the administration.

## 🛠️ Technologies Used

* **Python** — Backend programming language
* **Django** — Web application framework
* **HTML5** — Page structure
* **CSS3** — Styling
* **JavaScript** — Frontend interactions
* **Bootstrap** — Responsive user interface, if included in the project
* **SQLite** — Database, if configured as the default database

## 💻 System Requirements

Before running the project, ensure that you have installed:

1. Python 3
2. Git
3. Visual Studio Code or another code editor
4. pip (Python package manager)
5. A modern web browser

## 🚀 Installation and Setup

Follow these steps to download and run the project on your local computer.

### 1. Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/harshsharma45/student-management-system.git
```

Navigate to the project directory:

```bash
cd student-management-system
```

### 2. Create a Virtual Environment

On Windows:

```bash
python -m venv venv
```

Activate the virtual environment in Command Prompt:

```cmd
venv\Scripts\activate
```

Or, in PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

If the project contains a `requirements.txt` file, run:

```bash
python -m pip install -r requirements.txt
```

### 4. Configure the Project

Open the project in your code editor.

Check the Django settings file and verify that the database configuration and allowed hosts are appropriate for local development.

For local testing, `localhost` and `127.0.0.1` can be used as allowed hosts where required.

**Security note:** Do not use `ALLOWED_HOSTS = ['*']` as a production configuration. Never upload passwords, secret keys, or other sensitive credentials to GitHub.

### 5. Apply Database Migrations

Run:

```bash
python manage.py migrate
```

### 6. Create an Administrator Account

To create your own administrator account, run:

```bash
python manage.py createsuperuser
```

Follow the prompts to enter the required account details.

### 7. Start the Development Server

Run:

```bash
python manage.py runserver
```

Open the following address in your browser:

http://127.0.0.1:8000/

**Note:** The exact login page and administrator URL depend on the project's URL configuration. Check the project's URL files if you need to locate them.

## 📂 Project Structure

A typical Django project may contain the following files and directories:

```text
student-management-system/
│
├── manage.py
├── requirements.txt
├── README.md
├── db.sqlite3
├── static/
├── media/
└── project_apps/
```

The actual folder structure may differ depending on the application's configuration.

## 🎯 Project Objectives

* Simplify student record management.
* Organize attendance and academic results.
* Provide separate access for administrators, teachers, and students.
* Reduce manual work in routine academic administration.
* Improve the accessibility of academic information.
* Demonstrate practical application development using Python and Django.

## 🔮 Future Enhancements

Potential improvements include:

* Improved dashboard design and data visualization.
* Student performance analytics.
* Automated notifications and reminders.
* Report generation and PDF downloads.
* Enhanced form validation and security.
* Mobile-friendly interface improvements.

These are possible future enhancements and may not be implemented in the current version.

## 👨‍💻 Developer

**Harsh Sharma**

* **GitHub:** [@harshsharma45](https://github.com/harshsharma45)
* **LinkedIn:** [harshsharma45](https://www.linkedin.com/in/harshsharma45/)
* **Email:** [harshsharma2444@gmail.com](mailto:harshsharma2444@gmail.com)

## 🎓 Acknowledgment

This project is intended for educational purposes and practical learning in web application development using Python and Django.

The original codebase was obtained from an existing open-source project. Please refer to the original repository and its license for attribution and usage requirements.

## 📄 License

Refer to the applicable license in the original source repository. Ensure that the original license and attribution requirements are followed before redistributing or modifying the project.
