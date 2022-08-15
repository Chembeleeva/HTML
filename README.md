# HTML

HTML (HyperText Markup Language) - это язык гипертекстовой разметки. Сразу хочу отметить, что 
HTML не является языком разработки, языком программирования. Поэтому не ведитесь на то, когда вас спросят, 
например, какие языки программирования вы знаете, не нужно говорить HTML. HTML это подвид XML (eXtensible 
Markup Language), т.е. это расширенный язык разметки и он используется для тестирования API, он 
прописывается в SOAP протоколе. 

Текст документа заключается в тег <html>. Текст документа состоит из заголовка и тела, которые выделяются соответственно тегами <head> и <body>.
В заголовке (<head>) указывают название HTML-документа и другие параметры, которые браузер будет использовать при отображении документа.
Тело документа (<body>) — это та часть, в которую помещается собственно содержимое HTML-документа. Тело включает предназначенный для отображения текст и управляющую разметку документа (теги), которые используются браузером.


HTML (HyperText Markup Language) — «язык гипертекстовой разметки». Именно он определяет содержание и структуру веб-контента. HTML не является языком программирования; это язык разметки, и используется, чтобы сообщать вашему браузеру, как отображать веб-страницы, которые вы посещаете. HTML состоит из элементов - тегов, которые позволяют управлять контентом на странице, допустим, сделать слово ссылкой или выделить в тексте слова курсивом.

Тег — это HTML-элемент, состоящий из имени элемента окруженного < и >

ествует две важных категории элементов в HTML — элементы блочного уровня и строчные элементы. 

Блочные элементы:

Окажутся в новой строке после любого контента до них.
Любой новый контент окажется в новой строке после блочного.
Элементы блочного уровня не вкладываются в элементы строчного уровня, но могут вкладываться в элементы блочного уровня.
Блочными элементами являются абзацы, списки, меню навигации, подвал сайта.
<p>, <h1> - <h6>, <div>, <ol>, <ul>, <li>, <nav>, <aside>, <article>, <header>, <footer>, <details>, ...
Строчные элементы:

Не приводят к появлению новой строки в документе.
Содержатся в элементах блочного уровня. Обычно встречаются внутри абзаца.
Окружают небольшие части содержимого (т.е не содержат абзацы или группировки контента).
Строчными элементами являются ссылки, акцентирующие элементы.
<span>, <strong>, <em>, <img>, <a>


Тег <p> представляет собой абзац текста. На странице может быть любое количество абзацев. Абзац всегда начинается с новой строки.

Теги <h1> - <h6> представляют собой заголовки с 1-6 уровни.

Обычно на странице присутствует один заголовок первого уровня h1. Крайне редко используются заголовки с 3-6 уровни.

Элемент div - это блочный элемент, универсальный контейнер для группировки контента, он не влияет на контент, пока не будет стилизован при помощи CSS. Пример использования ниже, мы будем рассматривать CSS дальше, сейчас нас интересует только HTML.
