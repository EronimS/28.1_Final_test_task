Модуль 28_Final_test_task
Финальный тестовый проект SkillFactory курса QAP

Автоматизированное тестирование UI сайта: https://besttea.ru/ с использованием PyTest и Selenium.

С тест-кейсами можно ознакомиться по ссылке: https://docs.google.com/spreadsheets/d/1RTK8KCflb1t7n3BocpGApRJ9gztEZ8vB/edit?usp=sharing&ouid=113523719246476717062&rtpof=true&sd=true

В папке pages в файле base_page.py находится конструктор webdriver и общие для всех тестируемых страниц методы.

В папке pages в файлах cart_page.py, main_page.py, search_page.py находятся методы для соответствующих тестируемых страниц.

В папке pages в файле "locators.py находятся все локаторы.

В корне проекта в файле conftest.py находится фикстура с функцией открытия и закрытия браузера. Для запуска тестов необходимо поменять путь до webdriver на свой.

В корне проекта в файле pytest.ini зарегистрированны метки маркеровок тестов.

В корне проекта в файле requirements.py описаны используемые библиотеки.

В корне проекта в файлах test_cart_page.py, test_main_page.py, test_search_page.py находятся тесты. Все тесты помечены номером который совпадает с номером тест-кейса в файле: https://docs.google.com/spreadsheets/d/1RTK8KCflb1t7n3BocpGApRJ9gztEZ8vB/edit?usp=sharing&ouid=113523719246476717062&rtpof=true&sd=true Во всех файлах с тестами находятся закомментированные команды для запуска тестов из командной строки (# pytest -v --tb=line test_main_page.py)
