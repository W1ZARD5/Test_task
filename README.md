# Общие сведения
Приложение, которое позволяет скачивать произвольную HTML-страницу посредством HTTP-запроса на жесткий диск компьютера и выдает статистику по количеству уникальных слов в консоль.
# Технологии
* C#
* ASP CORE
* HtmlAgilityPack
# Задание
Имеется входная строка с адресом web-страницы. Приложение должно скачать web-страницу, сохранить ее на жесткий диск. Затем текстовый контент, который есть на ней (который видит пользователь на странице браузера), разбивать на слова и подсчитывать количество нахождений на странице каждого уникального слова. Разделителями слов считать следующие символы: {' ', ',', '.', '!', '?','"', ';', ':', '[', ']', '(', ')', '\n', '\r', '\t'}

Пример входной строки:
https://www.simbirsoft.com/

Пример вывода статистики вхождений слов:
* СОЗДАЁМ - 1
* ПРОГРАММНОЕ - 1
* ОБЕСПЕЧЕНИЕ - 2
* ДЛЯ - 16
* РОСТА - 1
* ВАШЕГО - 3
* БИЗНЕСА - 3

# Руководство
Программа считывает файл sites.txt из каталога программы
Если его нет, создает тестовый пример
В файле sites.txt адреса сайтов должны находится по строчно, вида https://www.google.com/
