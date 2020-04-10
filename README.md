# covidFightFakeNews
Telegram bot to validate news

ngrok can be downloaded from here : https://ngrok.com/download
Replace <bot_token> in bot.py


How to run sample :

run bot.py -> "python bot.py"

start server -> "./ngrok http 8080"

For setting up WebHook:

https://api.telegram.org/<bot_token>/setWebHook?url=https://<url_generated_via_running_ngrok_server>.ngrok.io/

Once you webhook, it all set. Now your server is able to read messages received by bot.
