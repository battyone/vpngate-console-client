## Зависимости

- wget

- openvpn

- dialog

## Возможности

- Получение списка серверов

- Сортировка списка серверов

- Добавление дополнительных опций в конфиг VPN

- Установка соединения с сервером

## Переменные скрипта. 

Настройка скрипта осуществляется путем редактирования переменных скрипта.

### Основные настройки.

LISTADDR="http://www.vpngate.net/api/iphone/" - адрес списка серверов

LISTFILE="servers" - файл со списком серверов на локальной машине

DATADIR="./data" - рабочий каталог

DIALOG="dialog" - команда, вызывающая утилиту dialog.

OPENVPN="openvpn"- команда, вызывающая утилиту openvpn.

### Настройки авторизации.

VPN_LOGIN="vpn" - логин.

VPN_PASS="vpn" - пароль

AUTH_FILE="vpngate.auth" - файл авторизации

AUTH_DIR="$DATADIR" - директория с файлом авторизации.

### Настройки log'а

LOG_FILE="" - путь к файлу log'а

LOG_TTYN="3" - отправлять log на терминал, номер которого указан в переменной

RMLOG=0 - удалять log по выходу из программы (0 - не удалять, 1 - удалять)

LOG_APPEND=0 - дописывать log (0 - не дописывать 1 - дописывать)

## Использование

1. Установите пакет (Slackware) или скачайте основной скрипт, скрипт настройки маршрутизации и опции VPN

2. В случае необходимости измените значения переменных скрипта

3. Измените скрипт маршрутизации в соответствии с вашими настройками

3. Запустите скрипт (vpngate)

4. Обновите список VPN-серверов (пункт основного меню Update VPN List)

5. В случае необходимости отсортируйте список серверов и откорректируйте список дополнительных опций VPN.

6. Выберите пункт меню Connect VPN...

7. Выберите нужный сервер и нажмите OK

## Скриншоты

![Главное меню](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/01-main-menu.png)

Главное меню

![Загрузка списка серверов](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/02-update-vpn-list.png)

Загрузка списка серверов

![Подготовка списка серверов](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/03-update-vpn-list.png)

Подготовка списка серверов

![Параметр сортировки списка серверов](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/04-sort-field.png)

Параметр сортировки списка серверов

![Порядок сортировки](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/05-sort-order.png)

Порядок сортировки

![Опции VPN](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/06-vpn-options.png)

Опции VPN

![Выбор VPN-сервера](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/07-select-vpn.png)

Выбор VPN-сервера

![Информация о VPN-сервере](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/08-vpn-info.png)

Информация о VPN-сервере

![Соединение с сервером](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/09-vpn-connect-ok.png)

Соединение с сервером

![Разъединение](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/10-vpn-disconnecting.png)

Разъединение

![Окно About](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/11-about.png)

Окно About

![Тест соединения](https://raw.githubusercontent.com/tolik-punkoff/vpngate-console-client/main/screenshots/12-test-final.png)

Тест соединения