# Задача :
## Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


**Последовательное описание алгоритма:**  

* Объявляетса два массива - **array1** и **array2**
* **Методом**, включающим цикл соразмерный длине массива, осуществляется проверка условия внутри цикла (<=3)
* Если значение - **True**, то элемент первого массива записывется в переменную **count** второго массива
* Значение переменной **Count** последовательно увеличивается на **1**, возвращаясь к циклу **for**, в котором переменная **i** увеличивается на **1**, до конца проверки цикла.