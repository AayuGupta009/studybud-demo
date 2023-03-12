# Python

Python is a high-level scripting programming language. 

## Installation 

Use the package manager [apt](https://ubuntu.com/server/docs/package-management) to install python.

```bash
sudo apt-get install python3
```

To check whether python was installed successfully.

```bash
python3 --version
```
## Pip install

For installing libraries in python we can use [pip](https://packaging.python.org/en/latest/tutorials/installing-packages/)

## Setting Virtual Environment

Now , we will create a [virtual environment](https://docs.python.org/3/library/venv.html) to bundle all our dependencies , libraries and modules in a single place. 

```bash
pip install virtualenv
```

To activate the virtual environment.

```bash
virtual env

source env/bin/activate
```

To decativate the environment.

```bash
deactivate
```

## Installing Django

[Django](https://www.djangoproject.com/) is a free and open-source, Python-based web framework that follows the model–template–views architectural pattern.

We can install django by following command.

```bash
pip install django
```

## Django starter project

To create a starter django project, we use the following commands.

```bash
django-admin startproject projectname

python3 manage.py runserver
```
