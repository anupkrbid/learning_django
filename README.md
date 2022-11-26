## Notes

1. Install latest version of Python
2. python -m pip install Django
3. django-admin startproject <ProjectName>
4. Download VS Code
5. Choose the correct version of python at the bottom status bar in case more than one is installed
6. Install vs code extension Python and Pylance
7. Manual Format document will install another package (autopep8)
8. ./manage.py - wont change much here we will use this fillfrom time to time to run project specific commands, like starting a dev server and setting up a database.
9. ./learning_django/\_\_init\_\_.py - nothing to change here, this only exists to mark the folder and and all the files in it as a python module or a python package.
10. ./learning_django/asgi.py & ./learning_django/esgi.py - used to deploy project to real server to expose to real world.
11. ./learning_django/settings.py - contains global settings for this Django project. we can visit this file to tewwk certain settings. Configure behaviour of our Django project.
12. ./learning_django/urls.py - important file as we add more and more pages to the app.
13. we can add custom files but this is the rough overview of the default generated project structure.
14. Start Dev Server - python manage.py runserver
15. Runs at localhost:8000
16. A dummy db.sqlite3 is created automatically
17. Django Projects embrace a Modular structure, so it often consists of multiple modules that make up the project. In Django worls these Modules are called Apps. And you store your app code in those modules
18. Create App in Django Project - python manage.py startapp <AppName>
19. Overview of new folder created
20. ./learning_routing/admin.py - will bcome important when we start working on the built in administration area.
21. ./learning_routing/apps.py - has a name to identify the app and it is usefull when we want to connect multiple apps.
22. ./learning_routing/models.py - will become important when we start working with the database and we add data models to the project.
23. ./learning_routing/tests.py - will help with automated and unit tests
24. ./learning_routing/views.py - used to determine what to show user when they visit the app
25. URLs(Routes) & Views
26.
