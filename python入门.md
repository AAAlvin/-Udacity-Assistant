
> 本环节内容只针对小白同学，有基础的大神可以传送去项目讲解

## 01.安装python（选做）
- win上安装Anaconda
- Mac上安装Anaconda

>Python [官方版本](https://www.python.org/)
- 只有python标准库，使用第三方库的是需要使用pip或者conda在线安装，非常麻烦
- 编程效率较低，无自动提示，无法同时显示代码和运行结果  

>数据分析集成版本 [Anaconda](https://www.anaconda.com/download/)
- 集成了非常多的数据分析相关的python第三方库，直接调用即可；
- 多种编程环境可选，python2/3自由切换
- 可在[清华大学开源软件镜像站](https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/)下载


## 02. Markdown的基本语法
> 编写项目的文字部分需要用到Markdown这种标记语言  
**注意：** Markdown使用#、+、*等符号来标记， 符号后面必须跟上 至少1个 空格才有效！</u>

<font color=#DC143C	 > **备注：**本次只讲解项目中遇到的最简单的Markdown语言</font>

- ### 标题：用#标记

> # 我是一标
## 我是二标
### 我是三标
##### 这是四标

- ### 列表：-、+和*作为列表标记

> - Red
> * Green
> + Blue

- ### **强调：**两个*或-代表加粗，一个*或-代表斜体，~~代表删除

  
> **加粗文本** 或者 __加粗文本__

> *斜体文本*  或者_斜体文本_

> ~~删除文本~~

- ### **换行：**文本结束后添加两个空格换行  

> 文本结束后添加两个空格  
换行  

<font color=#708090	 >**注意：**以上只是项目中遇到的最简单的Markdown语言，如果想了解更多，请参考[官网](http://www.markdown.cn/)  </font>

## 03.Python的基础语法
> 以下语法只针对python3，python2运行可能会报错

- ### 重启代码空间需要从头执行
> 使用Anaconda需要特别注意，不管是优达的workspace还是本地环境，只要重新打开，就需要从头运行  


```python
apple = 111
```


```python
print(apple)
```

    111
    

> - 如果重启编程环境，而没有从头开始运行，就会报没有定义apple的错误！

- ### 行和缩进
> python 最具特色的就是用缩进来写模块，且缩进一定是四个空格，可以使用Tab来缩进内容，但是一定要注意控制一个Ta是四个空格b。


```python
if True:
    print ("True")#print前一定有四个空格才不会报错
else:
    print ("False")
```

    True
    

- ### Python 引号
> - Python 可以使用引号( ' )、双引号( " ) 来表示字符串，引号的开始与结束必须的相同类型的。  
> - 需要额外注意的是，python中语句部分中的所有标点都应该是**英文**的才能被识别。（当然不包括print需要输出引号内的中文部分的标点）


```python
print('word')
print("这是一个句子。")
```

    word
    这是一个句子。
    

- ### Python 注释
> python中单行注释采用 # 开头。




```python
# 下面我要打印一句话
print("Hello, Python!")  # 这就是打印的那句话
```

    Hello, Python!
    

> python 中多行注释使用三个单引号(''')或三个双引号(""")。


```python
'''
这是多行注释，使用单引号。
这是多行注释，使用单引号。
这是多行注释，使用单引号。
'''
print("常用于文档字符串，在文件的特定地点，被当做注释。")
```

    常用于文档字符串，在文件的特定地点，被当做注释。
    

## 资料大补充
- [廖雪峰的博客](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)  
- [编程小白学习Python](https://www.zhihu.com/pub/book/19550511)
- 数据库PostgreSQL的安装：[mac](http://postgresapp.com/ ) , [win](https://jingyan.baidu.com/article/11c17a2c2de638f447e39d10.html)
- [SQL交互式学习](https://sqlbolt.com/lesson/)
