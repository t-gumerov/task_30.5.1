# Модуль 30. Поиск элементов с помощью Selenium. Ожидание элемента на странице


Задания 30.3.1 и 30.5.1. Тестирование UI сайта http://petfriends.skillfactory.ru.


Задание 30.3.1

Написать тест, который проверяет, что на странице со списком питомцев пользователя:
п.1. Присутствуют все питомцы.
п.2. Хотя бы у половины питомцев есть фото.
п.3. У всех питомцев есть имя, возраст и порода.
п.4. У всех питомцев разные имена.
п.5. В списке нет повторяющихся питомцев. (Сложное задание).
        
        
Задание 30.5.1.

п.1. В написанном тесте (проверка карточек питомцев) добавьте неявные ожидания всех элементов (фото, имя питомца, его возраст).
п.2. В написанном тесте (проверка таблицы питомцев) добавьте явные ожидания элементов страницы.


В файле conftest.py находятся 2 фикстуры:

1) фикстура с драйвером и переходом на страницу авторизации; 
2) фикстура для перехода на страницу "Мои питомцы". 


В файле settings.py находятся данные об эл.почте и пароле.


Для запуска тестов потребуется установить библиотеки pytest и selenium.
