# Проект CatBot

CatBot- это бот для Telegram, который присылает пользователю котиков,
находит котика на фото.

## Установка

1. Клонируйте репозиторий с github
2. Создайте виртуальное окружение
3. Установите зависимости `pip install -r requirements.txt`
4. Создайте файл `settings.py`
5. Впишите в settings.py переменные:
```
API_KEY = "API-ключ бота"
PROXY_URL = "Адрес прокси"
PROXY_USERNAME = "Логин прокси"
PROXY_PASSWORD = "Пароль на прокси"
USER_EMOJI = [":dog:", ":cat:", ":girl:", ":boy:", ":smiley_cat:"]
CLARIFAI_API_KEY = "API-ключ clarifai"
```
6. Запустите бота командой `python bot.py`
