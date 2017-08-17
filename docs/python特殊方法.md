## python 特殊方法

通过特殊方法的实现，自定义数据类型可以表现得跟内置类型一样，从而写出更python的代码。

- 跟运算符无关的特殊方法

|类别|方法名|
|---|-----|
|字符串/字节序列| \_\_repr\_\_, \_\_str\_\_, \_\_format\_\_, \_\_bytes\_\_|
|数值转换| \_\_abs\_\_, \_\_bool\_\_, \_\_complex\_\_, \_\_int\_\_, \_\_float\_\_, \_\_hash\_\_, \_\_index\_\_|
|集合模拟| \_\_len\_\_, \_\_getitem\_\_, \_\_setitem\_\_, \_\_delitem\_\_, \_\_contains\_\_|
|迭代枚举| \_\_iter\_\_, \_\_reversed\_\_, \_\_next\_\_|
|可调用模拟| \_\_call\_\_|
|上下文管理| \_\_enter\_\_, \_\_exit\_\_|
|实例的创建和销毁| \_\_new\_\_, \_\_init\_\_, \_\_del\_\_|
|属性管理| \_\_getattr\_\_, \_\_getattribute\_\_, \_\_setattr\_\_, \_\_delattr\_\_, \_\_dir\_\_|
|属性描述符| \_\_get\_\_, \_\_set\_\_, \_\_delete\_\_|
|跟类相关的服务| \_\_prepare\_\_, \_\_instancecheck\_\_, \_\_subclasscheck\_\_|

- 跟运算符相关的代码

|类别|方法名|
|---|-----|
|一元运算符| \_\_neg\_\_ -, \_\_pos\_\_ +, \_\_abs\_\_ abs()|
|众多比较运算符| \_\_lt\_\_ <, \_\_le\_\_ <=, \_\_eq\_\_ ==, \_\_ne\_\_ !=, \_\_gt\_\_ >, \_\_ge\_\_ >=|
|算术运算符| \_\_add\_\_ +, \_\_sub\_\_ -, \_\_mul\_\_ *, \_\_truediv\_\_ /, \_\_floordiv\_\_ //, \_\_mod\_\_ %, \_\_divmod\_\_ divmod(), \_\_pow\_\_ ** or pow(), \_\_round\_\_ round()|
|反向算术运算符| \_\_radd\_\_, \_\_rsub\_\_, \_\_rmul\_\_, \_\_rtruediv\_\_, \_\_rfloordiv\_\_, \_\_rmod\_\_, \_\_rdivmod\_\_, \_\_rpow\_\_|
|增量赋值算术运算符| \_\_iadd\_\_, \_\_isub\_\_, \_\_imul\_\_, \_\_itruediv\_\_, \_\_ifloordiv\_\_, \_\_imod\_\_, \_\_ipow\_\_|
|位运算符| \_\_invert\_\_ ~, \_\_lshift\_\_ <<, \_\_rshift\_\_ >>, \_\_and\_\_ &, \_\_or\_\_ |, \_\_xor\_\_ ^|
|反向位运算符| \_\_rlshift\_\_, \_\_rrshift\_\_, \_\_rand\_\_, \_\_rxor\_\_, \_\_ror\_\_|
|增量赋值位运算符| \_\_ilshift\_\_, \_\_irshift\_\_, \_\_iand\_\_, \_\_ixor\_\_, \_\_ior\_\_|
