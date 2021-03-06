Фронтенд
========

**Глобальное задание на день**: сделать [Todo-list](http://ahamlett.com/Backbone.localStorage/examples/index.html) и выложить его в интернет

Для тех, кому скучно, или же как задание на будущее: сверстайте и запрогайте [вступительную в школу Хедхантер](https://github.com/vpavlenko/hh-school-frontend)

Введение
========

Что такое веб-страница: [страница](http://vpavlenko.github.io/startup-engineering/frontend/intro/), [фидл](http://jsfiddle.net/LBxWP/1/)

HTML
====

[Домашняя страничка Гвидо ван Россума](http://www.python.org/~guido/) как пример HTML-кода десятилетней давности

[Фидл с примером формы](http://jsfiddle.net/ZJcX2/1/)

[Фидл с примером таблицы](http://jsfiddle.net/b6R9R/)

Задание
-------

1. Создайте у себя на компьютере файл about_me.html, вставьте в него своё имя, свою фотографию и ссылку на свою страничку в контакте.
2. Списки, заголовки, жирный и курсивный текст: [htmlacademy](http://htmlacademy.ru/courses/38/run/16) — жёлтое выделение можно сделать тегом `<mark>`, а можно и забить на него
3. Таблицы: [htmlacademy](http://htmlacademy.ru/courses/39/run/9)
4. Формы: [htmlacademy](http://htmlacademy.ru/courses/46/run/11)

CSS
===

[Домашняя страничка Армина Ронахера](http://lucumr.pocoo.org/)

[Сокращенная версия презентации Вадима Пацева](http://vpavlenko.github.io/startup-engineering/frontend/YWDS-CSS-shortened/) ([а тут полная версия](http://vpavlenko.github.io/YWDS-CSS/))

Задание
-------

1. Размеры, цвет фона, цвет текста: [htmlacademy](http://htmlacademy.ru/courses/41/run/15)
2. Блочная модель: [htmlacademy](http://htmlacademy.ru/courses/44/run/8)
3. Сверстайте содержимое [Todo-list](http://ahamlett.com/Backbone.localStorage/examples/index.html)'а у себя на компьютере.

JavaScript
==========

План
----

1. JavaScript: типы данных, conrol flow, доступ к элементам по id и к содержимому, onclick
2. [DOMContentReady](https://gist.github.com/vpavlenko/9092030)
2. jQuery: селекторы, навешивание обработчиков, изменение значений, генерация тегов, перемещение по DOM-дереву
4. Процесс загрузки страницы (вкладка Networks), событие submit формы и его предотвращение
5. Навешивание эвентов к выбранным элементам и к классу

Примеры
-------

1. Чистый JavaScript для проверки данных в форме: [click](http://jsfiddle.net/u56uW/6/), [submit](http://jsfiddle.net/u56uW/4/)
4. [Демо по событиям нажатий клавиш](http://javascript.info/tutorial/keyboard-events)

7. [jQuery: селекторы, навешивание обработчиков, изменение значений](http://jsfiddle.net/J45tc/10/)
8. [jQuery: генерация тегов](http://jsfiddle.net/Ta576/2/)
9. [jQuery: перемещение по DOM-дереву](http://jsfiddle.net/5CyNu/3/)

2. Пример выбора поездов: [код](https://github.com/vpavlenko/js-todo-task/tree/master/rasp), [результат](http://vpavlenko.github.io/js-todo-task/rasp/)

3. [Навешивание эвентов к выбранным элементом и к классу](http://jsfiddle.net/8YbM9/1/)


Задание
-------

Что реализовать в [Todo-list](http://ahamlett.com/Backbone.localStorage/examples/index.html)'е:

1. Есть пустой список заданий (список строк), можно добавлять новые строчки. Дело добавляется по нажатию Энтера в поле ввода или по нажатию кнопки "Add".
2. Дело можно пометить сделанным. 
4. Текст дела можно менять: по двойному щелчку открывается возможность редактирования. (Hint: поищите свойство `contenteditable`.)
3. Дело можно удалить из списка. (jquery remove)
3. Все дела можно пометить сделанными, а все сделанные дела можно удалить.
5. Все дела автоматически сохраняются в LocalStorage. При перезагрузке страницы все дела достаются из LocalStorage.
6. Прикручен CSS-фреймворк, и всё выглядит более-менее аккуратно. Или всё очень элегантно свёрстано без фреймворка.

Хостинг
=======

Задание
-------

1. Выложите Todo-list на [Hostinger](http://www.hostinger.ru/)

2. Выложите Todo-list в интернет через GitHub Pages


Послесловие
===========

1. Как развиваться: htmlacademy, codecademy, ШРИ.
2. JavaScript: [Ajax-запросы, асинхронность, замыкания](http://jsfiddle.net/eLeV9/2/), переменное число аргументов, модули, класссы и наследование. 
3. Экосистема модулей JavaScript: underscore, require.js, Riot.js, Angular.js, Knockout.js.
4. CSS: [Pure CSS](http://purecss.io/), [Twitter Bootstrap](http://getbootstrap.com/), Modernizr.
5. Дизайнеры, фотошоп, макет.

Литература
==========

1. [Dive into HTML5](http://diveintohtml5.info/)
1. [Understanding Git](http://web.mit.edu/nelhage/Public/git-slides-2009.pdf)
3. John Resig, Bear Bibeault. Secrets of the JavaScript Ninja