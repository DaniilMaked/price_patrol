Скрипт для отслеживания изменений цен на криптовалюты - можно выбрать из заготовленного списка или взять любую другую по идентификатору с coinmarketcap. Работает через бота в Telegram, которому необходимо задать криптовалюту и изменение (например, 1%)
# price_patrol
Запуск Скрипта локально

Убедитесь, что у вас установлены все необходимые библиотеки: pip3 install requests nest_asyncio python-telegram-bot python-dotenv supabase

Создайте файл .env в корневой директории проекта и добавьте туда свои переменные окружения:

API_KEY=your_telegram_bot_api_key COINMARKETCAP_API_KEY=your_coinmarketcap_api_key SUPABASE_URL=your_supabase_url SUPABASE_KEY=your_supabase_key

Запустите скрипт:
python3 price_bot.py
