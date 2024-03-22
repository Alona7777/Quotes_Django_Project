# About project

This project is a web application for storing quotes and information about authors using Django and PostgreSQL database. Additionally, the project integrates OpenAI to generate new quotes every 12 hours and saves them to the database. Users can also register in the system, and registered users can add new quotes and new authors.

# Technologies
- Django 
- Postgres
- OpenAI



# Get started

1) Clone repository

    ```git clone https://github.com/Alona7777/Quotes_Django_Project.git```

2) Change directory to project folder

    ```cd quotes_project```

3) Activate Poetry environment

    ```poetry shell```

4) Install packages

    ```poetry install```

5) Run migration
    ```python manage.py makemigrations```
    ```python manage.py migrate```

6) Run server

    ```python manage.py runserver --noreaload```