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

- **`Python` 工具**
    - [01.01](01. python tools) Python 简介
    - [01.02](01. python tools) Ipython 解释器
    - [01.03](01. python tools) Ipython notebook
    - [01.04](01. python tools) 使用 Anaconda
- **`Python` 基础**
    - [02.01](02. python essentials) Python 入门演示
    - [02.02](02. python essentials) Python 数据类型
    - [02.03](02. python essentials) 数字
    - [02.04](02. python essentials) 字符串
    - [02.05](02. python essentials) 索引和分片
    - [02.06](02. python essentials) 列表
    - [02.07](02. python essentials) 可变和不可变类型
    - [02.08](02. python essentials) 元组
    - [02.09](02. python essentials) 列表与元组的速度比较
    - [02.10](02. python essentials) 字典
    - [02.11](02. python essentials) 集合
    - [02.12](02. python essentials) 不可变集合
    - [02.13](02. python essentials) Python 赋值机制
    - [02.14](02. python essentials) 判断
    - [02.15](02. python essentials) 循环
    - [02.16](02. python essentials) 列表推导式
    - [02.17](02. python essentials) 函数
    - [02.18](02. python essentials) 模块和包
    - [02.19](02. python essentials) 异常处理
    - [02.20](02. python essentials) 警告
    - [02.21](02. python essentials) 文件读写
- **`Numpy`**
    - [03.01](03. numpy) Numpy 简介
    - [03.02](03. numpy) Matplotlib 基础
    - [03.03](03. numpy) Numpy 数组
    - [03.04](03. numpy) 数组类型
    - [03.05](03. numpy) 数组方法
    - [03.06](03. numpy) 数组排序
    - [03.07](03. numpy) 数组形状
    - [03.08](03. numpy) 对角线
    - [03.09](03. numpy) 数组/字符串的转换
    - [03.10](03. numpy) 数组属性方法总结
    - [03.11](03. numpy) 生成数组的函数
    - [03.12](03. numpy) 矩阵
    - [03.13](03. numpy) 一般函数
    - [03.14](03. numpy) 向量化函数
    - [03.15](03. numpy) 二元操作符
    - [03.16](03. numpy) ufunc 对象
    - [03.17](03. numpy) choose 函数
    - [03.18](03. numpy) 数组广播机制
    - [03.19](03. numpy) 数组读写
    - [03.20](03. numpy) 结构化数组
    - [03.21](03. numpy) 记录数组
    - [03.22](03. numpy) 内存映射
    - [03.23](03. numpy) Numpy vs Matlab
- **`Scipy`**
    - [04.01](04. scipy) 科学 Python 计算简介
    - [04.02](04. scipy) 使用 Scipy 进行插值
    - [04.03](04. scipy) 使用 Scipy 进行统计
    - [04.04](04. scipy) 使用 Scipy 进行拟合
- **`Matplotlib`**
    - [06.01](06. matplotlib) 使用 matplotlib.pyplot 进行简单绘图