В данном задании вам предстоит работать с языком программирования Python 3 в любой операционной системе.

## Задача

Необходимо написать два консольных приложения на языке Python. Первое приложение рекурсивно каждые 2 секунды сканирует определенную папку на жестком диске (папка передается через аргумент приложения) и передает через TCP соединение второму приложению (ip адрес и порт передаются через аргумент) путь и размер файлов при их изменении (в том числе появлении и удалении) в данных папках.

Второе приложение принимает все TCP соединения от любого количества запущенных первых приложений (параллельно) и выводит путь к файлу, размер и тип изменения (новый файл, удаленный файл, измененный файл) в консоль, добавляя информации о времени, когда было получено сообщение.

Пример использования: первое приложение запускается на наборе рабочих станций, которые нам интересны. Второе приложение запускается на рабочей станции системного администратора для
анализа поведения пользователей в определенной (у каждого своей) папке на их компьютерах.

## Требования

- Файлы могут быть любого размера
- Поддержка кириллических имен файлов *

**Важно**
- Задания, помеченные * — дополнительные, не обязательные.
- Можно использовать любые пакеты Python.
