# WebApi. Практика Telnet
## Выполнение запроса к сайту c помощью Telnet
- Отправляем запрос к сайту e1.ru. Нам приходит ответ, что этот адрес устарел и нужно перейти на www.e1.ru, отправляем запрос к нему ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.43.55.png)
- Нам приходит ответ, что необходимо использовать протокол HTTPS. Тут мы к сожалению бессильны, потому что Telnet умеет работать только с HTTP, однако трехсотый код был получен
## Задание 3 Telnet
- Запросить данные GET запросом с ресурса ip. Выполнить запрос методом GET ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.47.44.png)
- Выполнить запрос методом POST ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.51.04.png)
- Если мы укажем длину контента, меньше заданной строки, строка обрежется на заданной нами длине. Если же указать большую длину, запрос не отправится, пока мы не введем недостающие символы.
- Отправить запрос на установку Cookie. Просмотреть список установленных Cookie ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.52.39.png)
- Отправить запрос на страницу с перенаправлением ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.53.25.png)
## Задание 1 openSSL
- Подключиться по openssl к https://wikipedia.org и отправить запрос: ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.55.09.png) ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.58.31.png) ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2013.58.40.png)
- Мы видим, что сервер отправляет сообщение о том, что нужно использовать протокол HTTPS, с которым умеет работать openSSL, в отличие от Telnet. Также мы можем видеть, что русский язык обрабатывается в нечитабельной кодировке, поэтому кириллицу стараются не использовать в адресной строке
## Задание 3 openSSL
- Запросить данные GET запросом с ресурса ip ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2014.01.37.png) ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2014.01.47.png)
- Выполнить запрос методом GET ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2014.02.37.png)
- Выполнить запрос методом POST ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2014.02.55.png)
- Если мы укажем длину контента, меньше заданной строки, строка обрежется на заданной нами длине. Если же указать большую длину, запрос не отправится, пока мы не введем недостающие символы. Тут все аналогично Telnet
- Отправить запрос на установку Cookie. Просмотреть список установленных Cookie. Отправить запрос на страницу с перенаправлением ![](https://github.com/MikhaillVodolaginn/WebApiTelnetOpenSSL/blob/main/Снимок%20экрана%202023-10-22%20в%2014.03.07.png)
## Парсер на Selenium WebDriver
- парсер
## Парсер на requests
- парсер
