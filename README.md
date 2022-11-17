# Telegram-Group-Search-Using-Telegrambots
## How To Run
 - Change /src/main/resources/application.properties config
	```
	tgbotapi.botUsername={bot-username}
	tgbotapi.botToken={bot-token}
	```
	> tip:you can apply your bot token using [botFather](https://t.me/BotFather) then type /start and /newbot to apply your bot.
- Change /src/main/resources/application.yml config
	```
	url: jdbc:postgresql://localhost:5432/{your-table-name}?useSSL=false
	```
- Run Java Application TgChannelSearchApplication.java
## Or How to Use
- go to this [bot ](https://t.me/gp8hmF5cPmdPAQWeQzs9s_BOT) and you can first
	```
	1.Export your group chat history.
	2.upload your group chat history(.html file) to this bot.
	3.type searchKeyWord {search keyword}.
	4.you will get keyword if chat content has contain keyword.
	```

That it! hope you enjoy it,if you want some more feature,you can leave your message in issue space,thank you for your time.
