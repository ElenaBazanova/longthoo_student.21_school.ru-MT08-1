
**Какой запрос отправляется на сервер для получения списка типов товаров в шторке "Каталог"?**

```

POST https://sbermegamarket.ru/api/mobile/v1/catalogService/catalog/menu
```


**Какие запросы отправляются на сервер при использовании поиска товаров в каталоге?**

```

POST https://sbermegamarket.ru/api/mobile/v1/catalogService/catalog/search

POST https://sbermegamarket.ru/api/mobile/v1/catalogService/filters/search

POST https://sbermegamarket.ru/api/mobile/v3/catalogService/catalog/searchSuggest
```

**Какой запрос отправляется на сервер при поиске региона или города в модалке выбора вашего региона?**

```
POST https://sbermegamarket.ru/api/mobile/v1/addressSuggestService/address/suggest
```



