# CryptoScreener

[![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/scr_en.png)](https://www.youtube.com/channel/UCiSd7JTmnbap0tVrPlf-Dew)

[**Video review of the screener**](https://youtu.be/5Oa0iQE0sJk "#### **Video review of the screener**")

[`Download`](https://github.com/alex290/CryptoScreener/releases/download/0.3.0-beta/CryptoScreener.zip "`Скачать`")

When updating the release, do not replace the file **data/setting.set**


#### Configuring Telegram Bot

First, let's create a bot

in the telegram search, we enter `BotFather` and we launch this bot `/start`

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot-001.jpg)

Next, select `/newbot` - create a new bot

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot002.png)

And we come up with a name for the bot according to the instructions

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot003.png)

Then we copy the TOKEN of the created bot and paste it into the settings of our program

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot004.png)

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot005_en.png)

Next, you need to find out the chat ID where your bot will send messages.

To do this, we follow the link to the chat Bot

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot006.png)

Запускаем его `/start` И пишем любое сообщение

далее создаем адрес https://api.telegram.org/botTOKEN/getUpdates где Вместо TOKEN вставляем токен бота например https://api.telegram.org/bot123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11/getUpdates и  вставляем в браузер данную ссылку

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot007.png)

Если с первого раза не получится набишите в чате еще сообщение и обновите в браузере страницу. Далее копируем chat -> id сам номер и вставляем в программу.

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot008_en.png)

Для проверки сообщения бота можно нажать на кнопку `тест` в настройках

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot009_en.png)

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot010.png)

Если сообщение пришло значит настройки верные и сигналы будут приходить в зависимости от параметров сигнала
