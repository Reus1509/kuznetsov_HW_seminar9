# **Телефонный справочник**

**Структура приложения (модули)**

1. main (основной модуль)
2. logger (модуль логирования)
3. bot.py (модуль телеграм-бота)
4. .gitignore
5. crud
6. user_interface
7. data_generation (модуль генерации БД)

**Как запустить проект**

1. Для запуска с помощью консоли:
    - скачать проект в локальный репозиторий;
    - в консоли ввести команду "python3 main.py";
    - в случае необходимости создания рандомной базы контактов раскоменнтировать строку #7 (метод dg.start()) модуля main.py;
    - следовать инструкциям в консоле.
2. Для запуска телеграм-бота:
    - скачать проект в локальный репозиторий;
    - обновить Python до версии 3.10.5;
    - настроить окружение, введя в консоле поочередно команды: 
        - python3 -m venv .libraries;
        - pip install pyTelegramBotAPI;
    - при необходимости обновить библиотеку до последней версии (следуя инструкциям в консоле)
    - перезапустить консоль;
    - в корневой папке проекта создать файл с названием "token.csv", в котором в первой строке добавить индивидуальный токен телеграм-бота, после чего сохранить изменения файла;
    - в консоле ввести команду "python3 bot.py" или "python bot.py" (при необходимости установить версию Python 3.10.5)
    - Адрес бота: t.me/n_k_telephone_bot
