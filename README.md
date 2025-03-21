# Table of contents

 1. [create a new repository on the command line](#create-a-new-repository-on-the-command-line)
 2. [Django Startup](#django-startup)
    1. [Create a file named .gitignore](#create-a-file-named-gitignore)
    2. [Setting up a virtual environment](#setting-up-a-virtual-environment)
       1. [To Activate the environment](#to-activate-the-environment)
       2. [To Deactivate the environment](#to-deactivate-the-environment)
    3. [Install packages with pip](#install-packages-with-pip) **do this if find a file named requirement.txt**
    4. [Install Django](#install-django)
    5. [Check the modals saved](#check-the-modals-saved)
    6. [Save the dependencies in the requirements.txt file](#save-the-dependencies-in-the-requirementstxt-file)
    7. [Start a project](#start-a-project)
    8. [Start an app](#start-an-app)
    9. [Create migration](#create-migration)
    10. [Create Admin user](#create-admin-user)
    11. [Start the page](#start-a-project)

## create a new repository on the command line

```shell
git init
```

```shell
git add README.md
```

```shell
git commit -m "first commit"
```

```shell
git branch -M main
```

```shell
git remote add origin <https://github.com/JeromeMberia/startup.git>
```

```shell
git push -u origin main
```

## 2. push an existing repository from the command line

```shell
git remote add origin <https://github.com/JeromeMberia/startup.git>
```

```shell
git branch -M main
```

```shell
git push -u origin main
```

## Django Startup

### Create a file named .gitignore

```shell
New-Item -Path ".gitignore"
```

You will find it [here](https://github.com/JeromeMberia/gitignore/blob/main/Python.gitignore) the link to the  repository for gitignore.

### How to install Django on Windows

The link to the Django website on how to install Django [here](https://docs.djangoproject.com/en/4.1/howto/windows/).

### Setting up a virtual environment

```shell
py -m venv venv
```

### To Activate the environment

```shell
.\venv\Scripts\activate
```

### To Deactivate the environment

```shell
deactivate
```

### Install packages with pip

```shell
pip install -r requirements.txt
```

### Install Django

```shell
py -m pip install Django
```

### Check the modals saved

```shell
py -m pip freeze
```

### Save the dependencies in the requirements.txt file

```shell
python -m pip freeze > requirements.txt
```

### Start a project

```shell
django-admin startproject project .
```

### Start an app

```shell
py manage.py startapp <name of the app>
```

### Create migration

```shell
py manage.py migrate
```

### Create Admin user

```shell
py manage.py createsuperuser
```

### Start the page

```shell
py manage.py runserver
```

This command open the link the starts the server

```shell
Start-Process "http://127.0.0.1:8000/" | py manage.py runserver
```

or

```shell
Start-Process "http://localhost:8000/" | py manage.py runserver
```

## Powershell commands

### Create a folder in the current folder

```shell
New-Item ".\SharedFolder" -itemType Directory
```

### Create multiple files in the current folder

```shell
New-Item -Path ".\PSDocument.doc", ".\PSTextfile.txt"
```

### listing all the files by name on the current directory

```shell
Get-ChildItem -Recurse . | Select Name
```
