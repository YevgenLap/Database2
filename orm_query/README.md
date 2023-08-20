# Работа с базой

## Задание

Каждый маленький сайт может однажды стать большим посещаемым порталом.
С ростом посещаемости размер БД растет и растет время выполнения запроса.
Необходимо оптимизировать запросы, чтобы были исключены запросы к лишним полям.
Подразумевается использование deref, only и select_related.

1) Вывести на шаблон дополнительно авторов и жанры.
2) Используя `defer`, `only`, `select_related` сделать вывод более оптимальным.


## Документация по проекту

Для запуска проекта необходимо:

Установить зависимости:

```bash
pip install -r requirements.txt
```

Провести миграцию:

```bash
python manage.py migrate
```

Запустить отладочный веб-сервер проекта:

```bash
python manage.py runserver
```