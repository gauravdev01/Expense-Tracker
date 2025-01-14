# Django-based Expense Tracker

A simple, efficient, and intuitive expense tracker application built with Django to help users manage and track their expenses. It includes features like user authentication, expense categorization, profile management, and detailed reporting with data visualization.

## Key Features
- **User Authentication**: Sign up, login, and manage user profiles.
- **Expense Tracking**: Add, edit, and delete expenses categorized by type (e.g., Food, Transport, etc.).
- **Category Management**: Manage and assign categories to expenses.
- **Reporting**: Generate expense reports based on selected timeframes (daily, monthly, yearly).
- **Data Visualization**: Visualize expenses using charts and graphs.

## Technologies Used
- **Django** (Backend Framework)
- **Python** (Programming Language)
- **SQLite** (Database)
- **HTML/CSS** (Frontend)
- **JavaScript** (Dynamic Elements)
- **Matplotlib** (Data Visualization)
- **Django Rest Framework** (For potential API development)
- **JWT** (Authentication)

## Installation

Follow these steps to set up the project locally:

### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone (https://github.com/gauravdev01/Expense-Tracker)
cd expense-tracker
```
### 2. Create a Virtual Environment (Optional but recommended)
It's recommended to use a virtual environment for managing dependencies. You can create one by running:
```bash
python -m venv venv
```
Activate the virtual environment:
On Windows:
```bash
venv\Scripts\activate
```
On Mac/Linux:
```bash
source venv/bin/activate
```
### 3. Install Dependencies
Install the required Python packages:
```bash
pip install -r requirements.txt
```
### 4. Set Up the Database
Run the migrations to set up the database:
Python Expense Tracker Output:
```bash
python manage.py migrate
```
### 5. Create a Superuser (for Admin Access)
If you want to access the Django admin panel, create a superuser:
```bash
python manage.py createsuperuser
```
Follow the prompts to set the username, email, and password.

### 6. Run the Development Server
Start the development server to run the application:
```bash
python manage.py runserver
```
The application should now be accessible at http://127.0.0.1:8000/

**Usage**

**Accessing the Application:** Visit http://127.0.0.1:8000/ in your web browser to start using the expense tracker.

**Admin Panel:** Access the Django admin panel at http://127.0.0.1:8000/admin/ using the superuser credentials created earlier.

Login Form:
![image](https://github.com/gauravdev01/Expense-Tracker/assets/109756079/fd0af81e-2642-41d6-95bc-2e3e0d16785e)

Dashboard:
![image](https://github.com/gauravdev01/Expense-Tracker/assets/109756079/a065a8d2-ac76-4794-bf7e-91e39b871cf9)

![image](https://github.com/gauravdev01/Expense-Tracker/assets/109756079/7d88987f-f3f8-4860-a282-4d6acf2767d2)

Monthly Expense Page:

![image](https://github.com/gauravdev01/Expense-Tracker/assets/109756079/144d7909-36ef-4416-8444-d21ffaad1a0b)

History Page:

![image](https://github.com/gauravdev01/Expense-Tracker/assets/109756079/3b573e71-1ca1-4ec7-9131-7914ea52c324)

Summary

We have successfully created the expense tracker project in python. We learned a variety of concepts while making this project.
