# Проект Telegram Бот для автоматической покупки/продажи коммерческой недвижимости
# Этот проект представляет собой Telegram бота, который осуществляет автоматическую покупку/продажу коммерческой недвижимости. Бот разработан на языке программирования Python с использованием базы данных SQLite и # фреймворка aiogram для работы с Telegram API.

### Установка и настройка
Для установки и настройки проекта, выполните следующие шаги:

Клонируйте репозиторий с помощью команды:

bash
Copy code
`
git clone https://github.com/Reyquazar/pyTelegramBotCommercialProperty.git
`
Установите зависимости, выполнив команду:

Copy code
pip install -r requirements.txt
Создайте файл config.ini и заполните его следующим образом:

csharp
Copy code
[Telegram]
token = YOUR_TELEGRAM_BOT_TOKEN

[Database]
file = database.db
Замените YOUR_TELEGRAM_BOT_TOKEN на токен вашего Telegram бота. Если у вас еще нет токена, создайте нового бота и получите токен, следуя инструкциям от BotFather.

Запустите бота, выполнив команду:

css
Copy code
python main.py
Использование
После успешного запуска бот будет готов к использованию. Добавьте его в свой Telegram аккаунт и начните общение с ним.

Бот поддерживает следующие команды:

/start - Начать общение с ботом.
/help - Вывести список доступных команд и их описание.
/buy - Осуществить покупку коммерческой недвижимости.
/sell - Осуществить продажу коммерческой недвижимости.
При выполнении команд /buy и /sell, бот будет запрашивать необходимую информацию для осуществления операции. Результаты операций будут сохранены в базе данных SQLite.

Структура проекта
main.py - Главный файл, содержащий код для запуска и настройки бота.
bot.py - Основной модуль бота, содержащий обработчики команд и логику взаимодействия с пользователем.
database.py - Модуль для работы с базой данных SQLite.
config.ini - Конфигурационный файл, содержащий настройки бота.
requirements.txt - Файл, содержащий список зависимостей проекта.
