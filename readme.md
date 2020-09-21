# django basic starter for deploy
> ver

django < 3.1

> .gitignore

pycache, db.sqlite, media, migrations, config_secret/* 

> .config_secret
django secret_key, database configs

> file structure
```
djangoproject
 ┣ .config_secret
 ┃ ┣ settings_base.json
 ┃ ┣ settings_deploy.json
 ┃ ┗ settings_dev.json
 ┣ config
 ┃ ┣ settings
 ┃ ┃ ┣ base.py
 ┃ ┃ ┣ deploy.py
 ┃ ┃ ┣ dev.py
 ┃ ┃ ┗ __init__.py
 ┃ ┣ asgi.py
 ┃ ┣ urls.py
 ┃ ┣ wsgi.py
 ┃ ┗ __init__.py
 ┣ main
 ┃ ┣ migrations
 ┃ ┃ ┗ __init__.py
 ┃ ┣ admin.py
 ┃ ┣ apps.py
 ┃ ┣ models.py
 ┃ ┣ tests.py
 ┃ ┣ views.py
 ┃ ┗ __init__.py
 ┣ db.sqlite3
 ┗ manage.py
 ```
