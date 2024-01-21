# WizComm_Blog_Asst_Django
A Django Blog App with CRUD Functionality hosted on render with Postgres SQL Database wherein a user can create blogs with authentication mechanisms. 

# Render
The App is deployed on Render which is a free app to provide basic infrastructure such as Postgres(configured in settings.py file), deployment server to interact with wsgi.py file. The build command ensures that requirements are downloaded as the part of initialisation. An important thing to note is project name which is django_project in this case.

# Backend Overview
There is a user model associated with a post model with cascade delete option wherein posts associated with a user are deleted if user is deleted. That feature is under progress and currently it can be deleted from admin site if required.

# Frontend Overview
Frontend is created from bootstrap classes and is defined in templates and static folders at respective places. Additionally whitenoise is used for static file storage and can interact with any server within wsgi to provide static files.

# Features
1. Pagination
2. Profile Pic for User
3. User Registration and Login

# Testing SOP on Local Server

1. `git clone https://github.com/HarshitPro1608/WizComm_Blog_Asst_Django.git`
2. `git pull origin master`
3. `cd django_project`
4. `python manage.py runserver`

# Deployment SOP on Render

1. `git clone https://github.com/HarshitPro1608/WizComm_Blog_Asst_Django.git`
2. `git pull origin master`
3. `cd django_project`
4. `git commit -m "Your Message"`
5. `git push origin master`
6. Link to see deployment changes: https://dashboard.render.com/web/srv-cmmhq5821fec73cm0ju0/events

# Finally the Link to access project :) : https://wizcomm-blog-app.onrender.com/
