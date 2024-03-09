Виртуальная стажировка

Федерации спортивного туризма России pereval.online (ФСТР) заказала студентам SkillFactory разработать мобильное приложение для Android и IOS, которое упростило бы туристам задачу по отправке данных о перевале и сократило время обработки запроса до трёх дней.

Пользоваться мобильным приложением будут туристы. В горах они будут вносить данные о перевале в приложение и отправлять их в ФСТР, как только появится доступ в Интернет.

Задача: Создать REST API для мобильного приложения для туристов, должны быть реализованы возможности для добавления информации о перевале с заданными параметрами, просмотра детальной информации о перевале, редактирование данных перевала, а также вывод списка перевалов, добавленных конкретным пользователем с идентификацией по его адресу электронной почты.

Технологии, используемые в процессе реализации проекта: Python Django Pycharm Postgres 

Классы/методы:

1. Класс: SubmitDataApi Метод: submit_data_create Тип HTTP-запроса: POST /submitData Действие: Добавление перевала
2. Класс: SubmitDataApi Метод: submit_data_partial_update Тип HTTP-запроса: PATCH /submitData/{id}/ Действие: Редактирование перевала
3. Класс: SubmitDataApi Метод: submit_data_retrieve Тип HTTP-запроса: GET /submitData/{id}/ Действие: Извлечение данных о перевале
4. Класс: SubmitDataApi Метод: submit_data_user_email_list Тип HTTP-запроса: GET /submitData/user__email={email} Действие: Извлечение списка перевалов пользователя

Project Link: https://github.com/LiubovO/Pereval