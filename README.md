# Репозиторий V4

## chains.json

### Описание
Этот JSON-файл содержит информацию о сетях:

1. **id**: Идентификатор сети.
2. **idAndroid**: Идентификатор сети для Android.
3. **prefix**: Префикс сети.
4. **name**: Название сети.
5. **symbol**: Символ сети.
6. **iconUrl**: URL-ссылка на иконку сети.
7. **relayChain**: ID основного токен сети.
8. **relayChainAndroid**: ID основного токена сети для Android.
9. **typesUrl**: URL-ссылка на файл с типами данных сети.
10. **typesUrlAndroid**: URL-ссылка на файл с типами данных сети для Android.
11. **nodes**: Список узлов сети.
    **id**: Идентификатор узла.
    **url**: URL для подключения к узлу.
12. **assets**: Список токенов сети.
    **symbol**: Символьное отображение токена.
    **type**: Тип токена (нативный / ORML / другие).
    **typeAndroid**: Тип токена для Android.
    **typeExtras**: Дополнительная информация о токене:
        **currencyIdAndroid**: ID токена в блокчейне.
        **currencyIdScale**: ID s.c.a.l.e кодака для ORML переводов.
        **currencyIdType**: ID типа сети для ORML переводов.
        **existentialDeposit**: Минимальная сумма чтобы считать аккаунт активным.
13. **explorers**: Список ссылок на исследовательские сервисы сети:
    **subscan**: Применим ко всем.
    **polkascan**: Применим ТОЛЬКО к Polkadot и Kusama.
    **subid**: Применим ко всем.
14. **subscanApiHost**: Хост API для Subscan.

## assets.json

### Описание
Этот JSON-файл содержит информацию о токенах:

1. **name**: Название токена.
2. **symbol**: Символ токена.
3. **decimals**: Количество десятичных знаков для токена.
4. **iconUrl**: URL-ссылка на иконку токена.
