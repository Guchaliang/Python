# Python的字符串

- 测量字符串的长度函数  **len** 

  - 使用时与 C语言 的 strlen 差不多

    ​


- 将字符串中的小写字母变为大写字母的为upper

  - ```python
    str = "hello world"
    print(str)
    print(str.upper())
    ```



- 将字符串中的大写字母变为小写字母的为lower

  - ```
    str = "hello world"
    print(str)
    print(str.lower())
    ```


- 将字符串中每个单词的首字母大写的为title

  - ```
    str = "hello world"
    print(str)
    print(str.title())
    ```


- 将字符串中的开头空格或者末尾空格删除的为strip

  - ```
    str = "   hello world"
    print(str)
    print(str.title())
    ```

  - 注意的是这个可以使用 lstrip 开头空格删除

  - rstrip 末尾空格删除


- 寻找字符串中的索引 find

  - ```
    str = "hello world"
    print(str)
    print(str.find("lo"))
    ```

  - 返回索引 3


- 替换字符串中的东西 replace 

  - ```
    str = "hello world"
    print(str)
    print(str.replace("o","a"))
    ```


- 接下来的python让我感觉有点像是用英语来编程