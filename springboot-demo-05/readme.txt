同意异常处理
1. 在springboot实现了对异常的同意处理,
可以通过使用@ControllerAdvice定义统一的异常处理类,
而不是在每个Controller中逐个定义, @ExceptionHandler用来定义函数针对的异常类型.

2. 整个异常捕获的流程如下:
    2-1: 用户发起请求

    2-2: 程序出现异常, 程序自定义抛出异常

    2-3: 全局异常处理机制截获异常

    2-4: 先用户反馈程序运行信息


