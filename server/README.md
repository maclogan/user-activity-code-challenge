This Django app is meant to fulfill the Backend requirement of Attainia's User Activity Monitor coding assessment (https://github.com/Attainia/user-activity-code-challenge)

To run the server code independently of the VUE client, run the following command withing the Attainia/server folder:
python manage.py runserver

In the case you would like to manipulate the datastored without making api calls, the admin info is as follows:
admin site: localhost:8000/admin
username: Admin
password: Test1234! 

After reviewing the instructions, it was unclear whether the server should host the users.json file directly or if it should store its contents and serve them when requested. Since this is a Django backend project, I figured it would make the most sense to build a true API with SQLlite backend and host as requested.  I imported the json using POSTMAN to submit a post request to 'localhost:8000/users' with the contents of the JSON file.

