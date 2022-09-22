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

### Setting up a virtual environment¶

```shell
py -m venv project-name
```

### To Activate the environment

```shell
project-name\Scripts\activate
```

### To Deactivate the environment

```shell
project-name\Scripts\deactivate
```

### Create a file named .gitignore

```shell
New-Item -Path ".gitignore"
```

### Install Django

```shell
py -m pip install Django
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
