Create project and application

Create virtual environment using-"python3.7 -m venv virtual_env"

Install django: - pip install django==3.2.7

1.Create project(company) : django-admin startproject company

    Create app(staff): - cd company (inside the company dir give command) - python manage.py startapp staff (This will create staff app)

    Install Requirements - pip install -r requirements.txt

2.Create models and migrations

python manage.py makemigrations (This will create migration files)
python manage.py migrate (Apply migrations in db)

3.Inlines and filters added

4.Test admin interface:-
Create Superuser to access admin - python manage.py createsuperuser (Enter username, email and password) 
To start server "python manage.py runserver" (This will run the server in http://127.0.0.1:8000) 
Browse the url http://127.0.0.1:8000/admin 
Enter admin credentials - To view Department and Employees

5.Department list available in http://127.0.0.1:8000/departments/

6.Click on department to view its detail (http://127.0.0.1:8000/department/<department_id>/)
Form created for Employee with name and department

7.Create employee object http://127.0.0.1:8000/add-employee/

8.5 and 7 views templates are department_list.html and create_employee.html respectively, these templetes are placed under app staff/templates/staff/.
