# Learning-Log

> Веб-приложение с именем Learning Log, при помощи которого                                                                                                пользователь сможет вести журнал интересующих его тем и создавать записи 
> в журнале во время изучения каждой темы. Домашняя страница Learning Log 
> содержит описание сайта и приглашает пользователя зарегистрироваться 
> либо ввести свои учетные данные. После успешного входа пользователь получает возможность создавать новые темы, добавлять новые записи, читать 
> и редактировать существующие записи.





```bash
pip freeze > requirements.txt
```

```bash
pip install -r requirements.txt
```

```bash
django-admin.py startproject learning_log .
```

```bash
python manage.py makemigrations
python manage.py migrate
```

```bash
python manage.py runserver
```

```
python manage.py startapp learning_logs
```

```
python manage.py createsuperuser
```

