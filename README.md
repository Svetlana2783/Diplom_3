# Diplom_3
Задание 3: веб-приложение 
Тестирование API для Stella Burgers https://stellarburgers.nomoreparties.site/

Восстановление пароля
Проверки:
переход на страницу восстановления пароля по кнопке «Восстановить пароль»,
ввод почты и клик по кнопке «Восстановить»,
клик по кнопке показать/скрыть пароль делает поле активным — подсвечивает его.
Личный кабинет 
Проверки:
переход по клику на «Личный кабинет»,
переход в раздел «История заказов»,
выход из аккаунта.
Проверка основного функционала
Проверки:
переход по клику на «Конструктор»,
переход по клику на «Лента заказов»,
если кликнуть на ингредиент, появится всплывающее окно с деталями,
всплывающее окно закрывается кликом по крестику,
при добавлении ингредиента в заказ, увеличивается каунтер данного ингредиента
залогиненный пользователь может оформить заказ.
Раздел «Лента заказов»
Проверки:
если кликнуть на заказ, откроется всплывающее окно с деталями,
заказы пользователя из раздела «История заказов» отображаются на странице «Лента заказов»,
при создании нового заказа счётчик Выполнено за всё время увеличивается,
при создании нового заказа счётчик Выполнено за сегодня увеличивается,
после оформления заказа его номер появляется в разделе В работе.


Установлены библиотеки:

pip install pytest - установка фреймворка для тестирования.

pip install requests - установка библиотеки для выполнения HTTP-запросов.

pip install faker - генерация фейковых данных.


pip install -r requirements.txt - установлены зависимости.

pytest tests --alluredir=allure_results - запуск тестов.

allure serve allure_results - отчёт в Allure.




