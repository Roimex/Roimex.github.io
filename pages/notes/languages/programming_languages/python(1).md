# Object

In Python, everything is an object. Each object belongs to a specific type, and each type has its own attributes and methods.

## Examples

| Types            | Objects      | Examples                              |
|---------------------|------------------|----------------------------------------|
| **Basic types**     | `int`, `float`, `bool`, `str`, `complex` | `42`, `3.14`, `True`, `"hello"`, `1+2j` |
| **Containers**      | `list`, `tuple`, `set`, `dict`, `range` | `[1,2]`, `(1,2)`, `{1,2}`, `{"a":1}`, `range(5)` |
| **Function**| `function`, `lambda`     | `def f(): ...`, `lambda x: x+1`        |
| **Structure objects**| `class`, `module`       | `class A: ...`, `import math`          |
| **Scientific objects** | `np.array`, `pd.Series`, `pd.DataFrame`, `sympy.Expr` | NumPy, pandas, SymPy data structures |

## Built-in Types

| Object Type | Attributes (Examples)       | Methods (Examples)                                      |
|-------------|------------------------------|----------------------------------------------------------|
| `int`       | `real`, `imag`               | `bit_length()`, `to_bytes()`                             |
| `float`     | `real`, `imag`               | `is_integer()`, `as_integer_ratio()`                     |
| `str`       | *N/A*                        | `lower()`, `upper()`, `find()`, `replace()`, `split()`   |
| `list`      | *N/A*                        | `append()`, `extend()`, `pop()`, `sort()`, `reverse()`   |
| `tuple`     | *N/A*                        | `count()`, `index()`                                     |
| `set`       | *N/A*                        | `add()`, `remove()`, `union()`, `intersection()`         |
| `dict`      | *N/A*                        | `get()`, `keys()`, `values()`, `items()`, `pop()`        |

---

## Scientific Objects

| Object Type      | Attributes (Examples)                   | Methods (Examples)                                      |
|------------------|------------------------------------------|----------------------------------------------------------|
| `np.array`       | `shape`, `dtype`, `size`, `ndim`         | `reshape()`, `flatten()`, `sum()`, `mean()`, `transpose()` |
| `pd.Series`      | `index`, `values`, `dtype`               | `head()`, `tail()`, `mean()`, `plot()`, `sort_values()`   |
| `pd.DataFrame`   | `columns`, `index`, `shape`, `dtypes`    | `head()`, `describe()`, `groupby()`, `drop()`, `merge()`  |
