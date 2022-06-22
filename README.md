# Task Title: Django{URLs}
1. Create a new GitHub repository with a README.md, and Python .gitignore file.

2. Clone it to your machine/computer, which will create a new folder on your computer with your repository’s content.

3. Create a new virtual environment in that folder named env and install Django in it.

4. Create a new Django project. Use your Zuriboard username as the name of the project.

5. Run all migrations for your project.

6. Create a new admin account for the project using the createsuperuser command. 

7. Start the development server using python manage.py runserver
Open the URL  `http://127.0.0.1:8000/admin` and login with your new admin details. Now logout.

8. Open `project_app/urls.py` and change the URL Path for the Django Admin dashboard to `zuri-admin/`

9. You should be able to open `http://127.0.0.1:8000/zuri-admin/` and login to the admin dashboard.

10. Stage and Commit your Django project and push your changes to your GitHub repository. 

11. Do not add your database `(db.sqlite)` to version control `(GitHub)`. 

12. Ensure your final code/submission is on the default branch of your GitHub repository.