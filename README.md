# C/C++ in Technopark Mail.Ru Group
#### Задача A-3. Задача о максимальном подотрезке.
```bash
Time limit:	14 s
Memory limit:	64 M
Составить программу определения такого максимального подотрезка среди элементов заданного целочисленного массива, 
элементы которого увеличиваются по порядку на 1. 
Подотрезок массива - это часть ("кусок") массива, который включает в себя все элементы исходного массива от некоторого 
начального индекса до некоторого другого конечного индекса без изменения порядка следования элементов. 
Элементы подотрезка функция должна вернуть через указатель-параметр, а ее длину — через возвращаемый результат. 

Формат входных данных: 
N - длина входного массива 
A1 ... An - целочисленный массив 
Формат выходных данных: 
N - длинна найденного подотрезка 
A1 ... An - подотрезок 

Гарантируется, что все значения помещаются в 32-битный целый тип (int). 
Если заданный подотрезок не найден, или если найден только вырожденный подотрезок (длиной 1), 
необходимо вывести только длину - 0. 
Если подходящих подотрезков несколько, то необходимо вывести информацию (длину, подотрезок) про первый из них.

Программа должна уметь обрабатывать ошибки во входных данных (отрицательное количество элементов и др.). 
В случае возникновения ошибки нужно вывести в поток стандартного вывода сообщение "[error]" (без кавычек) и завершить выполнение программы. 

ВАЖНО! Программа в любом случае должна возвращать 0. Не пишите return -1, exit(1) и т.п.
Даже если обнаружилась какая-то ошибка, все равно необходимо вернуть 0! (и напечатать [error] в stdout).
```
