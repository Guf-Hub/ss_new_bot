# Logistica Telegram bot

Telegram bot (Python >= **3.9**, Aiogram) для организации очереди курьеров.<br/>

[![Donate](https://img.shields.io/badge/Donate-Yoomoney-green.svg)](https://yoomoney.ru/to/410019620244262)
![GitHub last commit](https://img.shields.io/github/last-commit/Guf-Hub/ss_new_bot)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/Guf-Hub/ss_new_bot)
![lang](https://img.shields.io/badge/lang-Python-red)

### Установка
* `git clone https://github.com/Guf-Hub/ss_new_bot.git` - клонирование проекта из репозитория
* `pip install --upgrade pip` - обновить pip
* `pip install -r requirements.txt` - установить пакеты в проект

### Содержимое .env файла
* TELEGRAM_TOKEN - token бота;
* ADMINS - массив (int или str) user id или '@username' администратора(-ов);
* GROUP_ID - массив (int или str) chanal id или '@chanal' канала(-ов).

```dotenv
TELEGRAM_TOKEN=
ADMINS=[]
GROUP_ID=[]
```