# whitelister
Бот для добавления списка игроков в белый список на вашем сервере на Python.

**ШАГИ УСТАНОВКИ И ИСПОЛЬЗОВАНИЯ**
1. Установите нужные для работы библиотеки *(только mcipc)* `pip install mcipc`
2. В релизе скрипта уже есть файл в который требуется загрузить никнеймы. *Учтите, что 1 никнейм – 1 строка.*
3. Установите свои параметры RCON. *(9-11 строки)*
4. Запустите скрипт и наслаждайтесь, при возникновении проблем задайте вопрос.

**НАСТРОЙКА RCON НА СЕРВЕРЕ**
1. Перейдите в `sever.properties`
2. Найдите строку `enable-rcon=` и замените `False` на `True`
3. Найдите строку `rcon.port=` *У вас может быть установлен любой порт, но вам нужно указать один из открытых портов на сервере. ОСНОВНОЙ ПОРТ НЕ ПОДОЙДЁТ!*
4. Установите `rcon.password=`, это пароль по которому можно будет получить доступ к RCON. *(Советуем указать надёжный пароль, и никому его не говорить а то будет очень плохо.)*
5. Перезапустите сервер и RCON настроен)
