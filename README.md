# django-polls-tutorial
Django polls tutorial

# To Install
```bash
$ cd mydevdir
$ git clone https://github.com/jcfausto/django-polls-tutorial.git
$ cd django-polls-tutorial
$ pip install -r requirements.txt
$ python manage.py migrate
```

# Run the tests first
```bash
$ coverage run --source='.' manage.py test myapp
```

# To Run
```bash
$ python manage.py runserver
```

## Using vagrant?
```bash
$ python manage.py runserver 0.0.0.0:8000
```
