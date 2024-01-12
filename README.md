# Seller APIs

Скрипты производят синхронизацию продукции с сайта [Часов](https://timeworld.ru) и интернет магазинов на [Ozon Seller](https://www.ozon.ru/) и [Yandex Market](https://market.yandex.ru).

## Как установить
Вам необходимо создать файл .env и записать туда данные в формате: ПЕРЕМЕННАЯ=значение. 

Для скрипта seller.py доступны 2 переменные:

```
SELLER_TOKEN=

CLIENT_ID=
```

Для скрипта market.py:

````
MARKET_TOKEN=

FBS_ID=

DBS_ID=

WAREHOUSE_FBS_ID=

WAREHOUSE_DBS_ID=
````

Для запуска Python3 должен быть уже установлен.

## Пример запуска кода

```
py seller.py

py market.py
```

### Цель проекта
Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
