# План тестирования
## Введение
Для того, чтобы убедиться в соответствии реальной и ожидаемой работ приложения BuildComponentShop создается данный документ.
## Объекты тестирования 
В качестве объектов тестирования с учетом выбраны следующие атрибуты качества ISO 25010:
1. Надежность:
- доступность - cтепень работоспособности и доступности продукта, когда это необходимо для использования.
- отказоустойчивость - степень, в которой система продукт работает, как предполагалось, несмотря на наличие аппаратных или программных сбоев.
- восстанавливаемость - степень, в которой, в случае прерывания или сбоя продукт могут восстановить данные, на которые непосредственно влияют, и восстановить желаемое состояние системы.
2. Функциональная пригодность:
- функциональная полнота - степень, в которой набор функций охватывает все указанные задачи и задачи пользователя.
- функциональная правильность - степень, в которой продукт обеспечивает правильные результаты с необходимой степенью точности.
## Риски
При отсутствии подключения к сети Интернет каталог товаров может не отобразиться.
## Аспекты тестирования
Для того, что протестировать работу данного приложения необходимо проверить работоспособность всего основого функционала, то есть функциональных требований. Так же будут проверены нефункциональные требования.
Основные функции:
1. Парсинг информации:

- Данная функция должна правильно собрать и обработать полученную информацию с веб-ресурса Remmers.
2. Отображение каталога товаров:

- Данная функция должна корректно отобразить полученную информацию.

3. Работа с корзиной:

- Данная функция должна позволить работу с корзиной товаров , а именно редактировать список товаров в корзине.

4. Поиск категорий:

- Необходим поиск категорий товаров.

Нефункциональные требования:
- Удобство исползования приложением ( весь функционал доступен в пределах 3-7 тапов ).
## Подходы к тестированию
Предполагается использовать ручное тестирование.
## Представление результатов
Результаты тестирования представлены в документе [Test Results](https://github.com/ParkhomenkoArtyom750504/SPoH/blob/master/Tests/Test%20Results.md)
## Вывод

Тестовый план к данному приложению позволяет протестировать его на основную функциональность, а соответственно выявить недоработки и возможное некорректные поведения программы, если они присуствтуют.
В ходе тестирования были успешно пройдены все тесты на фукциональность продукта, а значит можно предполагать, что работа продукта корректна и исправлений не требует.
В процессе игры появились идеи и предложения о возможных нововведениях в игру для дальнейшего ее развития:
- Добавление возможности оплаты товаров напрямую из-под приложения.
- Добавление новостей магазина Remmers.
- Добавить обзоры продукции магазина.
- Добавить отзывы реальных покупателей.