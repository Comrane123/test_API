# games_test
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for testing purposes.

### Mission 1
* Can be found in `test_project/games/services.py`
* To run `python services.py`


### Installing


* Create a virtualenv for the project
* Install the requirements.txt file with pip


```
pip install -r requirements.txt
```
* Run migrations
```
python manage.py migrate
```

* Run the django server

```
python ./manage.py runserver
```

### Api endpoint
* Endpoint to access all games:
```
127.0.0.1:8000/TEST
```
*use `?search=[search request]`