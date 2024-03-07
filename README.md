**ЗАДАЧА**
-/Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] [“1234”, “1567”, “-2”, “computer science”] → [“-2”] [“Russia”, “Denmark”, “Kazan”] → []

**РЕШЕНИЕ**
Создать массив строк arrayOne[]
Создать переменную count и установить ее значение равным 0.
Пройти по каждой строке в массиве arrayOne[]
Если длина строки меньше или равна 3 символам, увеличить count на 1
Создать новый массив arrayTwo[] длиной count
Создать переменную index и установить ее значение равным 0
Пройти по каждой строке в массиве arrayOne[]
Если длина строки меньше или равна 3 символам, добавить эту строку в массив arrayTwo[] на позицию index и увеличить index на 1
Вернуть новый массив arrayTwo[] из строк, длина которых меньше или равна 3 символам
