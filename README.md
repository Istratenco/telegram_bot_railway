# Telegram Bot on Railway

## Установка

1. Создайте Railway проект.
2. Добавьте переменную среды `BOT_TOKEN` в настройках Railway.
3. Railway автоматически установит зависимости из `requirements.txt` и запустит `python bot.py`.

### Локальный запуск
```bash
pip install -r requirements.txt
cp .env.example .env
python bot.py
```