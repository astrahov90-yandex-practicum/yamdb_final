# Учебный проект про django-rest на основе docker
![example workflow](https://github.com/astrahov90-yandex-practicum/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
### Описание
Проект API предназначен для хранения базы произведений с категоризацией по жанрам,
годам выпуска и категориям. К произведениям можно создать отзывы.
### Технологии
Python 3.7
Django 2.2.19
Postgres
Nginx
### Подготовка данных
Необходимо заполнить .env файл со следующими переменными:
DB_ENGINE=django.db.backends.postgresql
DB_NAME=postgres
POSTGRES_USER=Имя пользователя БД
POSTGRES_PASSWORD=Пароль пользователя БД
DB_HOST=db
DB_PORT=5432
### Старт контейнера
docker run --name <имя контейнера> -it -p 8000:8000 api_yamdb
### Адрес проекта
Готовый проект можно посмотреть по <a href='http://sai-testlab.ddns.net/redoc/'>ссылке</a>:
### Автор
astrahov90

