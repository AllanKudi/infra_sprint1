### Проект для владельцев котиков KITTYGRAM:

В этом репозитории представлен код backend и frontend части, иными словами полноценный проект.

Благодаря этому проекту владельцы котов смогут похвастаться своими питомцами!
На сайте можно зарегистрироваться, добавить своего любимца, его фото, окрас и достижения,
а также посмотреть на чужих котиков :)

Все готово, все работает, остается только запустить проект и как это сделать написано ниже :)


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:AllanKudi/infra_sprint1.git
```

Перейти в директорию проекта:

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

Для Windows:

```
python -m venv env
source env/Scripts/activate
```

Для Linux и masOS:

```
python3 -m venv env
source env/bin/activate
```

Установить зависимости из файла requirements.txt через загрузчик pip:

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py makemigrations
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
