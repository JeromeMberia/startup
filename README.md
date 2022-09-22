# Table of contents

 1.[create a new repository on the command line](#create-a-new-repository-on-the-command-line)
 2.[Django Startup](#django-startup)

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
> you will find it [here](https://github.com/JeromeMberia/gitignore/blob/main/Python.gitignore).

### Setting up a virtual environment¶

```shell
py -m venv venv
```

### To Activate the environment

```shell
.\venv\Scripts\activate
```

### To Deactivate the environment

```shell
.\venv\Scripts\deactivate
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
django-admin startproject <name of the project>
```

### Start an app

```shell
py manage.py startapp <name of the app>
```

### Start the page

```shell
py manage.py runserver
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
