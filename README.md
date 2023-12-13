# Blog

Этот проект представляет собой веб-приложение для создания кратких постов, построенное на базе Django. Приложение позволяет пользователям зарегистрироваться, войти в систему, создавать посты, редактировать и удалять их, также есть возможность комментировать и ставить лайки/дизлайки. 

## Установка и запуск

1. Клонирование репозитория

   Перейдите в папку, куда будет сохранен проект.
   
   Клонируем репозиторий:   `git clone https://github.com/Peca2003/Blogs.git`

2. Создание виртуального окружения

   Открываем проект в PyCharm.

   Создаем виртуальное окружение:   `python3 -m venv venv`

   Активизируем виртуальную среду:   `source venv/bin/activate`
   
3. Установка зависимостей

   Установим зависимости:   `pip install -r requirements.txt`
   
4. Запуск сервера

   Запустим сервер:   `python manage.py runserver`