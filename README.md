# api_yatube:

## Описание:

API для проектра социальная сеть [Yatube](https://github.com/E-bean/Yatube).

Доступ к чтению публикаций есть у любого пользователя.

Для авторизированных пользователей доступны добавления и изменения публикаций,
добавления комментариев и подписка на авторов.

Аутентификация осуществляется по JWT-токену.

## Технологии:
Python 3.7, 
Django 2.2.19, 
Django REST Framework, 
SQLite3

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/E-bean/api_yatube
```

```
cd api_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
cd yatube_api
```
```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
