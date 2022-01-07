# Python的语句

- **if**  语句

  - ```python
    number = 35
    if number > 30：
    	print("this is a big number")
    print("done")
    ```

  - ```c
    int number = 35;
    if(number > 30 ){
    	printf("this is a big number");
    }
    ```

  - python 是以缩进作为if语句的范围的



- **elif** 语句
  - 这个其实与 C语言 中的 **else if** 一样
  - 除了用法和上面的相同是没有变化的
  - 同时还有 **else**



崩溃瞬间：

```
age = 22
message = "eligible" if age >= 18 else "No eligible"
print (message)
```



- 内置函数range
  - 用于生成一个整数序列
  - 创建range对象的三种方式
  - range(stop)创建一个[0,stop)之间的整数序列,步长为1
  - 创建range对象的三种方式range(start,stop)创建一个[start,stop)之间的整数序列，步长为1
  - range(start,stop,step)创建一个[start,stop)之间的整数序列,步长为step



- 循环语句 while
  - 和C语言差不多
  - 还是缩进



- 循环语句 for _ (若没有变量可以使用_来替代) in＋可迭代对象(类似于range函数或者说字符串)

