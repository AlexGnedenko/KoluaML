Разложение факториала
Инструкция:
Цель этого задания разложить n! (факториал n) на простые множители.

Примеры:

n = 12; decomp(12) -> "2^10 * 3^5 * 5^2 * 7 * 11"

n = 22; decomp(22) -> "2^19 * 3^9 * 5^4 * 7^3 * 11^2 * 13 * 17 * 19"

n = 25; decomp(25) -> 2^22 * 3^10 * 5^6 * 7^3 * 11^2 * 13 * 17 * 19 * 23

Простые числа должны быть в порядке возрастания. Когда показатель простого числа равен 1, не ставьте показатель степени.

Заметки:

Функция decomp(n) должна возвращать разложение n! на простые множители в порядке возрастания простых чисел, как строка. Факториал может быть очень большим числом (4000! имеет 12674 цифры, n будет от 300 до 4000). Выходная строка не должна содержать лишних побелов в конце.