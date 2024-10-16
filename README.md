### Zapret (Запрет: обход блокировки Discord'а и Youtube'а)
1. Скачать по ссылке https://github.com/censorliber/zapret/archive/refs/heads/main.zip
2. Запустить **`preset_russia.cmd`**

## Перед тем как использовать
### 1. Chromium браузеры
Все конфиги представленные ниже работают только на Chromium подобных браузерах (Chrome, Opera, Vivaldi и т.д.). Поэтому рекомендуем переключиться на них.
<br>
К сожалению в некоторых случаях Яндекс браузер может блокировать работу программы, поэтому рекомендуем воздержаться от его использования.
<br>
Не используйте Cent Browser и иные подобные браузеры со встроенными блокировщиками (Thromium, Ungoogled Chromium, Iridum, Brave и т.д.). Они безусловно полезны, но могут отключать некоторые функции, такие как WebRTC, которая важна для работы Discord. Поэтому для необходимых ресурсов используйте чистые браузеры. 

### 2. Настройки браузера
Для правильной настройки Zapret поставьте на DEFAULT (а не выключите!) протокол QUIC по адресу:
```
about://flags/#enable-quic
```

В настройках браузера включите Comss DNS, Ваш провайдер может блокировать запросы DNS:
```
chrome://settings/security
```

И впишите в строку "Безопасный провайдер DNS":
```
https://dns.comss.one/dns-query
```
Иногда данный DNS сервер не разблокирует заблокированные ресурсы. В таком случае попробуйте сменить DOH от компаний Google DNS, Cloudflare DNS или Next DNS.

**После каждой смены DNS серверов обязательно перезапускайте браузер!**

### По всем вопросам обращаться в группу https://t.me/youtubenotwork
> [!CAUTION]  
> При любых ошибках просьба **ВСЕГДА** оставляйте скриншот и изображение ошибки, не описывайте их на словах, так Вам нельзя будет помочь, так как не понятно что за проблема.
> <br>
> Также следует писать Вашего **провайдера и город**, чтобы можно было составить список рабочих конфигураций для различных провайдеров, который будет не публичный.

> [!WARNING]  
> Если не работает Discord, указывается используете ли вы **приложение** или веб браузер. Если используется **веб браузер** (_что рекомендуется_), то указывайте бренд и имя версии.

> [!TIP]  
> Если совсем отчаетесь то можете написать в [ЛС **БЕСПЛАТНЫЙ** запрос на удалённую настройку](https://t.me/youtubenotwork/4764) через AnyDesk. В любой момент подключение можно завершить и удалить программу.

<div align='center'><a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=60326&s=1' border='0' alt='Free Website Counter'></a><br / ><small></small></div>
