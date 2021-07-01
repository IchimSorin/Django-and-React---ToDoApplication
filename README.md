![Django and React - To Do Application](https://user-images.githubusercontent.com/34681854/123550272-793b3180-d775-11eb-8eb7-3b77af0f2f21.gif)
# Django-and-React---ToDoApplication.
To Do Application built off Django (including the Django REST Framework for API CRUD operations) and React
TUTORIAL LINK: https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react
<br><hr>
How to run the application: <br>
1. Clone the project to your machine <br>
2. Navigate into the diretory [cd "Django and React - To Do Application"] <br>
3. Source the virtual environment [pipenv shell] <br>
4. Install the dependencies <br>
	pipenv install djangorestframework django-cors-headers <br>
5. Navigate into the frontend directory [cd Frontend] <br>
6. Install the dependencies: <br>
	npm install bootstrap@4.6.0 reactstrap@8.9.0 --legacy-peer-deps
<br><hr>
You will need two terminals pointed to the frontend and backend directories to start the servers for this application.
<br><hr>
Run this command to start the backend server in the [Backend] directory: [python manage.py runserver]
Run this command to start the frontend development server in the [Frontend] directory: [npm start]
Go to: http://localhost:3000/
