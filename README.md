# Задача

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 

Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


```
["hello", "2", "world", ":-)"] --> ["2", ":-)"]
["1234", "1567", "-2", "computer science"] --> ["-2"]
["Russia", "Denmark", "Kazan"] --> []
```
# Блок схема алгоритма
![](https://lh3.googleusercontent.com/GcdbzK3WEYIsHy6HOnBdQgiq8pF4mRfKqud8hEWh85NH2pxkvni0Mdqr1VcfoFAo4k_i97R1A36MPCXNEt9aY3bnNEPzP_6Y-pS6Paa16L_m6wXSTEU5AVIAO_BptYIV_vlFeryVpButo87e0O1g81l96btigxQwObYD4YDzdDK3VAOX4kOQvVYgMiiFFaryasvzDfG6-KkilyJkAIdB_FDcqa4DoVkpUKqnwBPqCx4nCNcvIYICocQ88WYALrQ-ffNOe1qUaFRI86avlbW8Fu9xf6_dKe7f_U_XGVtLwTnFTT49nAModk8NmhvjQvAl1nkPmpUE9Ev7nHAk3OnnsZPDbtmVa5ATnVKItPyto7JXvvTrLD__JmpAEoZX7aBxpy9MrTz7fP78tw3RNQy8rFCKeEHMnhK_6gDo8PSbNyTI7mp9uetjE-Xg_ckW0OrNkNNvNRCpia2HKShsoAt7wLX_d-El5-jpNab65_hmLXlzjTS7aZYYB5NspLJ-vzSS4uJvvkifV8YpPWuvOOAucq62doNYgztcmScIYtAkOMOvAYNCMifgeT0SWezbLPXRCBPABmnG_MMPta3Z7g89Xa-ydakmznwgbST7AzZHRu43EhhR4ZHKG64eS15vwWMzDR3dI1UrT0ZVXa_OYU6CiLrNip27eXIVCSLCclKn-ZpOyCYUfW_MDneG_P0Vu12d1UphzBfs83R4id1OaAuwR55mnpXXrUsRlH7C_WchEKrEq04B6DnHJB6Kaj8wgb9bZVvjM2Lg-GL1tFAtlSH8NgqE5y_SDotgbMpJY2ZABxoAoWf0vbVFlXV1_daa9wQGeOkFTi36P3IJiKo-Ze-2Gq92eoxVArFkrwGQ2H_KPodpD-Kcbb9CiV7YgDVfB3TfquDlXHnk76lcjODiNarv-8voMapn5EYL_QE51nxechkM=w529-h582-no?authuser=0)
# Решение

На старте задаем одномерный массив строк из пяти элементов, а так же объявляем второй массив с тем же количеством ячеек, что и у первого.

Далее создаем метод, который принимает оба массива. В цикле проверяется длина строки каждого элемента первого массива, и если она совпадает с условием (Length <= 3), то элемент добавлется во второй массив. Метод возвращает этот массив.

Второй массив принимает void метод, которой выводит в консоль все элементы, используя цикл.

