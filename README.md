# django-materialize-boilerplate
A barebone Django app using [Materialize CSS framework](http://materializecss.com/).  
If you're unfamiliar with Heroku, please refer to [Getting Started with Python on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python#introduction) article.

## Running Locally
Make sure you have [pip3](https://stackoverflow.com/questions/6587507/how-to-install-pip-with-python-3), [Django](https://www.djangoproject.com/), and [Heroku-CLI](https://devcenter.heroku.com/articles/heroku-cli) installed.

```
$ git clone https://github.com/anthonyc1/django-materialize-boilerplate.git
$ cd django_materialize_boilerplate
$ python3 manage.py runserver
```

Your app should be running on [localhost:8000](http://localhost:8000)

## Deploying to Heroku
```
$ heroku create
$ git push heroku master
$ heroku open
```