# Задача

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. 

Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


```
["hello", "2", "world", ":-)"] --> ["2", ":-)"]
["1234", "1567", "-2", "computer science"] --> ["-2"]
["Russia", "Denmark", "Kazan"] --> []
```
# Блок схема алгоритма
![](https://lh3.googleusercontent.com/1hSbIsbBVPBQXEjdWu1yvN7xSIIWvM0f-Qc7Q32Y8wCYZPosvhnoYi9SRQmoJ1-ra8-6dMJhuwSi-YPNa1qqE8grqaDeTqwbJuggTCi0rAi6fI6-G16Ofa6q00CWnVoSRdrCF_mg8EQyG7dPOmrLFiQklBIgw9FOezp0MZwrGvn0TS3vXKyGCrCMRVktIvcejEcNekch71qQT_Vxcj6OmwxbddCSjlVn61mrWrlA5FoqOWGWk0NG1dx4IizOD4YonCSyuFvXoad5MphOFX4vCKDDiihec_egiq67disJRisvAONx4UcyUsx2v2aydKKLCh3r6LsRwLnhI89zY1qQ_7OQEYr5ad4m-XS6bvB17K3lxJeI7VtyYP0EhJZRrHky027tbfTAlglsSz655SLZ0AEOz2jAccHSkMV8zC9VCRScbddwwIb2LHh-qJt5pzujQZyEChx1490UqrcZww4OcLGXtlUbghowxA7FWYZ4J5_MTS2_v3p2ZSopReBaDto5--jBo5knqr6WhN1o-n16akoyPI34SeTgY_AlpUZDXV3x0RhLMheGwBzfjDmeUD68mPi-civR2js9N1metqIMGnX9vZsCHOJU2WpTIR8xmsoKT1Bwh3cCYFPDRoHPgINkr4wDK8-CHRuGwNR6lA188YBOhnWPmuoKJ4O4sX3D4aYryouLhpM9LOIRKDg_YzwDmKREWct9MxJxdax7QAIr9QAAfDjinyu5zVGJAwWeKuDO77sI-5-EFNyPWuwiK6TajE8zUKfjGAbEqoLmw3JNPGQYFvCs0k9tYYAyhMqOehXL44BTeJU57_voK2FjgDgrN9HkUoPRr8nvTKItR353idmLLra42IzHtjngXGI0QgViqcNd2UCZACHINOaSV29scHjeuGHPaNui3a_5lNa2qrAPXaHB_f3xpg4EEDEaoaXI=w529-h582-no?authuser=0)
# Решение

На старте задаем одномерный массив строк из пяти элементов, а так же объявляем второй массив с тем же количеством ячеек, что и у первого.

Далее создаем метод, который принимает оба массива. В цикле проверяется длина строки каждого элемента первого массива, и если она совпадает с условием (Length <= 3), то элемент добавлется во второй массив. Метод возвращает этот массив.

Второй массив принимает void метод, которой выводит в консоль все элементы, используя цикл.

