Проблема в том что характер переменных в коде целые числа. Если хотя бы одно из них было дробным расчет был бы верным.
Решения:
1. Задать для одной из переменных дробный характер, например: double chicken = 6; // куриных бёдер
2. Умножить переменную на 1.0, например: System.out.println((chicken*1.0 / eaters) + " куриных(ое) бёдер(ро)");