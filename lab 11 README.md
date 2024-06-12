
**Лабораторна робота №11: Advanced Working with Arrays of Numbers in Python**

Мета роботи:
Ознайомитися з різними методами роботи з масивами чисел у Python. Навчитися застосовувати ці методи для вирішення задач, пов'язаних з обробкою та аналізом числових даних.

Опис завдання:
Написати функцію task1, яка обчислює суму квадратів всіх чисел у масиві.
Вхід: [1, 2, 3]
Вихід: 14

Написати функцію task2, яка повертає суму всіх елементів масиву, які більше або дорівнюють середньому значенню масиву.
Вхід: [1, 2, 3, 4, 10]
Вихід: 14

Написати функцію task3, яка сортує масив чисел за частотою появи елементів від найбільшої до найменшої. Якщо два числа мають однакову частоту, то менше число повинно йти першим.
Вхід: [4, 6, 2, 6, 4, 4, 6]
Вихід: [4, 4, 4, 6, 6, 6, 2]

Написати функцію task4, яка знаходить відсутнє число в масиві, що містить усі цілі числа від 1 до n, крім одного.
Вхід: [1, 2, 4, 5]
Вихід: 3

Написати функцію task5, яка знаходить довжину найдовшої послідовності послідовних елементів у невідсортованому масиві.
Вхід: [100, 4, 200, 1, 3, 2]
Вихід: 4

Написати функцію task6, яка обертає масив праворуч на k кроків.
Вхід: [1, 2, 3, 4, 5], 2
Вихід: [4, 5, 1, 2, 3]

Написати функцію task7, яка обчислює масив добутків всіх чисел, крім числа на поточному індексі, без використання ділення.
Вхід: [1, 2, 3, 4]
Вихід: [24, 12, 8, 6]

Написати функцію task8, яка знаходить максимальну суму підмасиву у одновимірному масиві чисел.
Вхід: [-2, 1, -3, 4, -1, 2, 1, -5, 4]
Вихід: 6

Написати функцію task9, яка повертає всі елементи 2D матриці у спіральному порядку.
Вхід: [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
Вихід: [1, 2, 3, 6, 9, 8, 7, 4, 5]

Написати функцію task10, яка знаходить k найближчих точок до початку координат (0, 0) на 2D площині, маючи масив координатних точок.
Вхід: [(1, 2), (1, 1), (3, 4)], 2
Вихід: [(1, 1), (1, 2)]

Виконання роботи:
Кожне завдання було реалізовано окремою функцією. Для перевірки правильності роботи функцій використовувалися тестові випадки.

print(task1([1, 2, 3])) # 14

print(task2([1, 2, 3, 4, 10])) # 14

print(task3([4, 6, 2, 6, 4, 4, 6])) # [4, 4, 4, 6, 6, 6, 2]

print(task4([1, 2, 4, 5])) # 3

print(task5([100, 4, 200, 1, 3, 2])) # 4

print(task6([1, 2, 3, 4, 5], 2)) # [4, 5, 1, 2, 3]

print(task7([1, 2, 3, 4])) # [24, 12, 8, 6]

print(task8([-2, 1, -3, 4, -1, 2, 1, -5, 4])) # 6

print(task9([[1, 2, 3], [4, 5, 6], [7, 8, 9]])) # [1, 2, 3, 6, 9, 8, 7, 4, 5]

print(task10([(1, 2), (1, 1), (3, 4)], 2)) # [(1, 1), (1, 2)]

Результати:
Отримані результати показують правильність реалізації функцій, зокрема:

Виконання обчислень сум квадратів, фільтрації та сумації елементів масиву.
Сортування масиву за частотою елементів.
Знаходження відсутнього числа та довжини найдовшої послідовності.
Обертання масиву та обчислення масиву добутків.
Знаходження максимальної суми підмасиву.
Повернення елементів матриці у спіральному порядку.
Знаходження найближчих точок до початку координат.
Висновки:
Мета роботи була досягнута. Було розглянуто та реалізовано різноманітні задачі з використанням методів роботи з масивами чисел у Python. Виниклі проблеми були вирішені за допомогою додаткових тестів і відладки коду.

Інструкції з запуску:
Вимоги до середовища: Python 3.x.
Необхідні бібліотеки: всі необхідні бібліотеки є стандартними для Python 3.x.