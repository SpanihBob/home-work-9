# home-work-9
ТЕМА: ОБЪЕКТ. МАССИВЫ. ОБЪЕКТ ARRAY. СТРОКИ. ОБЪЕКТ STRING. ОБЪЕКТ DATE. ОБЪЕКТ MATH. ВВЕДЕНИЕ В ОБЪЕКТНО-ОРИЕНТИРОВАННОЕ ПРОГРАММИРОВАНИЕ
Задание 1
Реализовать класс, описывающий окружность. В классе должны быть следующие компоненты:
■ поле, хранящее радиус окружности;
■ get-свойство, возвращающее радиус окружности;
■ set-свойство, устанавливающее радиус окружности;
■ get-свойство, возвращающее диаметр окружности;
■ метод, вычисляющий площадь окружности;
■ метод, вычисляющий длину окружности.
Продемонстрировать работу свойств и методов.
Задание 2
Реализовать класс, описывающий html элемент.
Класс HtmlElement должен содержать внутри себя:
■ название тега;
■ самозакрывающийся тег или нет;
■ текстовое содержимое;
■ массив атрибутов;
■ массив стилей;
■ массив вложенных таких же тегов;
■ метод для установки атрибута;
■ метод для установки стиля;
■ метод для добавления вложенного элемента в конец текущего элемента;
■ метод для добавления вложенного элемента в начало текущего элемента;
■ метод getHtml(), который возвращает html код в виде
строки, включая html код вложенных элементов.
С помощью написанного класса реализовать следующий блок
и добавить его на страницу с помощью document.write().
Обратите внимание. Чтобы получить весь этот html в виде
строки должно быть достаточно вызвать метод getHtml только
у тега с идентификатором wrapper.
Домашнее задание №4 Домашнее задание №4
Задание 3
Реализовать класс, который описывает css класс.
Класс CssClass должен содержать внутри себя:
■ название css класса;
■ массив стилей;
■ метод для установки стиля;
■ метод для удаления стиля;
■ метод getCss(), который возвращает css код в виде строки.
Задание 4
Реализовать класс, описывающий блок html документ.
Класс HtmlBlock должен содержать внутри себя:
■ коллекцию стилей, описанных с помощью класса CssClass;
■ корневой элемент, описанный с помощью класса
HtmlElement;
■ метод getCode(), который возвращает строку с html кодом (сначала теги style с описанием всех классов, а потом
все html содержимое из корневого тега и его вложенных
элементов).
С помощью написанных классов реализовать следующий блок
(см. рис. 2) и добавить его на страницу с помощью document.write().
