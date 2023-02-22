# api yamdb

## Что это за проект?

```
> Это API для проекта Yamdb, позволяющая получать, удалять, редактировать
> данные о произведениях и пользователях, оставлять комментарии и отзывы к произведениям
> Произведения удобно распределены по категориям и жанрам
> Все данные возвращаются в формате JSON
```

## Использованные технологиии:

```
requests==2.26.0
django==2.2.16
djangorestframework==3.12.4
PyJWT==2.1.0
pytest==6.2.4
pytest-django==4.4.0
pytest-pythonpath==0.7.3
djangorestframework-simplejwt==4.8.0
django-filter==21.1
gunicorn==20.0.4
psycopg2-binary==2.8.6
```

## Как запустить проект:

### 1)
```
> Устаноить приложения Docker
```

### 2_
```
> Клонировать репозиторий
```

### 3)
```
> cd infra_sp2/infra
> docker-compose -d --build
> docker-compose exec web python manage.py migrate
> docker-compose exec web python manage.py collectstatic --no-input
```

## Документация:
> Находится на эндпоинте: http://localhost/redoc/ с примерами ответов API

## Авторы проекта:
> Serenity(Users/Auth), Lolozius(Serializers/Views), Nail(Models)
