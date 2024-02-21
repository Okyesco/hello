# Hostel management system using django web framework


Current features
----------------
* 


# Pre-requisites:

> The following programs are required to run the project

- [Any Python-3 version](https://www.python.org/downloads/)
- [PostgreSQL database](https://www.postgresql.org/download/)

# Installation

- Clone the repo with (https) `git clone https://gitlab.com/jordanahu/hostel-management.git`
- Clone the repo with (ssh) `git clone git@gitlab.com:jordanahu/hostel-management.git`

- Create and activate a python virtual environment
- `mkvirtualenv [name of virtual environment]`
- `workon [name of virtual environment]`

- Install Project Requirements
- `pip install -r requirements.txt`

- Create `.env` file inside the root directory and include the following variables
```config
DB_NAME=[YOUR_DB_NAME]
DB_USER=[DB_ADMIN_NAME]
DB_PASSWORD=[DB_PASSWORD]
DB_HOST=localhost
DB_PORT=5432
```

- `python manage.py makemigrations`

- `python manage.py migrate`

- `python manage.py runserver`

Last but not least, go to this address http://127.0.0.1:8000

# Connect with me

<div>
<a href="https://www.linkedin.com/in/nyarko-george-76478b1aa" target="_blank">
<img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" />
</a>
<a href="https://github.com/Okyesco" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
</div>

### Let's enhance the project by contributing! 👩‍💻👩‍💻