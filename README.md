# mhkselfstudy
[Link](https://mypadhai.herokuapp.com/)

## Study Portal
This Study Portal allows User to Login on the potal and **Create or Delete Notes, Homework and To-Do Lists**.
Users can also **Search Books, Meanings of words and Wikipedia Information** on any topic

![dashboard](https://user-images.githubusercontent.com/85742867/147137483-14dc47a5-3198-4e12-b424-6c5e6feb4ad2.png)


**TechStack Used**
1. Python (Programming Language)
2. Django (Web Framework)
3. SQLite (Database)

**How to setup and run locally**

1. Clone the Repository
2. Create and Activate Python Virtual Environment
3. After activating the virtual enviornment, redirect to project base directory.
4. Run the following command for installing dependencies. 
  ```
  $ pip install -r requirements.txt
  ```
5. Now before running the server, we have to setup database, so run. 
  ```
  $ python manage.py migrate
  ```
6. Now create superuser for accessing the dashboard to view the stored content.
  ```
  $ python manage.py createsuperuser
  ```
7. After completeing of all the entries while creating superuser, we are ready to test the whole project.
8. Now run the following command for starting the server
  ```
  $ python manage.py runserver
  ```
9. To access the dashboard checkout http://127.0.0.1:8000
10. To access the admin panel checkout http://127.0.0.1:8000/admin
