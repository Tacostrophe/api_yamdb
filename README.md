# Yamdb

### Описание
**Yamdb** - это проект сайта для оценки произведений (фильмов, книг, музыки), путем написания отзывов и выставления оценок (численных значений). Данных проект создан в самоучебных целях.

#### Доступный функционал:
- регистрация пользователя;
- добавление произведения;
- публикация отзывов с оценкой произведения;
- комментарии к отзывам.

### Инструкция по развертыванию

Клонировать репозиторий:

```
git clone https://github.com/Tacostrophe/api_yamdb.git
```
Все нижеперечисленные действия выполнять из api_yamdb/

В репозитории создать и активировать виртуальное окружение:
```
python3 -m venv /path/to/new/virtual/environment
```
```
source /path/to/new/virtual/environment/bin/activate
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
python api_yamdb/manage.py migrate
```
Запуск проекта:
```
python api_yamdb/manage.py runserver
```

<sub>Всегда рад замечаниям и советам</sub>
