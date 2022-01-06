# Python 列表(数组)

### 1.数组

- 这个就相当于字符数组和数字数组的结合

  - 与C语言差不多

  - ```
    name_list = []即可
    ```

    ![数组](C:\Users\顾茶凉\Pictures\Saved Pictures\shuzu.png)

    ​

    - 注意sorted 与sort 的区别
      - sorted()是将这个排序后加入另一个列表





- 但是

  - ``` 
    str = "python"
    print(str[0:3])
    ```

  - 可以打印出 pyt



### 2.指针(类似)

- 可以通过 *＋变量名来定义一个指针

  - 这个指针可以看做是数组

  - 同时，定义函数的时候也可以使用

    ```
    def exp(*num)
    	函数内容

    exp(1,2,3,4)

    ```

    这样可以将所有的全部封装



- 所以也可以有

  - ```
    numbers = [1,2,3,4,5,6]
    first, second, *other = numbers
    ```



- 以及枚举
  - enumrate 其实和 C语言 差不多
  - ​