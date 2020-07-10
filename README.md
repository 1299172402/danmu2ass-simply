# danmu2ass
弹幕转ass

简化了操作步骤

若文件夹结构如图
```
d:
--danmaku2ass.py
--danmaku2ass.exe
--\xml文件
  |--a.xml
  |--\xmlwenjian
     |123xml4.xml
```

在命令行中运行
```
python d:\danmaku2ass.py d:\xml文件
```
可将 d:\xml文件 的文件夹（包括子文件夹）下的所有xml文件转为ass并保存在各自的xml目录下

或者
```
python d:\danmaku2ass.py d:\xml文件\a.xml
```
则只转换这一个文件并保存在与xml同目录下

对于没有安装python的人提供了exe

https://zhiyuyu.lanzous.com/b099c16kd  
密码:5z1n

在命令行中运行
```
d:\danmaku2ass.exe d:\xml文件
d:\danmaku2ass.exe d:\xml文件\a.xml
```
可以与上文同样结果
