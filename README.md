# Демо-проект по Django

## Важные файлы, которые мы редактировали:

- `pid/static/css/style.css`
- `pid/templates/pid/index.html`
- `pid/views.py`
- `pidsim/urls.py`
- `pidsim/settings.py`

## Установка

### Установка Python

```
sudo apt install python3.12 python3.12-dev python3.12-pip python3.12-venv
```

### Настройка venv и установка зависимостей

```
python3.12 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Создание проекта

```
django-admin startproject pidsim
cd pidsim
python3 manage.py startapp pid
```

### Добавление файлов проекта

Здесь необходимо добавить/отредактировать файлы проекта:

- `pidsim/urls.py`
- `pidsim/settings.py`
- `pid/static/css/style.css`
- `pid/templates/pid/index.html`
- `pid/views.py`

### Запуск сервера

```
python3 manage.py runserver
```

После этого по адресу `http://localhost:8000/` должна открыться наша страничка
