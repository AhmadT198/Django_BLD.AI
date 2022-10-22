
# Session 1 (Intro to Django #1)



## Content

 - Poetry (Python Package Managing tool)
 - How to create a Django Project
 - Manage.py
 - Settings.py
 - Blocking Vs Non-Blocking Applications

 




## - Poetry

 It allows you to declare the libraries your project 
 depends on and it will manage (install/update) them for you.
 It creates a file called `pyproject.toml` that contain all your project's
 dependencies.

 For installation: [Documentation](https://python-poetry.org/docs/)




## - How to create a Django Project

 - Make sure to have Django installed in your Python project.
 
 ```bash
  poetry add django
```
- Run
 ```bash
  django-admin startproject *name*
```

A project will be created with several files.


## - Manage.py
It's considered the entry point of Django, from which you can start
your server.
