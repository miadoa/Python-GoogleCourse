# 大鱼AI🐟 ：Python-GoogleCourse

 Google for Education平台的Google Developer Python Course是基于python的一门经典课程。


### 1、课程概述

考虑到许多想学习机器学习或深度学习课程的同学还没有编程语言Python的基础，特意免费为大家提供了这门Python先导课程。该门课程专注于数据分析、机器学习、深度学习的Python基础，略去了网页和游戏开发等内容，方便学员快速入门人工智能。本们课程选用的素材乃是Google for Education平台的Google Developer Python Course经典课程，课程在学习基本知识的基础上，加入了大量的练习，帮助你更快的提升python技能。

&emsp;&emsp;  **学习人群定位**：python入门小白课程

&emsp; &emsp; **现有资料**: Google for Education平台Google Developer Python Course发布的视频，文档资料，国内Python教学经典资料

&emsp; &emsp; **就业方向**: python web开发，游戏开发，算法工程师，数据分析师等

### 2、 整体安排

#### 2.1 时间安排

 本课程需要1周，每天都会针对python基本知识进行学习。课程安排如下：

>

1. 【day 1】python环境搭建，解释器，基础知识
2. 【day 2】string, list, tuple
3. 【day 3】dict, set ，判断分支，循环，三目表达式
4. 【day 4】函数概念掌握
5. 【day 5】文件读写，os模块，datetime模块学习
6. 【day 6】类和对象
7. 【day 7】正则表达式，re模块，http请求

#### 2.2 学习大纲安排

课程资料及阅读材料：[Google Python](https://developers.google.cn/edu/python/) <br>
课程【视频链接】: [Google Python](https://www.bilibili.com/video/av27039298/) <br>
国内参考资料(1)：[廖雪峰Python教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000) <br>
国内参考资料(2)：[小甲鱼python基础视频](https://www.bilibili.com/video/av4050443/)

**【Day 1】**


1. 环境搭建<br>
   anaconda环境配置<br>

2. 解释器<br>

   熟悉解释器的概念，并了解CPython,IPython两种解释器<br>

3. jupyetr notebook<br>

   掌握基础操作<br>

4. python初体验<br>

   input() and print()<br>python变量特性+命名规则<br>
   学会使用dir()及和help( )<br>
   pep8基础掌握<br>

   1)  代码布局：重点掌握缩进，行最大长度，换行，import导入<br>2)  注释：块注释，行内注释，文档字符串<br>

5. python数值基本知识<br>
   python中数值类型，int，float，bool，e记法等<br>
   算数运算符<br>
   逻辑运算符<br>
   运算符优先级<br>


 【作业】

 学习代码分享，200-300行要求。

 要求用户依次输入姓名，性别，年龄，并对用户信息进行输出格式如下：您的姓名是：###，您的性别是：###，您是##年出生的。

------

**【Day 2】**


**基础**

1. string字符串<br>定义及基本操作（+，\*，读取方式）<br>
   字符串相关方法<br>字符串格式化问题<br>
2. list列表<br>
   标志<br>
   基本操作(创建，append( )，pop( ) ,del( ), 拷贝）<br>
   列表相关方法<br>
3. tuple元组<br>
   标志<br>
   基本操作（创建及不可变性）<br>

**提升**

1. 序列类型，序列类型间的相互转换及序列相关方法<br>
2. 成员运算符<br>
3. 身份运算符<br>

 【作业】

 学习代码200-300行‘

 定义一个列表，包含自己的家庭成员名字，定义完成后在你名字前加入“大鱼AI"，再将”大鱼AI”这一名字删除，此时判断“大鱼AI“是否在列表中。

[Google Python官方练习题string1 and list1](https://developers.google.com/edu/python/exercises/basic)

------

**【Day 3】**


1. dict字典<br>
   定义<br>
   创建<br>
   字典的方法<br>
2. set集合<br>
   特性<br>
   创建<br>
   方法<br>
3. 判断语句（要求掌握多条件判断）<br>
4. 三目表达式<br>
5. 循环语句<br>

 【作业】

学习代码200-300行

请对方输入一个0-9之间的数字，进行检查，若不是数字提示：您输入的不是数字，请输入0-9间的数字，若数字不在0-9范围内，提示用户输入0-9之间的数字，直至用户输入正确。

 系统随机生成一个长度为3的数字列表，且列表中元素在0-9之间并且不相等。将用户输入与该列表进行比较，若为列表第一个元素，则荣获第一名，列表第二个元素，则荣获第二名，列表第三个名字，则荣获第三名，否则提示用户未得奖，输入1重新开始游戏，输入2则结束游戏。

 注意：每次游戏中列表中数字要求随机生成，每轮游戏都不相等。

------

**【Day 4】**


1. 函数的定义<br>

2. 函数的调用<br>

3. 函数参数<br>

   3.1 普通参数<br>3.2 关键字参数<br>3.3 默认参数，定义了默认值的参数<br>3.4 可选参数<br>

4. 函数返回值<br>

5. 函数变量作用域<br>

6. 内嵌函数及闭包<br>

7. lambda表达式<br>

8. 两个重要的BIF : filter()和map()<br>

 【作业构想】

 实现random.sample方法<br>
 实现Max方法<br>
 实现判断两个字符串是否相等的方法<br>

------

**【Day 5】**

1. 文件的读写方式<br>
   打开文件方式（读写两种方式）<br>
   文件对象的操作方法<br>
   学习对excel及csv文件进行操作<br>
2. os模块<br>
3. datetime模块<br>

 【作业】

学习代码200-300行

请用户输入一个时间，输出选项所对应的现在时间，告诉用户这两个时间相隔的天数，小时数，分钟数和秒数。

 读取一个文件【文件将在之后给出】，将文件中转换为字典，key值为学习项目，value值为一个负责人列表，并判断字典中是否有负责人负责多个学习项目。


 [Google Python官方练习题wordcount](https://developers.google.com/edu/python/exercises/basic)

------

**【Day 6】**

1. 类和对象<br>

   1.1 self理解<br>1.2 \__init__方法理解<br>1.3 继承<br>1.4 公有和私有<br>

2. 了解异常捕获（try...except...)

 【作业】

 学习代码200-300行

定义一个父类people,包含姓名，年龄，eat()方法。定义两个子类，Chinese和American，均含有eat()方法。实例化子类对象，并实现调用父类的eat()方法。

------

**【Day 7】**

1. 正则表达式<br>
2. re模块<br>
3. http请求<br>

【作业】

学习代码200-300行

请用户输入电话及邮箱，并判断用户输入是否合法

 对http://www.baidu.com 进行请求，并用正则化匹配图片内容。将百度图标爬取下来保存至本地
