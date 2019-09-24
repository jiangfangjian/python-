# python-
学习python过程中的疑问和容易出错的点

## Python的优缺点
- 代码量少
- 易于上手
## Pycharm工具的使用
- 下载地址：http://www.jetbrains.com/pycharm/
- pycharm是编辑器，python是解释器、编译器
- package一般用来存放代码，而directory则可以用来存放一些静态文件，如资源、测试数据等
## 基本语法
## 字符串切片
- a='string' 字符串的索引是从0开始的，最后一位为-1，即a[0]='s' a[-1]='g'
- a[m:n:k],m为第一个索引值，n-1为最后一个索引值，k为步长；如a[0:3:2]='sr'
## 字符串格式化
- 第一种方式:d%f%s%,name='王萍',age=10,print(('s%的年龄是d%')%(name,age))
- 第二种方式：format,print('{}的年纪是{}'.format(name,age))
