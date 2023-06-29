# Flask Tutorial

source: https://flask.palletsprojects.com/en/2.3.x/tutorial/

## Local Server

run `flask --app flaskr run --debug`

## Tests

```shell
pytest
```

```shell
coverage run -m pytest
coverage report
```

## Dependencies

Install

```shell
pip install -r requirements.txt
```

Update

```shell
pip freeze > requirements.txt
```

## Virtual Env

Setup

```shell
python3 -m venv venv
```

Activate

```shell
source venv/bin/activate
```

Deactivate

```shell
deactivate
```
