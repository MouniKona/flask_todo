Simple Flask Todo App using SQLAlchemy and SQLite database.

For styling [semantic-ui](https://semantic-ui.com/) is used.

### Setup
Create project with virtual environment

```console
$ mkdir myproject
$ cd myproject
$ python -m venv venv
```

Activate it on Linx
```console
$ . venv/bin/activate
```

or on Windows
```console
$ venv\Scripts\activate
```

Install Flask
```console
$ pip install Flask
$ pip install Flask-SQLAlchemy
```

Set environment variables in Linx
```console
$ export FLASK_APP=app.py
$ export FLASK_ENV=development
```

or on Windows
```console
$ set FLASK_APP=app.py
$ set FLASK_ENV=development
```

import and create db all function
```console
$ Flask shell
$ from app import db
$ db.create_all()
$ exit()
```

Run the app
```console
$ flask run
```
