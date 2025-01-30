# IMEItestbot

Телеграм бот предназначен для получения информации по IMEI.

Клонируйте репозиторий: git clone https://github.com/sergeyvakhrin/IMEItestbot.git

Заполните в корне файл .env по примеру .env.sample

Рабочий файл main.py

В Телеграм в BotFather заведите нового бота и получите токен

Полученный токен поместите в .env

Если вы находитесь в белом списке бота, то сразу можете делать запрос, 15-ти значный код IMEI.

Если такой код существует и нет ошибок, то получите ответ в виде:
* Модель MacBook (13-inch, Aluminum, Late 2008)
* IMEI2 005065074496948
* Серийный номер ZR26SE05A1X

Белый список находится в файле settings.py
