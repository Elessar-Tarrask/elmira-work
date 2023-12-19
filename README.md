# elmira-work

№README для программы фильтрации строк

Обзор
Эта программа на Java предназначена для фильтрации строк из массива, создавая новый массив, который содержит только строки длиной 3 символа или меньше. Программа демонстрирует основные операции с массивами и условную логику в Java.

Файлы
FilterShortStrings.java: Основной файл программы. Содержит код для фильтрации строк и тестирования функционала с несколькими примерами массивов.

Как использовать
Скопируйте код из файла FilterShortStrings.java.
Запустите код в любой среде разработки Java или компиляторе.
Программа автоматически выполнит фильтрацию для трех примеров массивов и выведет результаты.

Описание работы программы
Программа начинается с метода main, который содержит примеры массивов строк для фильтрации.
Метод filterStrings принимает массив строк и возвращает новый массив, содержащий только те строки, длина которых не превышает 3 символа.
Сначала программа подсчитывает количество коротких строк в исходном массиве.

Затем создается новый массив подходящего размера.
После этого программа повторно перебирает исходный массив и копирует в новый массив только короткие строки.
Метод arrayToString преобразует массив строк в одну строку для удобного вывода.


Примеры использования
Программа может быть модифицирована для чтения массивов строк из файла, пользовательского ввода или других источников.
Можно изменить условие фильтрации для работы с другими критериями длины строк.
