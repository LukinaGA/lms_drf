# Learning Management System on DRF

## Описание

Платформа для онлайн-обучения

## Содержание

* модуль manage.py в корне проекта
* папка static
* директория config
* директория lms
* директория users
* папка media

1. **lms** содержит модули для функционирования приложения lms, директорию с миграциями

2. **config** с основными настройками проекта

3. **users** отвечает за логку работы с пользователем

4. **static** включает в себя статические файлы

5. **media** предназначена для хранения медиафайлов


*Приложение lms содержит:*
1. Сериализаторы и представления для модели Course (ViewSet)
2. Сериализаторы и представления для модели Lesson (Generic)


Запуск программы осуществляется через модуль manage.py