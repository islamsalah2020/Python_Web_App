# Python_Web_App
Python_Web_App  (Build a Portfolio App)

Set up a new Django project and app

Build a Personal Portfolio Website with Django


### Steps for Hello world App:

1. clone project and run `git checkout origin/Hello_World`
2. run `python -m venv venv`
3. run `source venv/Scripts/activate` or `source venv/bin/activate` for linux
4. run `pip install Django`
5. run `python manage.py runserver`
6. if you want to change IP and port  `python manage.py runserver new_ip:port` and you need to add IP to settings.py ALLOWED_HOSTS=['']
7. access your website: [localhost:8000](http://localhost:8000/)


### Steps for Projects App:
1. clone project and run `git checkout origin/projects` after change dir inside the cloned repo
2. run `python -m venv venv`
3. run `source venv/Scripts/activate` or `source venv/bin/activate` for linux
4. run `pip install Django`
5. run
    a. python manage.py makemigrations projects
    b. python manage.py migrate projects
    c. python manage.py shell (will output python interperter)
    d. from projects.models import Project
    e. p1 = Project(title='My First Project',description='A web development project.',technology='Django',image='img/project1.png')
       p1.save()
    f. and the same for p2 and p3 then exit()       

5. run `python manage.py runserver`
6. if you want to change IP and port  `python manage.py runserver new_ip:port` and you need to add IP to settings.py ALLOWED_HOSTS=['']
7. access your website: [localhost:8000](http://localhost:8000/)
