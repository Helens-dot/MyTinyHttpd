<h3 align="center">一款可运行的HTTP服务器</h3>



### 1、简介

按照 【2、编译】中的步骤还是可以顺利运行的，可以自行尝试~


### 2、编译

请严格按照下面步骤进行编译

#### 1、编译准备工作

文件夹中的 post.html 以及 post.cgi 文件需要一定的权限才可以执行。

所以需要先进行权限给予。

第一步、克隆项目并给予足够权限，打开命令行依次输入下述命令：

~~~c
git clone  https://github.com/Hexiangkun/MyTinyHttpd.git

cd  httpdocs

sudo chmod 600 test.html

sudo chmod 600 post.html

sudo chmod +X post.cgi
~~~


#### 2、编译执行

依次输入下述命令即可。

~~~c
cd  ../

make

./myhttp
~~~

#### 3、整体过程图


1、项目默认端口号是6379，默认显示的界面是是test.html界面。

2、运行成功后默认显示的为test.html界面，同时同一路径下还有 post.html界面，可以将地址栏的“**test.html**”改成“**post.html**”来进行查看。



