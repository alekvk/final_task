# Описание решения задачи


## Исходное задание 

Написать программу, которая из имеющегося
массива строк формирует массив из строк, 
длина которых меньше либо равна 3 символа.

Первоначальный массив можно вводить с клавиатуры, либо задать на старте выполнения алгоритма.

При решении не рекомендуется использовать коллекции, лучше обойтись исключительно массивами.

Примеры:

["hello", "2", "world", -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []                                                   
## Описание решения
1.  Задаем первоначальный массив str, содержащий разные по длине строки.

2. Определяем массив строк str2 с размером, равном размеру первоначального массива.

3. Задаем цикл обхода элементов массива str.
Внутри цикла задаем условие: если размер строки (элемента массива) меньше, либо равен 3, то значение этой строки присваивается j-му элементу массива str2. При этом увеличиается на единицу значение переменной j.

4. При помощи метода Array.Resize уменьшаем размер массива str2 до размера значения переменной j.

5. Выводим на экран содержимое массивов str и str2. 


