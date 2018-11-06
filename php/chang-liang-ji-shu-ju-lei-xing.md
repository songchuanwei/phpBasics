1，定义字符串三种方式

```
一，单引号
```

二，双引号

三，![](/assets/QQ截图20181105214754.png)

2，float  不能用于float比较  0.1+0.8=0.799999

3，bool  7种false     0，0.0，‘0’，‘ ’，array\(\)，NULL，false

4，超全局数组

```
$CLOBALS，$_GET ，$_POST， $_REQUEST ，$_SESSION ，$_COOKIE， $_SERVER， $_FILES， $_ENV
$_SERVER['SERVER_ADDR']  //服务器ip    $_SERVER['REMOTE_ADDR']  //客户端ip

$_SERVER['SERVER_NAME']  //服务器名称
```

5，定义常量 （常量一经定义，不能修改，不能删除）

    const   更快是语言结构  可定义类常量

    define 是函数

预定义常量

\_FILE\_   返回文件路径名，文件名

\_LINE\_   所在行号

\_DIR\_   所在目录

\_FUNCTION\_  所在函数体

\_CLASS\_  ，   \__TRAIT_\_  ，  \_METHOD\_  ，  \_NAMESPACE\_

