#### Задание:

##### Вариант: 14

###### Написать программу, которая читая последовательность чисел из файла, выводит на экран числа, состоящие из не более K цифр.

#### Таблица с результатами тестирования программы:

|            Вариант тестирования             |                   Результат тестирования                    |                    Результат на экране                     |
| :-----------------------------------------: | :---------------------------------------------------------: | :--------------------------------------------------------: |
|                  Файл есть                  |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
|                  Файла нет                  | Программа определяет, что файл по такому пути не существует |    Файл *.txt не обнаружен.<br />Время выполнения: ...     |
|                 Пустой файл                 |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
|                Средний файл                 |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
|                Большой файл                 |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
|        Путь к файлу задан корректно         |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
|       Путь к файлу задан не корректно       | Программа определяет, что файл по такому пути не существует |    Файл *.txt не обнаружен.<br />Время выполнения: ...     |
|         Параметр K задан корректно          |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
|        Параметр K задан не корректно        |       Программа определяет, что K задан не корректно        | Вы ввели некорректное значение.<br />Время выполнения: ... |
|  Текст содержит символы, отличные от цифр   |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |
| Текст не содержит символы, отличные от цифр |                Программа работает правильно                 | Результат работы программы: ...<br />Время выполнения: ... |

#### Время работы программы:

| Количество символов |  Время работы  |
| :-----------------: | :------------: |
|   10000 символов    | 0,0691 секунды |
|   50000 символов    | 0,074 секунды  |
|   100000 символов   | 0,102 секунды  |
|   200000 символов   | 0,179 секунды  |
|   500000 символов   |  0,33 секунды  |
|  1000000 символов   |  0,49 секунды  |

#### Вывод:

###### В ходе тестирования программы можно сделать вывод, что моя программа работает правильно при любых исходных данных, исправно обрабатывая различные исключения. Сложность данной программы линейная - O(n).