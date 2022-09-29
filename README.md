## Задача : 
### *Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.*

## Описание алгоритма решения:
### Сначала объявляем два массива: изначальный и вторый такой же длины. Потом используем метод, в котором применяем цикл for. Внутри цикла проверяем условие, что длина элемента (строки) массива <=3 символов. Если да, элемент первого массива заносится в count элемент второго массива. Переменная count используется, чтобы поочередно перемещать элементы из первого массива во второй, и чтобы потом не было пробелов. После присвоения переменная count увеличивается на 1, и возвращаемся к циклу for, в котором i увеличивается на 1. И так проверяется до последнего элемента массива включительно.

*Графическое представление метода в двух файлах diagram в разных расширениях.
Реализация алгоритма в файле Program.cs*

