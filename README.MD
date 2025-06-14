# Django Project

## Установка

1. Клонировать репозиторий:

git clone <репозиторий>


2. Создать и активировать виртуальное окружение:

python3 -m venv venv
source venv/bin/activate


3. Установить зависимости:

pip install -r requirements.txt


4. Выполнить миграции базы данных:

python manage.py migrate


5. Запустить сервер разработки:

python manage.py runserver


## Запуск

Сервер будет доступен по адресу: `http://127.0.0.1:8000/`

## Описание

Проект на Django, сервер работает через WSGI.  
Все HTTP-запросы доступны через объекты `request.GET`, `request.POST`, `request.META`.  
Пользователь по умолчанию — AnonymousUser.

## Примечания

- Использовать Python 3.8 или выше  
- Виртуальное окружение обязательно  