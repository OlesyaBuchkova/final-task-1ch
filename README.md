# задача
Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

[“1234”, “1567”, “-2”, “computer science”] → [“-2”]

[“Russia”, “Denmark”, “Kazan”] → []

# Решение 
Мы создаем 2 массива (array и finalarray). В первом массиве задаем его размер [4] и прописываем содержание как в примере [“Hello”, “2”, “world”, “:-)”]. Второй массив равер длине первого массива.

Далее мы создаем метод который будет проверять строки из первого массива на длинну (она должна быть меньше и равна 3) и будет передавать значение в finalarray.
Так же мы создаем count который приравниваем 0 - это необходимо что бы положить элемент из array в finalarray с индексом count.  
Если наше условие выполняется (array[i] <= 3), то мы в элемент finalarray[count] переносим значение array[i] и прибавляем в count +1. И так до тех пор пока не проверим все значения первого массива.   

Второй метод мы создаем для вывода на консоль итогового массива.

В последних строчках мы запускаем два метода.

# Проверка кода

Для проверки кода можно заменить в пятой строчке значения массива на свои, главное что бы их количество не превышало 4.

