# Task: Django


> ## Django: Getting Started
 
   
- Create a new Python virtual environment.
- Initialize it, and install Django in it.
- Create a new Django project. Use your ZuriBoard username as the name of the project.
- Push your project to a new Public GitHub repository and submit the URL

  #      

>## Solution:


- Created virtual environment

- Activated virtual enviroment

        py -m venv venv
        source venv/bin/activate

- Installed django

        py -m pip install django

- Extracted installed dependencies to a file named requirements.txt

        pip freeze > requirements.txt

- Created a new Django project with my zuriboard username
    
        django-admin startproject EmmanuelEnebeli

- Created a new Django app called I4G

        py manage.py startapp I4G

- Added secret key to an enironment variable
- Ran the django server

        python manage.py runserver
- Created a new public GitHub repository.

- Initialized a git repository in the current directory.

- Linked local repository to the remote repository.

        git remote add origin https://github.com/EnebeliEmmanuel/Django-Task.git

- Git add and commit all files.

        git add .
        git commit -m "I4G"

- Pushed the local repository to the remote repository.

        git push origin main



