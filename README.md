# poll-app

Create db (first time)
```
createdb polldb
```
Set DATABASE_URL
```
export DATABASE_URL=postgresql://vivianliang@localhost:5432/pollsdb
```
Run locally
```
python manage.py runserver
```
Shell
```
python manage.py shell
```
Create admin
```
python manage.py createsuperuser
```

##Heroku

Deploy to heroku
```
git push heroku master
```
* https://poll-app-vivian.herokuapp.com/polls/

Sync database
```
heroku run python manage.py syncdb
```
Django shell
```
heroku run python manage.py shell
```

### Heroku Set up
https://devcenter.heroku.com/articles/getting-started-with-django
https://devcenter.heroku.com/articles/heroku-postgresql
