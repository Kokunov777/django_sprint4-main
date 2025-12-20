# Блогикум часть 3


## Технологии:

- Python 3.9.13
- Django 3.2.25
- SQLite

## Установка (Windows):

1. Клонирование репозитория

```
git clone https://github.com/Kokynov777/django_sprint4.git
```

2. Переход в директорию django_sprint4

```
cd django_sprint4
```

3. Создание и активация виртуального окружения

```
python -m venv venv
source venv/Scripts/activate
```

4. Обновите pip

```
python -m pip install --upgrade pip
```

5. Установка зависимостей

```
pip install -r requirements.txt
```

6. Перейти в папку проекта blogicum и запустить его:

```
cd blogicum
./manage.py migrate
./manage.py loaddata db.json
./manage.py runserver
```

7. Перейти на локальный сервер:

```
http://127.0.0.1:8000/
```

8. Перейти в панель администратора:

```
http://127.0.0.1:8000/admin/
```
