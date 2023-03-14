# Training-block-results

Добавление собранной блок-схемы

Написание программы, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, 
лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

Описание алгоритма решения: 
Создаем массив из слов вручную, пользуясь приведенным примером. 
Для решения задачи используем несколько методов:

SecondArray - для вычисления количества строк, по условию задания, длина которых не превышает 3 символов. 
Переменная count, равна 0. В неё мы будем записывать количество строк, длина которых 3 символа и меньше.
В цикле for проходимся по каждой строке массива. 
Если строка удовлетвор. условию (меньше либо равно трём символам), кладем значение в новый массив. 
После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1.
Повторяем, пока не достигнем конца исходного массива.
Возвращаем новый заполненный массив как результат.
PrintArray – для вывода (печати) на экран.
