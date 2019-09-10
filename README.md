# 使用Django框架搭建个人博客网站

-------
## 1.介绍Django框架的文件
-------
+ 当执行了**django-admin startproject mblog**创建了一个网站之后
+ **Django**为我们创建了一些文件夹和文件，了解这些文件很重要

### 1.1 manage.py文件
+ **manage.py**文件用来管理网站配置文件
+ 是一个可以接受命令行参数的**工具程序**

### 1.2 项目同名的文件夹
+ 存放该项目中最终重要的一些配置文件，包括**settings.py**、**urls.py**、**wsgi.py**
+ **wsgi.py**是和网页服务器沟通的接口，相关设置要等到网站上线才可以用到
+ **urls.py**用来设置每一个url网址要对应的函数以及对应的方式，通常是在要创建新的网页时，需要编辑的文件
+ **settings.py**是此网站的系统设计所在的位置，新创建的网站都要先打开这个文件，进行编辑设置操作。
