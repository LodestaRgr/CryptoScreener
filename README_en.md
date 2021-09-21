# CryptoScreener

[![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/scr_en.png)](https://www.youtube.com/channel/UCiSd7JTmnbap0tVrPlf-Dew)

[**Video review of the screener**](https://youtu.be/5Oa0iQE0sJk "#### **Video review of the screener**")


------------


### Download Release

[`Download the archive`](https://github.com/alex290/CryptoScreener/releases/download/0.9.0-beta/CryptoScreen.zip "`Скачать`")

[`Download Install`](https://github.com/alex290/CryptoScreener/releases/download/0.9.0-beta/CryptoScreener.exe "`Скачать`")

------------


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

Launching it `/start` And we write any message

next, create an address https://api.telegram.org/botTOKEN/getUpdates where instead of a TOKEN we insert a bot token for example https://api.telegram.org/bot123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11/getUpdates and we insert this link into the browser

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot007.png)

If it doesn't work the first time, write another message in the chat and refresh the page in the browser. Next, copy chat -> id we insert the number itself into the program.

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot008_en.png)

To check the bot's message, you can click on the `test` button in the settings

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot009_en.png)

![](https://raw.githubusercontent.com/alex290/CryptoScreener/main/imghelp/bot010.png)

If the message has arrived, then the settings are correct and the signals will come depending on the signal parameters
