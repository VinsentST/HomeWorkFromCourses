# hw-1-responsive

Сверстать проект в двух вариантах:

- flexbox
- grid

- Требования к каждому варианту:

- Виджет должен хорошо выглядеть на смартфонах, планшетах, ноутбуках и больших экранах. Например, если элементы не вмещаются в одну линию, то они должны переноситься на новую строку и делать это адекватно. Сам виджет должен растягиваться/сжиматься и контент внутри него тоже.

- Виджет должен выглядеть адекватно в разных браузерах (Google Chrome, FF, Edge, IE11)

- CSS должн быть написан с использованием БЭМ методологии

- Использование любого препроцессора будет плюсом

# hw-2-js-functions

Написать небольшие программы для решения задач на JavaScript.

1. Написать функцию,разделяющую предложение передданым ей символом.
2. Написать функцию,возвращающую массив собственных перечисляемых свойств объекта.
3. Написать функцию,переводящую все символы введеной строки в верхний регистр.
4. Написать функцию, переписывающие кахдое слово в переданном предложении в обратном порядке.
5. Написать функцию,которая повторяет указанное количество раз символ,следующий на цифрой.
6. Написать функцию, определяющую наибольшее и наиманьшее число,среди введенных аргументов.

###### 7. Создать функцию transform,осуществляющую данную операцию:

         const baseArray = [10, 20, 30, 40, 50]
         const newArray = transform(baseArray);
         console.log(newArray[0]());//10

8.  Написать функцию,суммирующую переданные аргументы.
9.  Написать функцию,уменьшающую введенный аргумент до нуля с запаздиванием.
10. Написать собственную функцию bind.

# hw-3-oop

Вы хозяин небольшого кафе быстрого питания. Ваше меню состоит из следующих позиций:

###### 1) Гамбургер

    - маленький (+50 тугриков, +20 калорий)
    - большой (+100 тугриков, +40 калорий)

    Гамбургер может быть с одним из нескольких видов начинок (обязательно):

    - сыром (+10 тугриков, +20 калорий)
    - салатом (+20 тугриков, +5 калорий)
    - картофелем (+15 тугриков, +10 калорий)

###### 2) Салат (цена и калории указаны за 100г)

    - Цезарь (+100 тугриков, +20 калорий)
    - Оливье (+50 тугриков, +80 калорий)

###### 3) Напиток

    - Кола (+50 тугриков, +40 калорий)
    - Кофе (+80 тугриков, +20 калорий)

Необходимо написать программу, для расчета стоимости и/или каллорийности заказа посетителя.
В заказе могут быть как одна, так и несколько позиций разных видов. (Например заказ может состоять из 2х гамбургеров(один большой, другой маленький), салата Оливье(150г) и кофе). В заказ можно как добавлять позиции, так и удалять из него лишнее (при условии, что оно там есть). После оплаты заказа он должен стать не редактируемым - ничего добавить или удалить из него больше нельзя.

# hw-4-todo-list

Необходимо написать todo list.

1. Можно добавлять/удалять задачи из списка
2. Можно пометить выполнена/не выполнена задача из списка
3. При добавлении задачи можно устанавливать дедлайн на ее выполнение
4. Можно фильтровать отображаемые задачи по: 1) сделано/не сделано 2) по дедлайну: завтра, неделя
5. Использовать паттерн "модуль"
6. на 5 с +: при обновлении страницы в браузере, добавленные таски в списке и вся информация о них должна оставаться
