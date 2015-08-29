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

---

## 参考

- [Enthought Training on Demand](https://training.enthought.com/)
- [Computational Statistics in Python](http://people.duke.edu/~ccc14/sta-663/index.html#rd)
- [Scipy.org](http://scipy.org/)
- [Deep Learning Tutorials](http://deeplearning.net/tutorial/)
- [High Performance Scientific Computing](http://faculty.washington.edu/rjl/uwhpsc-coursera/index.html)

----

## 目录

可以在[nbviewer](http://nbviewer.ipython.org/github/lijin-THU/python-tutorial)中查看该项目。

- [01. **Python** 工具](01. python tools)
	 - [01.01 Python简介](01. python tools/01.01 python overview.ipynb)
	 - [01.02 Ipython 解释器](01. python tools/01.02 ipython interpreter.ipynb)
	 - [01.03 ipython notebook](01. python tools/01.03 ipython notebook.ipynb)
	 - [01.04 使用 Anaconda](01. python tools/01.04 use anaconda.ipynb)
- [02. **Python** 基础](02. python essentials)
	 - [02.01 Python 入门演示](02. python essentials/02.01 a tour of python.ipynb)
	 - [02.02 Python 数据类型](02. python essentials/02.02 python data types.ipynb)
	 - [02.03 数字](02. python essentials/02.03 numbers.ipynb)
	 - [02.04 字符串](02. python essentials/02.04 strings.ipynb)
	 - [02.05 索引和分片](02. python essentials/02.05 indexing and slicing.ipynb)
	 - [02.06 列表](02. python essentials/02.06 lists.ipynb)
	 - [02.07 可变和不可变类型](02. python essentials/02.07 mutable and immutable data types.ipynb)
	 - [02.08 元组](02. python essentials/02.08 tuples.ipynb)
	 - [02.09 列表与元组的速度比较](02. python essentials/02.09 speed comparison between list & tuple.ipynb)
	 - [02.10 字典](02. python essentials/02.10 dictionaries.ipynb)
	 - [02.11 集合](02. python essentials/02.11 sets.ipynb)
	 - [02.12 不可变集合](02. python essentials/02.12 frozen sets.ipynb)
	 - [02.13 Python 赋值机制](02. python essentials/02.13 how python assignment works.ipynb)
	 - [02.14 判断语句](02. python essentials/02.14 if statement.ipynb)
	 - [02.15 循环](02. python essentials/02.15 loops.ipynb)
	 - [02.16 列表推导式](02. python essentials/02.16 list comprehension.ipynb)
	 - [02.17 函数](02. python essentials/02.17 functions.ipynb)
	 - [02.18 模块和包](02. python essentials/02.18 modules and packages.ipynb)
	 - [02.19 异常](02. python essentials/02.19 exceptions.ipynb)
	 - [02.20 警告](02. python essentials/02.20 warnings.ipynb)
	 - [02.21 文件读写](02. python essentials/02.21 file IO.ipynb)
- [03. **Numpy**](03. numpy)
	 - [03.01 Numpy 简介](03. numpy/03.01 numpy overview.ipynb)
	 - [03.02 Matplotlib 基础](03. numpy/03.02 matplotlib basics.ipynb)
	 - [03.03 Numpy 数组](03. numpy/03.03 numpy arrays.ipynb)
	 - [03.04 数组类型](03. numpy/03.04 array types.ipynb)
	 - [03.05 数组方法](03. numpy/03.05 array calculation method.ipynb)
	 - [03.06 数组排序](03. numpy/03.06 sorting numpy arrays.ipynb)
	 - [03.07 数组形状](03. numpy/03.07 array shapes.ipynb)
	 - [03.08 对角线](03. numpy/03.08 diagonals.ipynb)
	 - [03.09 数组字符串的转换](03. numpy/03.09 data to & from string.ipynb)
	 - [03.10 数组属性方法总结](03. numpy/03.10 array attribute & method overview .ipynb)
	 - [03.11 生成数组的函数](03. numpy/03.11 array creation functions.ipynb)
	 - [03.12 矩阵](03. numpy/03.12 matrix object.ipynb)
	 - [03.13 一般函数](03. numpy/03.13 general functions.ipynb)
	 - [03.14 向量化函数](03. numpy/03.14 vectorizing functions.ipynb)
	 - [03.15 二元运算](03. numpy/03.15 binary operators.ipynb)
	 - [03.16 通用函数](03. numpy/03.16 universal functions.ipynb)
	 - [03.17 choose](03. numpy/03.17 choose.ipynb)
	 - [03.18 数组广播机制](03. numpy/03.18 array broadcasting.ipynb)
	 - [03.19 数组读写](03. numpy/03.19 reading and writing arrays.ipynb)
	 - [03.20 结构化数组](03. numpy/03.20 structured arrays.ipynb)
	 - [03.21 记录数组](03. numpy/03.21 record arrays.ipynb)
	 - [03.22 内存映射](03. numpy/03.22 memory maps.ipynb)
	 - [03.23 从 Matlab 到 Numpy](03. numpy/03.23 from matlab to numpy.ipynb)
- [04. **Scipy**](04. scipy)
	 - [04.01 SCIentific PYthon 简介](04. scipy/04.01 scienticfic python overview.ipynb)
	 - [04.02 使用 Scipy 进行插值](04. scipy/04.02 interpolation with scipy.ipynb)
	 - [04.03 使用 Scipy 进行统计](04. scipy/04.03 statistics with scipy.ipynb)
	 - [04.04 使用 Scipy 进行拟合](04. scipy/04.04 curve fitting.ipynb)
- [06. **Matplotlib**](06. matplotlib)
	 - [06.01 使用 matplotlib.pyplot 进行简单绘图](06. matplotlib/06.01 simple plot using matplotlib.pyplot.ipynb)