### Анализ бизнес-показателей приложения Procrastinate Pro+
## Analysis_of_business_indicators
Требуется провести маркетинговую аналитику развлекательного приложения Procrastinate Pro+.
Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки.
Имеются данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:

* лог сервера с данными об их посещениях,
* выгрузка их покупок за этот период,
* рекламные расходы.

### Нам предстоит изучить:

* откуда приходят пользователи и какими устройствами они пользуются,
* сколько стоит привлечение пользователей из различных рекламных каналов;
* сколько денег приносит каждый клиент,
* когда расходы на привлечение клиента окупаются,
* какие факторы мешают привлечению клиентов.

### Цель исследования:

* Разобраться в причинах убытков компании и помочь ей выйти в плюс.

### Описание данных:

В нашем распоряжении три датасета.


1. `visits_info_short.csv` — хранит лог сервера с информацией о посещениях сайта.

### Структура:

`User Id` — уникальный идентификатор пользователя,

`Region` — страна пользователя,

`Device` — тип устройства пользователя,

`Channel` — идентификатор источника перехода,

`Session Start` — дата и время начала сессии,

`Session End` — дата и время окончания сессии.


2. `orders_info_short.csv` — хранит информацию о заказах.

### Структура:

`User Id` — уникальный идентификатор пользователя,

`Event Dt` — дата и время покупки,

`Revenue` — сумма заказа.


3. `costs_info_short.csv` — хранит информацию о расходах на рекламу.

Структура:

`dt` — дата проведения рекламной кампании,

`Channel` — идентификатор рекламного источника,

`costs` — расходы на эту кампанию.



