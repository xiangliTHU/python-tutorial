# 中文Python笔记

> 版本：0.0.1

> 笔记作者：李金

> 邮件地址：lijinwithyou@gmail.com

## 简介

大部分内容来自网络。

默认安装了`python 2.7`，以及相关的第三方包`ipython`， `numpy`， `scipy`，`pandas`。

> life is short. use python.

推荐使用[`anaconda`](http://www.continuum.io/downloads)，这个IDE集成了大部分常用的包。

笔记内容使用`ipython notebook`来展示。

安装好`python`和相应的包之后，可以在命令行下输入：

```
$ ipython notebook
```
来进入`ipython notebook`。

----

## 基本环境配置

- 安装 [`anaconda`](http://www.continuum.io/downloads)或者 [`miniconda`](http://conda.pydata.org/miniconda.html)

- 更新环境
``` 
conda update conda
conda update anaconda
(conda install anaconda) 
```

- 安装 `theano`， `GPU` 加速需要另外配置，这里不做介绍。
```
conda install mingw libpython
pip install theano
```


----

## 目录

可以在[nbviewer][1]中查看该项目。

- **[01.](01. python tools) `Python` 工具**
    - [01.01][2] Python 简介
    - [01.02][2] Ipython 解释器
    - [01.03][2] Ipython notebook
    - [01.04][2] 使用 Anaconda
- **[02.](02. python essentials) `Python` 基础**
    - [02.01][3] Python 入门演示
    - [02.02][3] Python 数据类型
    - [02.03][3] 数字
    - [02.04][3] 字符串
    - [02.05][3] 索引和分片
    - [02.06][3] 列表
    - [02.07][3] 可变和不可变类型
    - [02.08][3] 元组
    - [02.09][3] 列表与元组的速度比较
    - [02.10][3] 字典
    - [02.11][3] 集合
    - [02.12][3] 不可变集合
    - [02.13][3] Python 赋值机制
    - [02.14][3] 判断
    - [02.15][3] 循环
    - [02.16][3] 列表推导式
    - [02.17][3] 函数
    - [02.18][3] 模块和包
    - [02.19][3] 异常处理
    - [02.20][3] 警告
    - [02.21][3] 文件读写
- **[03.](03. numpy) `Numpy`**
    - [03.01][4] Numpy 简介
    - [03.02][4] Matplotlib 基础
    - [03.03][4] Numpy 数组
    - [03.04][4] 数组类型
    - [03.05][4] 数组方法
    - [03.06][4] 数组排序
    - [03.07][4] 数组形状
    - [03.08][4] 对角线
    - [03.09][4] 数组/字符串的转换
    - [03.10][4] 数组属性方法总结
    - [03.11][4] 生成数组的函数
    - [03.12][4] 矩阵
    - [03.13][4] 一般函数
    - [03.14][4] 向量化函数
    - [03.15][4] 二元操作符
    - [03.16][4] ufunc 对象
    - [03.17][4] choose 函数
    - [03.18][4] 数组广播机制
    - [03.19][4] 数组读写
    - [03.20][4] 结构化数组
    - [03.21][4] 记录数组
    - [03.22][4] 内存映射
    - [03.23][4] 从 MATLAB 到 Numpy
- **[04.](04. scipy) `Scipy`**
    - [04.01][5] 科学 Python 计算简介
    - [04.02][5] 使用 Scipy 进行插值
    - [04.03][5] 使用 Scipy 进行统计
    - [04.04][5] 使用 Scipy 进行拟合
- **[06.](06. matplotlib) `Matplotlib`**
    - [06.01][7] 使用 matplotlib.pyplot 进行简单绘图
    
[1]:http://nbviewer.ipython.org/github/lijin-THU/python-tutorial
[2]:http://nbviewer.ipython.org/github/lijin-THU/python-tutorial/blob/master/01.%20python%20tools/
[3]:http://nbviewer.ipython.org/github/lijin-THU/python-tutorial/blob/master/02.%20python%20essentials/
[4]:http://nbviewer.ipython.org/github/lijin-THU/python-tutorial/blob/master/03.%20numpy/
[5]:http://nbviewer.ipython.org/github/lijin-THU/python-tutorial/blob/master/04.%20scipy/
[7]:http://nbviewer.ipython.org/github/lijin-THU/python-tutorial/blob/master/05.%20matplotlib/