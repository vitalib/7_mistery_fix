# Решатель квадратных уравнений

Solves quadratic equation ax^2 + bx + c = 0 for non-complex decisions, returning roots as a tuple (root1, root2)

# Как использовать

FUNCTIONS
    get_roots(a, b, c)

    Arguments a, b, c - are coefficients of quadratic equation ax^2 + bx + c = 0. Returns tuple of roots -(root1, root2). In case descriminant equals to zero returns (root1, None), for negative discriminant returns (None, None).



EXAMPLE OF USAGE
    from quadratic_equation import get_roots
    roo1, root2 = get_roots(1, -2, 1)

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
