# Как запустить проект:
## Клонировать репозиторий и перейти в него в командной строке:

#### git clone https://github.com/Patron322/api_final_yatube.git
#### cd api_final_yatube

## Cоздать и активировать виртуальное окружение:

#### python3 -m venv env
#### source env/bin/activate

## Установить зависимости из файла requirements.txt:

#### python3 -m pip install --upgrade pip
#### pip install -r requirements.txt

## Выполнить миграции:

#### python3 manage.py migrate

## Запустить проект:

#### python3 manage.py runserver

## Документация к проекту доступна по адресу:

#### http://127.0.0.1:8000/redoc/

## Использованные технологии:

#### Python 3.9.7
#### Django 2.2.16
#### djangorestframework 3.12.4
#### djangorestframework-simplejwt 4.7.2
#### Pillow 8.3.1
#### PyJWT 2.1.0
#### requests 2.26.0
