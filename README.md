# Test

## Запуск
~~~~
$ git clone https://github.com/exynil/test.git
~~~~

~~~~
$ cd test
~~~~

~~~~
$ docker-compose up
~~~~

## Задание
Есть тестовый файл в формате .xslx. Его необходимо обработать и записать данные в базу.

Необходимо:
  - прочитать данные из файла
  - обработать данные, привести к единому формату
  - создать таблицу
  - записать данные в таблцу

Название колонок таблицы должно совпадать с названием колонок в файле.

Поля содержащие внешние id лучше сделать строковыми для более удобной работы.

Поля содержащие суммы должны иметь тип NUMERIC.

Обязательные библиотеки для использования:
  - pandas (для работы с данными)
  - sqlalchemy (для работы с базой)

Базу использовать локальную - sqlite.