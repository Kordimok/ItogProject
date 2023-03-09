Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

Description of the solution algorithm:
Объявляем два массива: имеющийся и вторый, длины которых эдентичны.

Пишем метод, в котором цикл равен длине массива.

Внутри нашего цикла проверяем условия (<=3), если условия выполняются "Да", тогда элемент первого массива заносится в count элемент второго массива.

Переменная count служит для того чтобы поочередно заносить элементы из первого массива во второй и чтобы отсутствовали пробелы.

Переменная count, после присвоения, увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1.

После чего мы переходим к следующиму элементу и наш цикл опять делает проверку, так происходит пока наш массив не дойдед до конца.
