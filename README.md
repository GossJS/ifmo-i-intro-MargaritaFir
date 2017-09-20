# ifmo_I_intro
исследование в области веб-языков и моделирования ИС

Адрес текста ЛР:
https://kodaktor.ru/08092017

1. mybalsamirq.png - визуальная модель дизайн-макета сайта;
2. ментальнаякарта.png - карта с навыками;
3. mycompetencies.xml - карта навыков в формате xml-документа;

https://c9.io/margaritafir

Ответ на 6 вопрос:

DTD расшифровывается Document Type Definition (объявление типа документа).

DTD - это не HTML тэг, это инструкция браузеру о версии языка разметки использующегося на странице.

DTD должен объявляться перед самым первым тэгом HTML документа.

Директива doctype необходима, чтобы браузер понимал как обрабатывать текущую веб-страничку, так как существует несколько версий языка HTML, а еще имеется XHTML (EXtensible HyperText Markup Language, расширенный язык разметки гипертекста), который похож на HTML, но различается с ним по синтаксису.

Считается, доктайпы сами по себе не так важны. Скажем, написали вы страницу с доктайпом от HTML 4.01, а потом взяли и добавили туда элементов из другой спецификации — пусть HTML 3.2, пусть HTML5, это не так важно. Браузер все равно никуда не денется и обработает их как умеет, так как он  поддерживает элементы и фичи, а не доктайпы. Единственно у вас может быть неправильное отображение страницы, вследствие не правильной интерпретации кода браузером.

Doctype html5 включает в себя правила предыдущих версий и возможность работы с тегами html4  и не требует наличия DTD файла:
<!doctype html>.

Единственная цель доктайпа для HTML5 — убедиться, что браузер будет обрабатывать следующий после него код, следуя стандарту. Но для валидации его наличие или отсутствие значения не имеет.

