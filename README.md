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

#Usage

Access the aplication at http://localhost:8000/polls/

* the port may vary due to your setup. I used a vagrant machine with
  portforwarding between 8000 => 8001

### Create a superuser to access the admin area
```bash
python manage.py createsuperuser
```

Fire http://localhost:8001/admin/

Login with previously created admin credentials and be happy :-)
