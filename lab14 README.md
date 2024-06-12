Лабораторна робота №14: Boolean Expressions and Conditional Statements
Мета роботи:
Метою цієї лабораторної роботи є навчитися аналізувати булеві вирази та використовувати умовні оператори для розв'язання різних задач. 
Очікувані результати включають опанування основних операцій з булевими змінними, розуміння умовних операторів та застосування їх у різних контекстах.

Опис завдання:
1) Basic Boolean Operations: Написати функцію check_truth, яка приймає три булеві параметри (a, b, c) і повертає результат виразу (a and b) or c.
2) Logical Equivalence: Написати функцію logical_equivalence, яка приймає два булеві параметри і повертає True, якщо вони логічно еквівалентні, інакше False.
3) Exclusive Or (XOR): Написати функцію xor, яка приймає два булеві аргументи і повертає True, якщо тільки один з аргументів є True.
4) Conditional Greeting: Написати функцію greet, яка приймає булеве значення. Якщо значення True, функція повинна повернути "Hello, World!", інакше "Goodbye, World!".
5) Nested Conditions: Написати функцію nested_condition, яка приймає три цілі числа (x, y, z). Функція повинна повернути "All same", якщо всі три числа рівні, "All different", якщо всі вони різні, і "Neither" в інших випадках.
6) Conditional Counting: Написати функцію count_true, яка приймає список булевих значень і повертає кількість True в списку.
7) Boolean Parity: Написати функцію parity, яка приймає ціле число і повертає True, якщо кількість одиниць в його двійковому поданні парна, інакше False.
8) Majority Vote: Написати функцію majority_vote, яка приймає три булеві значення і повертає True, якщо більше половини з них є True, інакше False.
9) Boolean Switch: Написати функцію switch, яка приймає булеве значення і повертає його протилежність.
10) Ternary Operator Simulation: Написати функцію ternary_check, яка імітує тернарний оператор. Вона приймає три параметри: булеву умову, результат якщо умова True, і результат якщо умова False.
11) Validate Combination: Написати функцію validate, яка приймає три булеві значення (x, y, z) і повертає True, якщо x є True або якщо обидва y і z є True, інакше False.
12) Condition Chain: Написати функцію chain_check, яка приймає три цілі числа і повертає "Increasing", якщо вони строго зростають, "Decreasing", якщо строго спадають, або "Neither" в інших випадках.
13) Boolean Filter: Написати функцію filter_true, яка приймає список булевих значень і повертає новий список, що містить лише значення True.
14) Conditional Multiplexer: Написати функцію multiplexer, яка приймає чотири параметри: три булеві значення і одне ціле число. Якщо перше булеве значення є True, повернути подвоєне ціле число.
Якщо друге булеве значення є True, повернути потроєне ціле число. Якщо третє булеве значення є True, повернути ціле число мінус п'ять. Якщо жодне з булевих значень не є True, повернути ціле число без змін.


Приклади використання:
print(check_truth(True, False, True)) # True

print(logical_equivalence(True, True)) # True

print(logical_equivalence(True, False)) # False

print(xor(True, False)) # True

print(xor(True, True)) # False

print(greet(True)) # Hello, World!

print(greet(False)) # Goodbye, World!

print(nested_condition(3, 3, 3)) # Всі однакові

print(nested_condition(3, 4, 5)) # Всі різні

print(count_true([True, False, True, False, True])) # 3

print(parity(3)) # False (двійкове 11)

print(majority_vote(True, True, False)) # True

print(switch(True)) # False

print(ternary_check(True, "Так", "Ні")) # Так

print(validate(True, False, True)) # True

print(chain_check(1, 2, 3)) # Зростає

print(chain_check(3, 2, 1)) # Спадає

print(filter_true([True, False, True, False])) # [True, True]

print(multiplexer(False, False, True, 10)) # 5

Результати:
Отримані результати показують правильність реалізації функцій, зокрема:

Виконання базових булевих операцій.
Перевірка логічної еквівалентності.
Реалізація функції XOR.
Виконання умовних привітань.
Реалізація вкладених умов.
Підрахунок кількості значень True у списку.
Перевірка парності одиниць у двійковому поданні числа.
Визначення більшості голосів.
Перемикання булевого значення.
Імітація тернарного оператора.
Валідація комбінацій булевих значень.
Перевірка умовної послідовності.
Фільтрація булевих значень.
Реалізація умовного мультиплексора.

Висновки:
Мета роботи була досягнута. Було розглянуто та реалізовано різноманітні задачі з використанням булевих виразів та умовних операторів. 
Виниклі проблеми були вирішені за допомогою додаткових тестів і відладки коду.

Інструкції з запуску:
Вимоги до середовища: Python 3.x.
Необхідні бібліотеки: Всі необхідні бібліотеки є стандартними для Python 3.x.