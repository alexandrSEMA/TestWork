# Описание содержимого 

*В данном репозитории содержится две папки:*

* Сhart
* Task

## Chart

*Содержит в себе jpg файл, на котором показана блок-схема*

## Task

*Содержит в себе файл с решением заданной задачи*

# Описание решения задачи

## Условие:
*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами*

## Решение:

1. Задаем массив с разными символами;
2. Задаем второй массив равный длинне первого;
3. Задаем значение " _count_ " для второго массива;
4. Используем цикл " _for_ ", в котором укзываем индекс " _i_ " равный нулю. Пока " _i_ " меньше длинны первого массива, то выполняем следующее условие. Увеличиваем " _i_ " на единицу;
5. Используем условие " _if_ ". Если длинна элемента массива меньше или равна трем символам, то выполняем следующее условие;
6. Присваиваем элемент первого массива второму и увеличиваем " _count_ " на единицу;
7. Возвращаемся к циклу " _for_ " и повторяем все действия до тех пор, пока условие выполняется;
8. Если условие не выполняется, выводим в терминал второй массив.