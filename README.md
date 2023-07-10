#### Список выполненных задач:

* Разобраться со структурой проекта (onboarding).
* Удалить социальные сети: vk, yandex.
* Вынести чувствительную информацию (логин, пароль БД, 
идентификаторы для OAuth регистрации/авторизации, настройки почты) в отдельный проперти файл.
Значения этих проперти должны считываться при старте сервера из переменных окружения машины.
* Сделать рефакторинг метода com.javarush.jira.bugtracking.attachment.FileUtil#upload чтоб он использовал 
современный подход для работы с файловой системой.
* Добавить локализацию минимум на двух языках для шаблонов писем (mails) и стартовой страницы index.html.
* Тесты переделаны на testcontainers вместо H2.
* Написать тесты для всех публичных методов контроллера ProfileRestController. Хоть методов только 2,
но тестовых методов должно быть больше, т.к. нужно проверить success and unsuccess path.