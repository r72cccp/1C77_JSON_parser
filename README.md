1C77_JSON_parser
================
1С 7.7 JSON парсер предназначен для разбора данных в формате JSON.

##Парсер строки с данными в формате JSON. 

Данный исходный код предоставляет возможность сделать парсинг (разбор) строки данных и преобразовать их в структуру вложенных друг в друга типов данных "Список значений".

Вложенные друг в друга структуры разбираются в виде пар "Ключ"-"Значение", если идёт разбор вложенной структуры типа {} или в виде пар "Номер"-"Значение", если вложенная структура завернута в квадратные скобки [].

Возвращаемое значение можно разбирать с помощью стандартной функции "Получить(<Имя поля>)" для типа переменной "Список значений".

1С77 JSON парсер
