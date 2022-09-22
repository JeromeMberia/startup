## create a new repository on the command line

### Step 1

```shell
git init
```

### Step 2

```shell
git add README.md
```

### Step 3

```shell
git commit -m "first commit"
```

### Step 4

```shell
git branch -M main
```

### Step 5

```shell
git remote add origin <https://github.com/JeromeMberia/startup.git>
```

### Step 6

```shell
git push -u origin main
```

## 2. push an existing repository from the command line

### 2. Step 1

```shell
git remote add origin <https://github.com/JeromeMberia/startup.git>
```

### 2. Step 2

```shell
git branch -M main
```

### 2. Step 3

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

### Install Django

```shell
py -m pip install Django
```
