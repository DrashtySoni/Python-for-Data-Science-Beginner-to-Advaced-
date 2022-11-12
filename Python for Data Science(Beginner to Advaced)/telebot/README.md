# Telegram Bot

## Features

- Text Response
- Image Response
- Video Response
- Document Type Response
- Audio Response
- Poll
- Quick reply Buttons
- Buttons with the links

## Installation

Requires [python](https://www.python.org/) to run.
Create Virtual Evironment

```sh
virtualenv env --python=python3
```
Now activate virtual Evironment
```sh
source env/bin/activate
```
Download [ngrok software](https://ngrok.com/download) to run.

Install all the required libraries.
```sh
pip install -r requirements.txt
```
## Execution

1. Setup the bot in telegram using @BotFather and generate your API Token
2. Modify the Token in telegrambot.py
3. Next, Run ngrok http://127.0.0.1:5000/
4. Further, https://api.telegram.org/bot<Your Bot Token>/setWebhook?url=<URL that you got from Ngrok>

Then run python Flask app.
```sh
python telegrambot.py
```
5. Run the code and test in browser and there you go!