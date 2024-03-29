# django_test_oauth

### Установка:

1) Склонируй репозиторий
2) Зайди в репозиторий (```cd django_test_oauth```)
3) (опционально) Создай виртуальное окружение - [windows](https://mothergeo-py.readthedocs.io/en/latest/development/how-to/venv-win.html), [linux](https://netpoint-dc.com/blog/python-venv-ubuntu-1804/) 
4) Установи необходимые библиотеки (```pip install -r requirements.txt```)
5) Зайди в папку с проектом Django (```cd oauth_sandbox```)
6) Создай миграции (```python manage.py makemigrations```)
7) Примени миграции (```python manage.py migrate```)
8) Теперь должно запускаться (```python manage.py runserver```), по умолчанию сайт будет [здесь](http://127.0.0.1:8000/)


### Настройка (обязательно!):

1) Создай суперюзера (```python manage.py createsuperuser```) - это нужно для доступа к [админке](http://127.0.0.1:8000/admin)
2) Зайди в [админку](http://127.0.0.1:8000/admin)
3) Зайди во вкладку Social applications (у тебя должно быть пусто на этой странице) и нажми на кнопку "создать": ![image](https://github.com/Mortie1/django_test_oauth/assets/75158078/dcacac89-0bb7-42fc-a9ef-da4bb8add55e)
4) Заполни поля для каждого провайдера. Эти ключи вбивал на рандом руками, тебе нужно их получить самому - [Google](https://www.section.io/engineering-education/django-google-oauth/) (смело проматывай до Step 4), [Yandex](https://oauth.yandex.ru/) (зарегайся тут и создай ключи, если что-то не понятно, то пиши). Поля key и settings не трогай: ![image](https://github.com/Mortie1/django_test_oauth/assets/75158078/56762954-1b8f-4cba-9783-702b999afe10)

5) Заходи на [свой сайт](http://127.0.0.1:8000) и пробуй залогиниться 
