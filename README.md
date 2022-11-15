# Final Task

## Задача

Написать программу, которая из имеющегося массива из строк, длина которых меньше либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Примеры:**

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] 

[“1234”, “1567”, “-2”, “computer science”] → [“-2”] 

[“Russia”, “Denmark”, “Kazan”] → []

## Алгоритм решения

1. Запрашиваем у пользователи элементы исходного массива; 

2. Формируем исходный массив; 

3. Перебираем значения исходного массива; 

4. Проверяем элементы массива по очереди на соответствие условию: длинна строкового элемента меньше или равна трем (3); 

5. Если условие выполняется, то этот элемент кладем в новый массив; 

6. Повторяем пункты 2 и 3 до тех пор, пока не достигнем конца исходного массива; 

7. Возращаем новый заполненый массив как результат. 

## Блок-схема алгоритма

![1](https://user-images.githubusercontent.com/113132692/201841426-f0c29724-9de0-4d6a-bf56-ba8e59e6cf43.jpg)

Решение задачи лежит в папке Task.
