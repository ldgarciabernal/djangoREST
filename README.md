# DJAGO REST FRAMEWORK TUTORIAL

Repository to save all the chapter of Django REST framework tutorial. You can see the tutorial click [here](https://www.django-rest-framework.org/tutorial/quickstart/)

## Installation

Before dwonload the repository, You need to use the command pip to create a virtual environment:
```bash
pip3 install virtualenv
```

Create virtualenv:
```bash
virtualenv -p python3 venv
```

Activar virtualenv:
```bash
source venv/bin/activate
```

Desactivar virtualenv:
```bash
deactivate
```

*Remenber that you need to create the venv with Python3.

When finished the installations of venv and we have run the virtualenv, we need to run some commands.

```bash
pip install -r requitements.txt # This is to install the necesaty dependencies for the project
python manage.py makemigrations # Generate the migrations files
python manage.py migrate        # Run the migrations
```

Finally you can run a server using:
```bash
python manage.py runserver 
```

