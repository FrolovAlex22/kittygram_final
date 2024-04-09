![Static Badge](https://img.shields.io/badge/Python-blue?logo=python&logoColor=%23F7DF1E)
![Static Badge](https://img.shields.io/badge/Django-%23092E20?logo=django)
![Static Badge](https://img.shields.io/badge/Django%20rest%20framework-red?logo=django&labelColor=%23092E20)
![Static Badge](https://img.shields.io/badge/GitHub-%23181717?logo=github)
![Static Badge](https://img.shields.io/badge/nginx-%23009639?logo=nginx)
![Static Badge](https://img.shields.io/badge/JavaScript-%23F7DF1E?logo=javascript&labelColor=%23181717)
![Static Badge](https://img.shields.io/badge/PostgreSQL-%234169E1?logo=postgresql&logoColor=white)
![Static Badge](https://img.shields.io/badge/Docker-%232496ED?logo=docker&logoColor=white)
![Static Badge](https://img.shields.io/badge/GitHub%20Actions-%232088FF?logo=githubactions&logoColor=white)

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
python-dotenv==0.10.1
```

### Об авторе:

Проект выполнен студентом 68 когорты "Яндекс практикума" курса "Python разработчик". 
Фроловым Александром
