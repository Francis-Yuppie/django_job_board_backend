# DJANGO JOB BOARD BACKEND
## INFO

This is the backend for the yjob web app with uses Nuxt 3 as its front end template you can find the 
themplate here [Yjob Frontend](https://github.com/Francis-Yuppie/job-board-nuxt3-frontend.git)

# Installation

## steps

1. Clone The repoo:

        git clone https://github.com/Francis-Yuppie/django_job_board_backend.git

2. Create a Virtul Environment

        python3 -m venv env

3. Activate virtual environment: for linux 

        source env/bin/activate

4. Install dependancis run:

        pip install -r requirements.txt

5. Run migrations and create superuser

        python manage.py makemigrations

        python manage.py migrate

        python manage.py createsuperuser

6. Run the server

        python manage.py runserver



## folder structure

--