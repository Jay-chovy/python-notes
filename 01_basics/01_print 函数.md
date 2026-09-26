# 列表推导式

**一句话**：用一行表达式从可迭代对象生成新列表。

**代码**：
```python
squares = [x**2 for x in range(5) if x % 2 == 0]
print(squares)