# api_final_yatube
### Описание
API для социальной сети блогеров Yatube.
### Технологии
Python 3.7
Django 2.2.16
### Запуск проекта в dev-режиме
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/serebrennikovalexander/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3.7 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip3 install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Автор
Александр Серебренников
