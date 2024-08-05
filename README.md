
# Дипломный проект
<!--Дипломный проект-->

## Тема: создание серверной части для платформы по перепродаже вещей
<!--Тема-->
## Описание
<!--Описание-->
1. Перед нашей командой стояла цель по созданию серверной части проекта для платформы по перепродаже вещей.
2. В данном проекте мы хотели воплотить все полученные в течение всего обучения знания и попробовать свои силы на реальной задаче.
3. В процессе написания кода мы сталкивались с различного рода проблемами. Но совместными усилиями, а также благодаря помощи наставников, все проблемы решались оперативно. В силу слаженной работы всех участников проекта, сроки сдачи не были нарушены.
4. В ходе добавления нового функционала приходилось более углубленно изучать документацию.
   
## Инструкция
<!--Инструкция-->
* Installation
* Usage
* Credits
* License
* Features
Installation
<!--Installation-->
*Для запуска приложения вам потребуется:

1. Установить Docker и Docker Compose.
2. Склонировать репозиторий.
3. Запустить Docker Compose, выполнив docker-compose up в корневой директории проекта.
После выполнения этих шагов ваше приложение будет доступно по адресу '''http://localhost:8080'''. *

Usage
<!--Usage-->
Проект использует следующие технологии и библиотеки:

Spring Boot: Фреймворк для создания веб-приложений на языке Java.
Hibernate: Фреймворк для работы с базой данных.
Docker: Платформа для разработки, доставки и выполнения приложений в контейнерах.
Postgresql: Система управления реляционными базами данных.
H2database: Встроенная база данных для разработки и тестирования.
Liquid Base: Инструмент для управления схемой базы данных.
Lombok: Библиотека, упрощающая написание кода.
Swagger и OpenAPI: Инструменты для создания и документирования API.
Mapstruct: Фреймворк для упрощения маппинга объектов.
Credits
<!--Credits-->
Наша Команда:

Карубеков Сыргак,
Ярина Юлия,
Богомолов Данил,
Мезенцев Константин,
Заноза Максим.
License
<!--License-->
Данный проект создан в учебных целях. Допускается использование данного кода в полном или частичном объеме в других проектах.

Features
<!--Features-->
Бэкенд-часть проекта предполагает реализацию следующего функционала:

Авторизация и аутентификация пользователей.
Распределение ролей между пользователями: пользователь и администратор.
CRUD-операции для объявлений и комментариев: администратор может удалять или редактировать все объявления и комментарии, а пользователи — только свои.
Возможность для пользователей оставлять комментарии под каждым объявлением. Показ и сохранение картинок объявлений, а также аватарок пользователей.
