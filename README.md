# ------------ Запуск бота --------------- #

1. Установить Python 3.10+ - https://www.python.org/downloads/
2. Установить PostgreSQL - https://www.postgresql.org/download/
3. Установить библиотеки requirements.txt - pip install -r requirements.txt
4. Настройте файл .env
5. Запустите файл bot.py
6. Запустите файл start_webhook.py

# -------------- Настройка ------------- #

1. Откройте файл .env
2. Поле BOT_TOKEN - вставьте токен вашего бота
3. Поле CHAT_ID - вставьте ID чата куда будут присылаться заявки
4. Поля DB_HOST, DB_PASS, DB_NAME, DB_LOG - введите данные от базы данных
5. Поля AVITO_API_KEY, AVITO_CLIENT_ID - введите данные от API Avito
5. Поле - LINK_WEBHOOK_AVITO - введите ссылку на вебхук
6. Поле COOKIES - В формате кортежа добавить куки кворка

# -------------- Запуск вебсервера ------------- #
1. Установите веб-сервер nginx 
2. Установите uvicorn
3. Настройте редирект 8000 порта на локальный сервер uvicorn