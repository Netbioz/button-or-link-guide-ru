# Кнопка или [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия")?

>Я знаю хабр не для жалоб, 
>но доколи
>использовать ты  будешь
>— [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") вместо кнопок <UserName />‽


Содержание
----------
* [Введение](#in)
* [Ссылки](#links)
* [Кнопки](#buttons)
* [Дизайнеру](#designer)
* [Спасибо](#thx)

<a name="in"></a>



Если коротко:
=============
Используйте для кнопок — кнопки, а для [ссылок](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") — [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия").

>Для кнопок использовать [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") не комильфо.
------
------------
---------------
-----КДПВ-----
----------
--------
------------


Введение:
=========
---------
```html
<a href="javascript:;">Ссылка которая кнопка</a>
```
Когда наводят указатель на [ссылку](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") которая кнопка то в левом нижнем углу появляется надпись javascript:;:
![javascript:;](https://slasher.ru/articles/link-or-button/javascript.png)
Или адрес с решёткой: 
![https//site.name/page.html#](https://slasher.ru/articles/link-or-button/octothorpe.png)

`ПКМ` на такой кнопке, контекстное меню любезно предложит
![Контекстное меню предлагает открыть [ссылку](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") в новой вкладке, сохранить, копировать…  ](https://slasher.ru/articles/link-or-button/mrb.png)

`ctrl` + `ЛКМ` на такой кнопке откроют новую вкладку на которой будет ровно таже страница с которой она была открыта

Кроме того такая [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") с решёткой в качестве [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия"), станет `:visited` если ещё не стала до этого и преобретёт соотстветствующее стелевое оформление. Если дизайнер его конечно не зарезал, что в большинстве случаев конечно зря, о чём ниже.

В JavaScript скриптах для таких кнопок дополнительно используется `e.preventDefault()`, чтобы предотвратить действие кнопки по умолчанию (переход по [ссылке](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия")) — это костыль.

`<a href="//link.url">Ссылка</a>`
---------------------------------
Если клик приведёт к смене адреса, этот адрес можно скопировать, отправить по электронной почте, на него можно снова зайти этот адрес не приводит на страницу где эта [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") была нажата **— это [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия")**.

У [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") должны быть стили для обычного, `:active`, `:visited`, `:focus`, `:hover` состояний.

Антипатерн:
-----------
```css
a {
    color: black !important;
    text-decoration: none !important;
    cursor: default !important;
}
```
Поздравляю! С такими стилями все ваши [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") визуально превратятся в обычный текст. Найти их на странице станет крайне затруднительно.

И помните, если вы ставите `!important` и не очень понимаете почему вы без него не можете обойтись, то читайте это слово как **импотент**. Возможно вам нужно немного  изменить селектор для того, чтобы перекрыть тот который вам мешает.



<a name="links"></a>

Ссылки:
=======
Пример различных состояний:
![текст с различными состояниями ссылки](https://slasher.ru/articles/link-or-button/link_sates_example.png)
-----------------------
`a` — обычное состояние
-----------------------
```css
a { 
    color: #0645ad;
    cursor: pointer;
    text-decoration: none;
}
```
В  обычном состоянии `a`  должна быть  синей или подчёркнутой, а лучше и синей и подчёркнутой, чтобы пользователь без наведения мыши понимал, что это — [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия"). Пользователь привык к тому, что синие слова на странице это [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия"), даже если они не подчёркнуты. Если вам не нравится синий цвет для [ссылок](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия"), меняйте его, но обязательно [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") подчёркивайте.



---------------------
`a:hover` — наведение
---------------------
```css
a:hover {
    text-decoration: underline;
}
```
Когда курсор находится над [ссылко](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия")й, она становится `:hover` и в данном примере преобретает подчёркивание. Так пользователь поймёт, что это *точно* [ссылка](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") на которую можно кликнуть.

----------------------------
`a:focus` — фокус клавиатуры
----------------------------
```css
a:focus {
    text-decoration: underline;
}
```
Когда на [ссылку](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") устанавливается указатель перемещаемый табулятором `TAB ↹`
она становится `:focus`. В 2016 году это может показаться странным, но есть люди которые работают с сайтам посредством клавиатуры. У некоторых вовсе сломана мышь. В любом случае, занулять `:focus` состояние — это преступление против таких людей. 
Особые спецэфекты применять не обязательно, достаточно таких как у `:focus`.
CSS чтобы не писать дважды:
```css
a:focus, a:hover {
    text-decoration: underline;
}
```



-----------------
`a:active` — клик
-----------------
```css
a:active {
    color: #faa700;
}
```
Важное состояние `:active` происходит когда пользователь уже кликнул на [ссылку](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия"), но клавишу ещё не отпустил. Помогает пользователю понять, что его клик сработал и он не нужно кликать по ней несколько раз, чтобы точно перейти на другую страницу.



---------------------------------------
`a:visited` — ранее посещённая страница
---------------------------------------
```css
a:visited {
    color: #0b0080;
}
```
>Можно все посмотреть‽

`:visited`, поможет пользователю не забыть какие странички он уже открывал  не открывать повторно. Так вместе с `:active` и `:hover` мы чуточку разгрузим интернет от случайных загрузок и сделаем его чуть лучше и быстре.

------------------
------------------

>_Слова в [ссылке](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") должны подчиняться правилам русского языка, капс не позволителен (исключение — аббревеатуры)










<a name="buttons"></a>

HTML5 `<button>Кнопка</button>`
===============================
Если клик не меняет адрес страницы, адрес нельзя скопировать и нельзя этим адресом поделиться — это кнопка.

>В кнопке позволителен капс при условии, что вы не используете аббревеатуры. Особенно в неочевидных местах.
Если у вас встречаются аббревеатуры, то верхний регистр в кнопке не желателен, выделяйте их другим сопособом. Не искушайте пользователей тапать по тому, что не тапается. У пользователей тачскрина нет возможности подсмотреть `:hover` или `:focus` состояние. Ну или есть, но происходит это всё не очень удобно, обычно уже после свершившегося тапа. 

Доступность
-----------

`<button />` может быть  недоступен на архаичных браузерах или устройствах. У кнопок не применятся стили без специальных JavaScript скриптов. 
Но вас это не должно беспокоить. На таких устройствах часто и JavaScript не работает. И быть может CSS.
>Вообще если следовать идеалогии, что всё, что должно обрабатываться JavaScript'ом, должно добавляться JavaScript'ом. Такой проблемы вовсе не возникнет. 

>Что *JSΩ*, то *JSॐ*   ! Как говориться.



Состояния
=========
Похожи на состояния у [ссылок](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") за исключением того, что у кнопок нет состояния `:visited`, зато есть состояние `:disabled`.
Обычно дефолтное оформление браузера выпиливается основательно, иногда с нейтрализацией отображения состояний отличных от обычного.
_Да. Этот гайд для тебя, любитель превратить веб-страницу в бумажный аналог._

Стилей для этих штучек понадобится немного больше, но всё не так страшно. Кроме того ребята из Twitter и отчасти Google уже позаботились о реализации велосипеда. 
Тёплый ламповый [Bootstrap](http://getbootstrap.com/css/#buttons) и новомодный [MaterializeCSS](http://materializecss.com/buttons.html) например.

Отображение
===========
Так выглядит `<button>Кнопка</button>` моём Chrome 54:
![отображение состояний кнопки](https://slasher.ru/articles/link-or-button/button_states.png)
На картинке `button`, `button:hover`, `button:focus`, `button:active` соответственно.

Без излишеств. Но учитывая движение Google в направлении *Material Design*, вполне может статься так, что в скором времени их заменят на [подобные аналоги](https://material.google.com/components/buttons.html "сайт презентация концепта Material Design от Google").

![Material Design кнопки серые стандартные](https://material-design.storage.googleapis.com/publish/material_v_9/0Bx4BSt6jniD7WlduMk1kbTRzQWc/components_buttons_main15.png)
![Material Design кнопки синие](https://material-design.storage.googleapis.com/publish/material_v_9/0Bx4BSt6jniD7UTh2dExpSlRVWVU/components_buttons_main16.png)


CSS
===
_Для наглядности — мой вариант велосипеда который выглядит странновато, но для примера сойдёт._
![Состояния кнопки в порядке: обычное, наведение, клик, отключена](https://slasher.ru/articles/link-or-button/button_bicycle_states.png)
Обычная, наведение, клик, отключена соответственно.
----------------------------
`button` — обычное состояние
----------------------------
```css
button {
    background: none;
    outline: none;
    border: none;
    text-transform: uppercase;
}
```



----------------------------------------------
`button:hover`, `button:focus` — при наведении
----------------------------------------------
```css
button:hover, button:focus {
    color: hsla(108, 12%, 0%, 1);
    box-shadow: -1px 1px 2px hsla(108, 62%, 42%, 1);
    background-color: hsla(108, 62%, 92%, 1)
}
```



--------------------------------
`button:active` — в момент клика
--------------------------------
```css
button:active {
    color: hsla(108, 42%, 32%, 1);
    box-shadow: -2px 4px 8px hsla(64, 64%, 42%, 1);
    background-color: hsla(64, 64%, 92%, 1);
}
```


----------------------------
`button:disable` — отключена
----------------------------
```css
button:disabled {
    color: hsla(0, 0%, 64%, 1);
    background: none;
    box-shadow: none;
    opacity: 1;
}
```






<a name="designer"></a>
Дизайнеру
=========
>Ты цээсэсов можешь и не знать, но состояния — отрисовать обязан!

От дизайнера помимо макета с обычным состоянием [ссылки](https://ru.wikipedia.org/wiki/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B0_(%D0%B7%D0%B0%D0%BF%D0%B8%D1%81%D1%8C) "Ссылка (запись) — Википедия") или кнопки, требуется прилагать различные состояния, дабы не устраивать верстальщику батхерт.
Например так:
![текст с различными состояниями ссылки](https://slasher.ru/articles/link-or-button/link_sates_example.png)
![Состояния кнопки в порядке: обычное, наведение, клик, отключена](https://slasher.ru/articles/link-or-button/button_bicycle_states.png)

>Ребята из Google [сделали такой](https://material.google.com/components/buttons.html) макет☺.


<a name="thx"></a>

Спасибо
=======
Спасибо, что дочитали. Всё здесь написаннное не является 100% истиной в последней инстанции.

[Репозиторий ](https://github.com/KasperGreen/button-or-link-guide-ru)




