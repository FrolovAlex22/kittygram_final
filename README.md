### Описание:
Kittygram — сервис для публикации данных о котиках.

После регистрации пользователи могут выложить публикацию о своих котиках. Приложить фотографию, указать имя, цвет, возраст, и достижения котика.

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/FrolovAlex22/kittygram_final
```

```
cd backend
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:


```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

### Примеры запросов :

Получение списка всех котиков:

```
projectkittygram.ddns.net/
```

Получение информации о конкретном котике:

```
projectkittygram.ddns.net/cats/{id}/
```

### Использованные технологии:

При работе над проектом, применялись следующие библиотеки:

```
Django==3.2.3
djangorestframework==3.12.4
djoser==2.1.0
webcolors==1.11.1
psycopg2-binary==2.9.3
Pillow==9.0.0
pytest==6.2.4
pytest-django==4.4.0
pytest-pythonpath==0.7.3
PyYAML==6.0
```

### Об авторе:

Проект выполнен студентом 68 когорты "Яндекс практикума" курса "Python разработчик". 
Фроловым Александром
