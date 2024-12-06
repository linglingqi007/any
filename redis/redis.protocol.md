# RESP

一个字符串的协议，标记了类型，数据长度信息。

1. strings
2. integers
3. arrays
4. errors

数据类型依赖首个字节。

1. 单行字符串，首字节为`*+*`