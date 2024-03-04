# CMS EDU kirkir
 
---
CMS платформа электронного обучения на Django.

---
 
***
## Особенности проекта
- Система авторизации пользователей
- 

## Стек
- Python 3.11
- Django 4.1
- 
-  
- 
- 
___


## Текущий прогресс
- 
- 

### Особенности приложения с визуальными закладками
- 
- 
- 
- 
- 
- 
- 
- 
- 

## Подготовка и запуск проекта
### Склонировать репозиторий на локальную машину:
```
git clone 
```
***- Установите зависимости из файла requirements.txt:***
```
pip install -r requirements.txt
```

***- Примените миграции:***
```
python manage.py migrate
```

### Запускаем внешние БД в докере:
Установить и настроить PostgreSQL и Redis в докере

```
docker pull redis
docker run -it --rm --name redis -p 6379:6379 redis
```
***- В папке с файлом manage.py выполните команду для запуска локально:***
```
python manage.py runserver
```
Cоздать и заполнить .env файл в корневой директории
```
SECRET_KEY = "ваш_ключ_Django"
```


## Об авторе <a id=7></a>

Киреев Александр Олегович  
Python-разработчик (Backend)  
E-mail: kireev20000@yandex.ru
Telegram: @kireev20000
