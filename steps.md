step 1: create a repository in git 'translater'
step 2: clone the repository in your local machine
    - "git clone <url>"
step 3: create a virtual environment
    - "py -m venv env"
step 4: activate the virtual environment
    - ".\env\Scripts\activate"
step 5: install django
    - "p    ip install django"  
step 6: create a django project
    - "django-admin startproject translater ."
step 7: create a django app
    - "python manage.py startapp translater"
step 8: create a model
    - "python manage.py makemigrations"
step 9: create a view
    - "python manage.py migrate"
step 10: create a template
    - "python manage.py runserver"
step 11: create a url
    - "python manage.py runserver"
step 12: run the server
    - "python manage.py runserver"
step 13: push the code to git
    - "git add ."
    - "git commit -m 'initial commit'"
    - "git push -u origin main"            