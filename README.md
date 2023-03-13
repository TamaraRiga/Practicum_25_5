# Practicum_25_5
В папке находятся файлы для проведения тестирования на сайте PetFriends.
В папку tests необходимо поместить cromedriver
В папке tests содержит набор тестов, который проверяет, что на странице со списком питомцев пользователя:

1. Присутствуют все питомцы.
2. Хотя бы у половины питомцев есть фото.
3. У всех питомцев есть имя, возраст и порода.
4. У всех питомцев разные имена.
5. В списке нет повторяющихся питомцев.
А также тест из модуля на проверку карточек всех питомцев сайта
Набор тестов включает в себя явные и неявные ожидания.

В файле conftest.py находятся фикстуры, необходимые для подготовки к тестам (авторизация и переход на страницу пользователя с его питомцами).
В файле settings.py находятся email и пароль для авторизации на сайте.
