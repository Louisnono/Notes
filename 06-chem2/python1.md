```python
a = input()
```

输入

print 打印

```python
print(a)
```

输出

变量类型：

| 整型                     | 浮点型           | 字符串           | boolean                 |
| ------------------------ | ---------------- | ---------------- | ----------------------- |
| int                      | float            | string           | boolean                 |
| 整数                     | 小数             | 字符串           | true/false              |
| int(a) 把a转换成整数输出 | float() 输出小数 | str() 输出字符串 | bool() 输出布尔类型变量 |

运算

四则运算 整除//和除法/的区别

```python
a = input()
b = 'input is ' + a + ' ending'
print(b)
```

基本的逻辑语句

```python
if a > 1:
    print(str(a)+' >1')
elif a == 1:
    print(str(a)+' =1')
else:
    print(str(a)+' <1')
```

判断



```python
while a > 1 :
    a = a - 1
    print(a)
```



循环1



```python
a = int(input())
for i in range(a):
    print(i)
```

i 从 0 到a-1

循环2



如果想终止循环：

```python
break
```

break一次只会终止一个循环



进阶变量：

列表 list

```python
a = [1,2,6,8,3] #创建列表
print(a[1])

```

负数索引 从后往前数



## 切片

```python
a = [1,2,6,8,3] #创建列表
b = a[1:3]
print(b)
```

包含起点不包含终点。

```python
a = [1,2,6,8,3] #创建列表
a.append(256)
print(a)
```

for循环遍历数组元素

```python
a = [1,2,6,8,3] #创建列表
a.append(256)
for i in a:
    print(i)
```



导入外部函数库的语法

```python
import numpy as np
```



因子查询器

```python
import numpy as np
# 输出所有的因数
a = int(input())
answers = []
for i in range(a):
    if (a//(i+1))*(i+1) == a:
        answers.append(i+1)
print('All the factors as follows: ' + str(answers))

```



pip install pandas