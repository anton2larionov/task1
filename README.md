## Тестовое задание

Задачи, требовавшие решения:

1. Первая программа принимает на вход имя файла fileName и число N, N может меняться от 1 до миллиарда. Программа должна создать бинарный файл с именем fileName и записать туда N псевдослучайных чисел Pi, получаемых по формуле: P(i) = P(i-1) + rand(1,2); P(0) = 0, rand(1,2) – псевдослучайное число в диапазоне [1;2].

2. Вторая программа принимает на вход имя файла, созданного предыдущей программой, и два произвольных числа – A и B. Ее задача – вывести количество чисел Pi в файле таких что A < Pi < B наиболее эффективным способом. Второй программе известна формула генерации чисел в файле, но неизвестно их количество N.

Разработка выполнена в Eclipse IDE for C/C++ Developers.

Параметры сборки:
g++ -std=c++11 -O0 -Wall -c -fmessage-length=0 -o Source\Main.o ..\Source\Main.cpp 
