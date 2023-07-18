
---
# Python Flask Template 2023

The purpose of this project is to use to play around. It uses pipenv, flask and has its own requirements.txt

## Clone this repo

- with an empty folder
- open terminal
- please install git before you continue
- write: ```git clone https://github.com/baylagas/python-flask-template-2023.git``` then press enter

## Install pipenv

```bash
pip install pipenv --user
```

## Create a new virtual environment

```bash
pipenv shell
```

## Install requirements

```bash
pipenv install -r requirements.txt
```

## Run the project

```bash
python app.py
```

## Usage: play around with your code

```py
from flask import Flask

app = Flask(__name__)


@app.route("/")
def hello():
    return "hello world"


if __name__ == "__main__":
    app.run(debug=True)
```