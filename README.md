# Задача

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 

Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


```
["hello", "2", "world", ":-)"] --> ["2", ":-)"]
["1234", "1567", "-2", "computer scince"] --> ["-2"]
["Russia", "Denmark", "Kazan"] --> []
```

# Решение

На старте задаем одномерный массив строк из пяти элементов, а так же объявляем второй массив с тем же количеством ячеек, что и у первого.

Далее создаем метод, который принимает оба массива. В цикле проверяется длина строки каждого элемента первого массива, и если она совпадает с условием (Length <= 3), то элемент добавлется во второй массив. Метод возвращает этот массив.

Второй массив принимает void метод, которой выводит в консоль все элементы, используя цикл.

