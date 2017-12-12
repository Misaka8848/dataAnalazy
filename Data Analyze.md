# Data Analyze

## Numpy
### ndarray：基本数据格式（矩阵）

#### 创建ndarray

```python
import numpy as np
# .array only accept 序列类型（list dic set）
np.array()
# 
np.zeros((x,y))
```

#### ndarray的attribute

```python
# 
ndarray.shape
# 
ndarray.dtype
```

#### ndarray数据类型

```python

```

#### 标量运算

`**`开根号

#### 索引&切片

```python
# 索引
# 和列表类似
In [5]: arr = np.arange(8)

In [6]: arr[1:3]
Out[6]: array([1, 2])

In [7]: arr[1:4]*2
Out[7]: array([2, 4, 6])

In [8]: arr
Out[8]: array([0, 1, 2, 3, 4, 5, 6, 7])

In [9]: arr[1:4] = 4
```

