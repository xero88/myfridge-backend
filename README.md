# MyFridge Backend

The backend of MyFridge project

## Requirement

### Postgres

A postgres database running

Python 3.7

Pipenv

# Setup


## Run shell

```
pipenv shell
```


## Install dependencies

```
pipenv install
```

## Install dependencies (dev)

```
pipenv install --dev
```

## Migrate (create tables on database)

```
python manage.py migrate
```

## Create super user

```
python manage.py createsuperuser
```

## Run server

```
python manage.py runserver
```

# Test

## Launch test

```
pytest -s --spec
```

## Launch coverage

```
pytest --cov=bookingCorner --cov-report=html
```

## TDD

```
ptw -- -s --spec --testmon
```

# Utils

## Reset db (remove tables)

```
python manage.py reset_db
```

## Reset db (remove data)

```
python manage.py flush
```

## Better console

```
python manage.py shell_plus
```