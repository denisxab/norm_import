# Как использовать

Импорт целого модуля

```python
from norm_import import iimport

ИмяМодуля = iimport(__file__, 1, 'ИмяМодуля').module
```

Импорт конкретных объектов из модуля

```python
from norm_import import iimport

Объект_1, Объект_2 = iimport(__file__, 1, 'ИмяМодуля').From('Объект_1', 'Объект_2')
```
