# poll-app

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

Heroku
----

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
