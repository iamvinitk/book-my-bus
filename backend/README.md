# Getting Started

* Clone the repository
* Install the dependencies

```shell
pip install -r requirements.txt
```

* Make migrations

```shell
python manage.py makemigrations
python manage.py migrate
```

* Populate the database

```shell
python populate_db.py
```

* The script will create a superuser with the following credentials:

```
username: admin
password: admin
```

* Run the server

```shell
python manage.py runserver
```

* Access the admin panel at http://127.0.0.1:8000/admin and login with the superuser credentials