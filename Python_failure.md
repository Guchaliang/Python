# Python_failure

- 异常捕获

  - ```
    try: 
    	语句1
    except 错误类型:
    	语句2
    except 错误类型:
    语句3
    ```

  - 为尝试执行语句1，如果没有问题则继续输出语句3

  - 有问题则输出语句2，语句3继续输出

  - 当python抛出异常时，那么第一个单词就是错误类型



- 捕获未知错误

  - ```
    try :
    	语句
    except 错误类型:
    	语句
    except Exception as result:
    	语句
    ```

  - 我们在设计时，不一定会预判到所有的错误，就需要应用这个

  - 加上最后一句即可



- 完全代码

  - ```
    try :
    	语句
    except 错误类型:
    	语句
    except Exception as result:
    	语句
    else:
    	没有异常时执行的代码
    finally:
    	无论有没有异常，都会执行
    ```

    ​

- 抛出异常

  - 异常类:Exception

  - 使用raise以抛出异常

  - ```
    ex = Exception(异常信息)
    raise ex
    ```

  - ​