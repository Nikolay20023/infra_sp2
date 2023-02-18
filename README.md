# API_yatube 
## Автор: AnnaMolodova, Dmitrii-Kiselev-31, nikolay20023


API_yautube - это API интерфейс предназначеный для развития функционала сайта.

- Type some Markdown on the left
- See HTML in the right
- ✨MaDjango


## Установка 

Чтобы развернуть проект на своем рабочем устройстве запустите [GitBash](https://git-scm.com/downloads)

Установка осущетвляется в таком порядке 

```sh
cd ../"Ваша_папка с проектами/
git clone "ссылка"
```

Ссылку можно найти в репозитории gitHub

Перейдите и в проект и установите виртуальное окружение и запустите его

```sh
python -m venv venv
source venv/Scripts/activate
```

Затем установите все библиотека находяшиеся в requirements.txt

```sh
pip install -r requirements.txt
```

## Запуск API 

Чтобы запустить проект перейдите 

```sh
cd ../yatube_api
python manage.py runserver 
```

## API

Всё.Вы запустили мощный инструмент взаимодействия с сайтом Yatube
Несколько примеров взаимодействия :
```sh
http://127.0.0.1:8000/api/v1/posts/
```
Получение списка постов 
```sh
http://127.0.0.1:8000/api/v1/posts/
```
Создания публикации 
```sh
http://127.0.0.1:8000/api/v1/posts/{id}/
```
Получения определённой публикации
```sh
http://127.0.0.1:8000/api/v1/posts/{post_id}/comments/
```
Получение комментариев и многое другое 
Для ознакомления полного списка метода перейдите 
```sh
http://127.0.0.1:8000/redoc/
```
## Работа
Молодова А.А.
Киселев Д.А.
Судаков Н.В.
