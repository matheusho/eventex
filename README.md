# EventeX

Sistema para controle de eventos desenvolvido no curso Welcome to the Django 14.


### Download:

```bash
$ git clone https://github.com/matheusho/eventex.git
$ cd eventex
$ pip install -r requirements.txt
```
### Env

Renomear arquivo rename-as-.env para .env e definir a `Secret Key`:
```bash
$ mv rename-as-.env .env
```

### Syncdb
```bash
$ python manage.py syncdb --migrate
```

### Run:
```bash
$ python manage.py runserver
```
