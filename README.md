# urls

Create a new virtual environment in that folder named env and install Django in it.

Create a new Django project. Use your Zuriboard username as the name of the project.

 

Run all migrations for your project.

 

Create a new admin account for the project using the createsuperuser command. 

 

Start the development server using python manage.py runserver
Open the URL  http://127.0.0.1:8000/admin and login with your new admin details. Now logout.

 

Open project_app/urls.py and change the URL Path for the Django Admin dashboard to zuri-admin/

You should be able to open http://127.0.0.1:8000/zuri-admin/ and login to the admin dashboard.
