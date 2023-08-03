
### Баг-репорт №1

**Заголовок:** Ошибка запроса GET сервера 400 Bad Request
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor
**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
GET
	https://online.sberbank.ru/CSAFront/api/oidc/sbid?client_id=52cd75e2-76e1-43ba-ade6-938b2c7d4e7a
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №2

**Заголовок:** Ошибка сервера POST 400 Bad Request
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools 

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
	
POST
	https://sbermegamarket.ru/api/fl?u=6efd37c0-6ff6-11ed-a2cf-b37c7b2b7873&cfidsw-smm=ZCe9wUJMz8hYE4LB1bQectDVjfJkpDAI5abBEIMkal+YPIeLst2jqI1lunIz4Og3karjEWAnB25HS42rX/HXuPFnaSMItYOTvudF+AismYKkz+N/wyQugRcifraQOQdhIPFN8Wt4WbK9uqo1m85XGPAFakMh8CLB/dG2Uu4=
```

**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №3

**Заголовок:** Неуспешная отправка запроса (Причина: не удалось выполнить запрос CORS)
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
Запрос из постороннего источника заблокирован: Политика одного источника запрещает чтение удаленного ресурса на https://cms-res.online.sberbank.ru/sberid/BlackList/Button/No_Button.json.
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №4

**Заголовок:** Ошибка запроса GET сервера (404 Not Found)
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/
3. Нажать на кнопку "о компании" в футере страницы

**Серьезность:** Major

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
	
GET
	https://sbermegamarket.ru/info/about-sbermegamarket-ru/desktop/css/desktop.css
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №5

**Заголовок:** Ошибка во время загрузки ресурсов (HTTP/1.1 502 Bad Gateway)
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
	
GET
	https://sbermegamarketru.webim.ru/button.php
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №6

**Заголовок:** Ошибка запроса шрифта
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/
3. Нажать на кнопку "О компании" в футере страницы

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
downloadable font: rejected by sanitizer (font-family: "Graphik LCG" style:normal weight:400 stretch:100 src index:0) source: https://main-cdn.sbermegamarket.ru/upload/static_pages/e/ab/738/eab738ad5e489ec2e334cf82dd047923/desktop/fonts/GraphikLCGRegular.eot
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №7

**Заголовок:** Неуспешная отправка запроса на чтение удаленного ресурса (vk.com)
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/
3. Нажать на кнопку логотипа социальной сети "VK" в футере страницы

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
Запрос из постороннего источника заблокирован: Политика одного источника запрещает чтение удаленного ресурса на «https://vk.com/rtrg?p=VK-RTRG-1421183-77G99&products_event=view_other&price_list_id=1&e=1&i=0&metatag_url=%2F%2Fsbermegamarket.ru%2Finfo%2Fabout-sbermegamarket-ru%2F&metatag_title=%D0%9E%20%D0%BA%D0%BE%D0%BC%D0%BF%D0%B0%D0%BD%D0%B8%D0%B8%20-%20%D0%9C%D0%B0%D1%80%D0%BA%D0%B5%D1%82%D0%BF%D0%BB%D0%B5%D0%B9%D1%81%20SberMegaMarket.ru». (Причина: Учётные данные не поддерживаются, если заголовок CORS «Access-Control-Allow-Origin» установлен в «*»).
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №8

**Заголовок:** Ошибка Open api access error
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/
3. Нажать на кнопку логотипа социальной сети "VK" в футере страницы

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка

```
v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    onerror https://vk.com/js/api/openapi.js?169:672
    s https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    (Асинхронный: EventHandlerNonNull)
    u https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    makeRequest https://vk.com/js/api/openapi.js?169:678
    ProductEvent https://vk.com/js/api/openapi.js?169:3137
    onViewedOther https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    onViewedOther https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    flushQueue https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    n https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    s https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    (Асинхронный: setInterval handler)
    l https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    init https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    onLoadInitiated https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    loadIntegration https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    queueIntegrationLoad https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    s https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    s https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireUnfiredEvents https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireUnfiredEvents https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    push https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    H https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    $ https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    te https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    setLocationInfo https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    fetchCurrentLocation https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    fetchLocationData https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    identifyRegion https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    mounted https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    nn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    zn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    insert https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0

### Баг-репорт №9

**Заголовок:** Ошибка DDManager Custom Event "Clicked ToCart Button (Desktop + Mobile Main Icon)"
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Открыть Инструменты разработчика
2. Открыть "Console" в DevTools 

**Ожидаемый результат:** 
- В консоле нет ошибок

**Фактический результат:**
- Ошибка
```
page url: https://sbermegamarket.ru/info/about-sbermegamarket-ru/; message: watcher callback; details: TypeError, window.webim.api is undefined, resetWebimVisitor@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:407787
setup/<@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:147844
nn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:536746
h@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:526877
st/b.run@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:527600
er@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:542996
vn/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:537828
ln@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:537227
promise callback*sn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:537317
vn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:537891
tr@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:543614
20144/Tn</e.prototype.update@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:540966
20144/we</e.prototype.notify@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:522899
set@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:524702
setProfile@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:380673
fetchProfile@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:381550
async*mounted@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:155437
nn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:536759
zn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:542500
insert@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:546239
E@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:581518
20144/xi</<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:582431
20144/</e.prototype._update@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:558809
r@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:589761
20144/Tn</e.prototype.get@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:540297
e@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:540210
20144/Lr.prototype.$mount/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:589785
20144/Lr.prototype.$mount@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:590003
88522/<@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:301005
async*78345/Te.prototype.transitionTo/</<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:505844
78345/Te.prototype.transitionTo/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:505822
78345/Te.prototype.confirmTransition/</<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:507706
r@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503571
r@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503609
Ce@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503618
78345/Te.prototype.confirmTransition/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:507609
r@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503571
r/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503600
v/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:507314
Me/</</c<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503928
Re/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:504584
promise callback*Me/</<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:504104
je/</<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:504295
je/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:504271
je@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:504221
Me/<@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503682
v@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:506949
r@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503580
r@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503609
Ce@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:503618
78345/Te.prototype.confirmTransition@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:507340
78345/Te.prototype.transitionTo@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:505665
78345/qe.prototype.init@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:512844
beforeCreate@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:515129
nn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:536759
zn@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:542500
20144/</e.prototype._init@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:556900
Lr@https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2:554416
88522/bi<@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:296031
88522@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:296172
c@https://extra-cdn.sbermegamarket.ru/static/dist/rtm.88e561d8.js:1:157
@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:937939
c.O@https://extra-cdn.sbermegamarket.ru/static/dist/rtm.88e561d8.js:1:480
@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:937959
a@https://extra-cdn.sbermegamarket.ru/static/dist/rtm.88e561d8.js:1:10066
@https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1:81
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №10

**Заголовок:** TypeError: DDManager Custom Event "Viewed Product Listing" Error
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Зайти в каталог 
2. Открыть Инструменты разработчика
3. Открыть "Console" в DevTools 

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка
```

 t.digitalData(...) is undefined
    handler https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    run https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    resolveHandlerAndFireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    trackEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireUnfiredEvents https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireUnfiredEvents https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    push https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    H https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    $ https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    te https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    setLocationInfo https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    fetchCurrentLocation https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    fetchLocationData https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    identifyRegion https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    mounted https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    nn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    zn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    insert https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    E https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    xi https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    _update https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    get https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    e https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    mount https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    $mount https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    88522 https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    transitionTo https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    transitionTo https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Ce https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    c https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Re https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    promise callback*Me/</< https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    je https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    je https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    je https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Me https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Ce https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    transitionTo https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    init https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    beforeCreate https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    nn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    zn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    _init https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Lr https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    bi https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    88522 https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    c https://extra-cdn.sbermegamarket.ru/static/dist/rtm.88e561d8.js:1
    <anonymous> https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    O https://extra-cdn.sbermegamarket.ru/static/dist/rtm.88e561d8.js:1
    <anonymous> https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    a https://extra-cdn.sbermegamarket.ru/static/dist/rtm.88e561d8.js:1
    <anonymous> https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0

### Баг-репорт №11

**Заголовок:** Ошибка Uncaught ReferenceError: product is not defined
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Зайти в каталог 
2. Открыть Инструменты разработчика
3. Открыть "Console" в DevTools 

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка
```
<anonymous> https://sbermegamarket.ru/supermarket/ line 301 > injectedScript:1
    a https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:301
    b https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:302
    Pc https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:65
    e https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:204
    Ia https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:43
    ir https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:205
    gr https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:205
    Fr https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:206
    Nr https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:208
    Vs https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:226
    Ys https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:231
    push https://www.googletagmanager.com/gtm.js?id=GTM-WSJ2VMC:235
    push https://mc.yandex.ru/metrika/tag.js:105
    push https://www.googletagmanager.com/gtag/js?id=DC-10810778&l=dataLayer&cx=c:253
    push https://www.googletagmanager.com/gtag/js:222
    push https://top-fwz1.mail.ru/js/code.js:32
    trackEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    pushEventQueue https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    o https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    s https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    s https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    push https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    _ https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireAddRemoveProduct https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    listenToEvents https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    fireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    push https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    H https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    J https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    updateItems https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    De https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    Oe https://extra-cdn.sbermegamarket.ru/static/dist/main.4782675b.js:1
    nn https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    n https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    _wrapper https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    s https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    p https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    To https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    ht https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Lo https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    m https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    xi https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    _update https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    get https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    e https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    mount https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    $mount https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    init https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    d https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    xi https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    _update https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0

### Баг-репорт №12

**Заголовок:** TypeError: DDManager Custom Event "Clicked ToCart Button (Desktop Dropdown)" Error
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Зайти в каталог 
2. Открыть Инструменты разработчика
3. Открыть "Console" в DevTools 

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка
```
 e.getAttribute(...) is null
    handler https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    run https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    resolveHandlerAndFireEvent https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    trackClick https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    i https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    o https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    s https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    p https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    a https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    a https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    s https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    p https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    a https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
    trackClick https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    track https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    initialize https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    initialize https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    initialize https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:1
    <anonymous> https://cdn.ddmanager.ru/ddm-initialization/f72a2e9d-633c-4ab0-9cff-2c32b4d5cad6.js:2
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0


### Баг-репорт №13

**Заголовок:** Error: Navigation cancelled from "/" to "/catalog/?q=%D0%BC%D0%B8%D1%81%D0%BA%D0%B0%20%D0%B4%D0%BB%D1%8F%20%D0%BA%D0%BE%D1%88%D0%BA%D0%B8&suggestionType=history" with a new navigation.
**Предшествующие условия:**
1. Открыть браузер Firefox
2. Открыть сайт https://sbermegamarket.ru/

**Серьезность:** Minor

**Шаги для воспроизведения:**
1. Зайти в каталог 
2. Открыть Инструменты разработчика
3. Открыть "Console" в DevTools 

**Ожидаемый результат:**
- В консоле нет ошибок

**Фактический результат:**
- Ошибка
```
Se https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Oe https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Ce https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
node_modules.89ca50aa.js:2:503285
    transitionTo https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    a https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Ce https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    confirmTransition https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    c https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Re https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    (Асинхронный: promise callback)
    Me https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    je https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    map self-hosted:221
    je https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    map self-hosted:221
    je https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    Me https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    u https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    g https://extra-cdn.sbermegamarket.ru/static/dist/9621.e453c88a.js:1
    u https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    u https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    r https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    u https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
    v https://extra-cdn.sbermegamarket.ru/static/dist/node_modules.89ca50aa.js:2
```
**Окружение:** Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:109.0) Gecko/20100101 Firefox/114.0