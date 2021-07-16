# CryptoScreener

[Скачать](https://github.com/alex290/CryptoScreener/releases/download/0.0.8-alpha/CryptoScreener.zip "Скачать")

При обновлении релиза не заменяйте файл **data/setting.set**


#### Настройка Telegram Bot

Для начала создадим бота

в телеграм поиске вводим `BotFather` и запускаем данного бота `/start`

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot-001.jpg)

Далее выбираем `/newbot` - create a new bot

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot002.png)

И придумываем название боту согласно инструкции

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot003.png)

Затем копируем ТОКЕН созданного бота и вставляем в настройки нашей программы

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot004.png)

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot005.png)

Далее нужно узнать ID чата где ваш бот будет присылать сообщения.

Для этого мы переходим по ссылке в чат Бота

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot006.png)

Запускаем его `/start` И пишем любое сообщение

далее создаем адрес https://api.telegram.org/botTOKEN/getUpdates где Вместо TOKEN вставляем токен бота например https://api.telegram.org/bot123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11/getUpdates и  вставляем в браузер данную ссылку

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot007.png)

Если с первого раза не получится набишите в чате еще сообщение и обновите в браузере страницу. Далее копируем chat -> id сам номер и вставляем в программу.

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot008.png)