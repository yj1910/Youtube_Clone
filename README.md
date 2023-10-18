# Youtube_Clone
YouTube clone project is video sharing platform where user can create own channel upload videos, watch others videos like it comment it and subscribe other channels. youtube clone project based on python-django framework with HTML, CSS, Javascript where sqlite is used as a database to store users activities, uploads and credentials.


## Project Overview

https://github.com/yj1910/Youtube_Clone/assets/83238190/0b291e94-e301-4568-b65e-524bf7783a47


# Local setup
Import the project file in your local. Open in IDE and open terminal

**To install dependencies, run:**
```
python -m pip install --upgrade pip (Upgrading pip)
pip3 install -r requirements.txt
```

**To initialize the Database (sqlite3 file)**
```
del db.sqlite3
python manage.py makemigrations
python manage.py migrate
```

**In order to run this project, execute:**
```
python manage.py runserver
```
open http://127.0.0.1:8000/ on your browser
