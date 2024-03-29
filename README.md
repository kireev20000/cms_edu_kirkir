# CMS EDU kirkir
 
---
CMS платформа электронного обучения на Django.

---
 
***
## Особенности проекта
- система регистрации и аутентификации пользователей
- возможность создавать, редактировать и удалять курсы
- добавлять модули в курс и их переупорядочивать
- используется кеш-бэкенд на Redis
- реализован API-интерфейс
- отдельный чат для студентов каждого курса (ASGI, WebSocket, Redis)

## Стек
- Python 3.11
- Django 4.1
- Memcached
- Redis
- Django Redisboard
- Django Rest Framework
- Django Channels
___

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
Telegram: @kireev20000

