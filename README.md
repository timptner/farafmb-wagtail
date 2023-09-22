# FaRaFMB

This repository contains the source code for the homepage of the student 
council for mechanical engineering at the Otto von Guericke University 
Magdeburg.

## Installation

The following steps describe how to set up a local development environment.

1. Create virtual environment for python.
2. Activate environment.
3. Install dependencies.
4. Apply migrations to database.
5. Create initial admin user.
6. Start local webserver.

```commandline
python3 -m venv ./venv
source venv/bin/activate
python3 -m pip install -r requirements.txt
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver
```

## Author

Aiven Timptner
