# django-e-learning
E-Leraning application following the book _Django 3 by Example_

![Django CI](https://github.com/vitorpvcampos/django-e-learning/workflows/Django%20CI/badge.svg)
[![Updates](https://pyup.io/repos/github/vitorpvcampos/django-e-learning/shield.svg)](https://pyup.io/repos/github/vitorpvcampos/django-e-learning/)
[![Python 3.9.0](https://img.shields.io/badge/python-3.9.0-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Django 3.1.4](https://img.shields.io/badge/django-3.1.4-blue.svg)](https://www.djangoproject.com/download/)
[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/vitorpvcampos/django-e-learning/blob/main/LICENSE)

### How to run the project?

* Clone the repository
* Create a virtual environment
* Install the dependencies
* Run docker-compose.yml
* Run the migrations

```
git clone https://github.com/vitorpvcampos/django-e-learning.git
cd django-e-learning
pip install pipenv
pipenv install --dev
docker-compose up -d
python manage.py migrate
```

#### PEP8 lint
```
pipenv run flake8
```
