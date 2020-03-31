# quarantine


### /product/category.tpl

```php
.h2_overlay

<div class="quarantine">
    Уважаемые посетители! Мы работаем в условиях карантина с 10:00 - 21:00 без выходных. <br>
    Для Вас доступен самовывоз и бесплатная доставка по Санкт-Петербургу. <br>
    Все курьеры имеют маски и защитные перчатки.
</div>
```

### /product/product.tpl

```php
.top_overlay

<div class="quarantine">
    Уважаемые посетители! Мы работаем в условиях карантина с 10:00 - 21:00 без выходных. <br>
    Для Вас доступен самовывоз и бесплатная доставка по Санкт-Петербургу. <br>
    Все курьеры имеют маски и защитные перчатки.
</div>
```

### header.min.css

```css
/* Карантин */
.h2_overlay, .top_overlay {position: relative;}
.quarantine {
    position: absolute;
    max-width: 100%;
    width: 100%;
    top: -45px;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    color: #b360ad;
    margin-left: 50px;
    text-decoration: underline;
}
@media only screen and (max-width: 1350px) {
    .quarantine br {display: none;}
    .quarantine { max-width: 60%; margin-left: 0; left: auto;right: 0;transform: none;}
}
@media only screen and (max-width: 993px) {
    .quarantine {
        position: static;
        margin-top: 10px;
        text-align: center;
        max-width: 100%;
    }
    
}

/* карточка товара */
.top_overlay .quarantine {
    top: -58px;
    margin-left: 80px;
    color: #f8355e;
}
@media only screen and (max-width: 1350px) {
    .top_overlay .quarantine {font-size: 15px;max-width: 65%;text-align: right;}
}
@media only screen and (max-width: 1200px) {
    .top_overlay .quarantine{line-height: 1.2;}
}
@media only screen and (max-width: 993px) {
    .top_overlay .quarantine{line-height: 1.4;margin-left: 0;max-width: 100%;margin-top: 15px;text-align: center;}
}
/* /Карантин */
```
