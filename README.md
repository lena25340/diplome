# Diplome2024
Проект  тестирование был сделвн по сайту Fun&Sun. 
По данному сайту было прироведенны провернки 5 проверок на api тестиррования и 5 проверок  на  ui тестировния. 
При тестирование было проведенно 9  позитивные проверок и 1 негативная проверка 
технические делили 
- язык програмирования: Python
Бибилиотеки:
allure - для генерации отчета
pytest - для запусков теста 
selenium - для авторизации взаимодействия с веб- прилоложением через браузер 
  Тесты ui.py
  test_check_autofill_moscow- Тест проверят автозаполнение города напровления
  test_negative_empty_field- Тест проверят пройдет ли если поле не заполненно
  test_header-'Тест проверят бронирования отеля
  test_search_tour-Тест проверят какие есть туры
  test_tour_request- Тест проверят мы можем оставить заявку

 Тест api:
 test_search_by_origin- Тест проверят возврат кода 200 при отправке запроса на поиск города Душанбе
 test_search_by_cities- Тест проверят возврат кода 200 при отправке запроса по городам направления
 test_search_by_wishList- Тест проверят возврат кода 200 при отправке билеты из Москвы
 test_search_by_moskow- Тест проверят возврат кода 200 при отправке из Москвы

Запуск тестов: 
pytest test_api.py - команда для запуска только АПИ тестов 
pytest test_ui.py - команда для запуска только UI тестов 
pytest - команда для запуска всех тестов