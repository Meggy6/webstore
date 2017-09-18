## Верстка онлайн-магазина Shopy

### Просмотр верстки через Google Pages:
* Первая страница магазина - https://meggy6.github.io/webstore/app/index.html
* Вторая страница магазина - https://meggy6.github.io/webstore/app/category.html
* Страница продукта - https://meggy6.github.io/webstore/app/product.html
---
### Используемые библиотеки JS:

#### JQuery
Используется для стилизации форм

#### FlexsliderJS - [Github](https://github.com/woocommerce/FlexSlider)
Используется для создания карусели картинок на странице

#### Slicknav - [Github](https://github.com/ComputerWolf/SlickNav)
Используется для создания мобильного адаптивного меню для низких разрешений экрана

#### Bootstrap JS Carousel 
Используется для создания карусели картинок на странице

#### Gulp
Используется для автоматизации работы фронтенд-девелопера. В этом проекте выполняет такие функции:
* создание вендорных префиксов CSS - `gulp css`
* обновление браузера после обнаружения изменений в файлах проекта - `gulp browser-sync`
* создание спрайта из картинок в src - `gulp sprite`
* минимизация JS - `gulp scripts`
* минимизация CSS - `gulp css-libs`
* мониторинг за изменениями в папках css, js, sprite, html - `gulp watch`
* сжатие картинок - `gulp img`