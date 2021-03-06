# Решатель квадратных уравнений
Решает квадртное уравнение вида ax^2 + bx + c = 0.

# Как использовать
Скрипт содержит одну функцию get_roots(a, b, c), в которой аргументы a, b, c являются соответствующими 
коэффициенатами квадратного уровнения. Функция возвращает кортеж, состоящий из 2-х корней уравнения.

Пример использования
```python
from quadratic_equation import get_roots
roo1, root2 = get_roots(1, -2, 1)
```

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
