# Change didn't show in git

## Flask API Folder structure

write below code to let flask know where flask app is

``` bash
export FLASK_ENV=development
export FLASK_APP=src
```

## Databse and models set up

init database in shell

``` bash
flask shell
>>> from src.database import db
>>> db.create_all()
>>> db
# to recreate
>>> db.drop_all()
>>> db.create_all()
```