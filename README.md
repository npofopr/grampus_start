# HTML

Список тэгов(шпаргалка) - https://html5book.ru/examples/html-tags.html
Все про html5 по русски - https://webref.ru/html
Ответы на типовые вопросы - https://webref.ru/recipe

---

# Заготовка

С комментариями (когда перейдем к верстке первого макета, будем использовать вот эту заготовку) - https://github.com/npofopr/grampus_start (https://npofopr.github.io/grampus_start/)

---

# №1 Список популярных тэгов:

### Служебные теги:

* <html></html>
* <!DOCTYPE>
* <meta>
* <head></head>
* <link>
* <script></script>
* <style></style>

### Текст:

* <h1></h1> (по h6)
* <p></p>
* <br>
* <i></i>
* <b></b> или <strong></strong>

### Изображения:

* <img>

### Ссылки:

* <a></a>

### Списки:

* <ol><li></li></ol>
* <ul><li></li></ul>

### Группировка контента:

* <body></body>
* <div></div>
* <span></span>
* <header></header>
* <footer></footer>
* <section></section>
* <aside></aside>
* <nav></nav>
* <main></main>

### Формы:

* <form></form>
* <input>
* <textarea></textarea>
* <label></label>
* <select><option></option></select>
* <button></button>

---

# №2 Список самых используемых тэгов:

<link> подключение файла стилей
<script></script> подключение js скриптов

<h1></h1> (по h3) Заголовки
<p></p> Параграф
<br> Перенос строки
<i></i> Наклонный шрифт(дополнительно используется для стилизации элементов, например иконок)
<b></b> или <strong></strong> Жирный шрифт

<img src="путь_к_картинке" alt="подпись к картинке(необязательно)"> Вставка изображения

<a href="адрес_ссылки"></a> Ссылка. При нажатии переход на страницу указанную в атрибуте href

<ul> Маркированный список
	<li></li> Элемент списка
</ul>

<ol> Нумерованный список
	<li></li> Элемент списка
</ol>

<div></div> Самый распространенный тэг для создания блочного элемента
<span></span>  Самый распространенный тэг для создания строчного элемента

### HTML5 (используется для облегчения индексации страниц поисковыми роботами)

<header></header> Тэг обозначающий шапку
<footer></footer> Тэг обозначающий подвал
<section></section> Разбивка страницы на отдельные секции !!! Обязательно наличие вложенного заголовка (h1-h4)
<aside></aside> Боковая панель вне контента (используется для выноса меню, банеров и прочего вспомогательного контента)
<nav></nav> Основное меню сайта
<main></main> Основной контент сайта

<form action="ссылка_на_пхп_обработчик"></form> Обертка формы
<input type="тип_поля"> Поле ввода. Либо однострочный текст, либо checkbox, либо radio
<textarea> Многострочное поле ввода текста
<label for=""></label> Название поля ввода, при заполненном атрибуте for клик по label может фокусировать на указанное поле(у поля значение атрибута id должен быть равен значению атрибута for).
<select> Станадартный выпадающий список
  <option></option> Элемент выпадающего списка
</select>
<button></button> Кнопка
