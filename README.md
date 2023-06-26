### Проект YaMDb (групповой проект). Python-разработчик (бекенд) (Яндекс.Практикум)

### Описание:
Данный проект был использован для практического применения загрузки проекта на удалённый сервер

Проект Taski позволяет пользователями создавать, редактировать, помечать завершёнными и удалять различные задачи

### Как запустить проект:

Проект активен, работает на сервере. Доступен по ссылке:
```
https://chesterton.gotdns.ch
```

Для запуска backend на своей машине клонируйте репозиторий:
```
git clone git@github.com:Starkiller2000Turbo/taski.git
```

Измените свою текущую рабочую дерикторию:
```
cd /taski/backend/
```

Создайте и активируйте виртуальное окружение

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Обновите pip:
```
python3 -m pip install --upgrade pip
```

Установите зависимости из requirements.txt:

```
pip install -r requirements.txt
```

Создайте миграции:

```
python manage.py migrate
```

Запустите сервер:

```
python manage.py runserver
```

Для запуска frontend на своей машине измените директорию:
```
cd /taski/frontend/

```

Запустите npm:
```
npm run start
```
