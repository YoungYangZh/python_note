# **Python**

**python** 变量

不能用数字开始，不能包含空格，使用snake\_case

## 全局变量

在函数外部创建的变量称为全局变量。

每个人都可以使用全局变量，无论是在函数内部还是外部。

**python** 数据类型

python自带的数据类型：

| 文本类型 | str |
| --- | --- |
| 数字类型 | int，float，complex |
| 序列类型 | list，tuple，range |
| 映射类型 | dict |
| 集合类型 | set，frozenset |
| 布尔类型 | bool |
| 二进制类型 | bytes，bytearray，memoryview |
| 无类型 | none |

**python** 字符串

字符串

python字符串是用引号包着。

多行字符串

"""字符串内容

字符串内容"""

字符串是数组

像其他语言一样，python中的字符串是表示unicode字符的字节数。

方括号可以被用于访问字符串的元素

字符串长度

len（字符串名）

## 切割字符

## 修改字符串

所有的字符串函数返回一个新值，不会改变原字符串。

大写 **.upper** （）

小写 **.lower** （）

去除前后空格 **.strip** （）

替代字符串 **.replace** （）

字符串名.replace（'想替代的字'，'替代成什么字'）

拆分字符串 **split** （）

该方法返回一个列表，其中指定分隔符之间的文本称为列表项。

字符串名.split（'分隔符'）

## count（）

字符串.count（值，起点，终点）

值：必须有，一个字符串，要搜索的值的字符串

起点：可选。一个整数。默认值是0

终点：可选。一个整数。

## Isdigit（）

字符串.isdigit（）

如果所有字符都是数字，isdigit（）方法返回True，否则返回False

指数也被认为是数字。

## 字符串的级联

用加号

## 字符串格式

我们不能把字符串和数字用加号连接，只有通过Format（）函数才可实现。

Format（）方法接受传递的参数，格式化它们，并将它们放在占位符{}所在的字符串中。

format（）方法接受无限个参数，并把它们放到分别的位置里。

你可以使用{索引号}来确保参数放到正确的位置。

你可以在大括号里说明你要怎样转化值。

| ：f | 确定小数点后几位格式 |
| --- | --- |
|
 |
 |
|
 |
 |
|
 |
 |
|
 |
 |

## 转义字符

在字符串里的引号不被允许，可以使用转义字符\来解决

'字符串\'字符串\'字符串'

| \n | 换行 |
| --- | --- |
|
 |
 |
|
 |
 |
|
 |
 |
|
 |
 |

##

**python** 语言的类型

## 数字类型

1、整数类型int()

2、浮点数类型float()

3、复杂类型complex()数字和字母混合

数字类型的关系

三种类型存在一种逐渐扩展关系：

整数\>浮点数\>复数（三种类型可以相互转换

示例：

Int（4.5）=4

数字类型的关系

## 字符串类型str()

字符串的操作

《string》.upper()

\<string\>.lower()

## 元祖类型

元祖是包含多个元素的类型，元素之间用逗号

元祖有三个特点

（1）元祖中的元素可以是不同类型

（2）元祖中各元素存在先后关系

（3）元祖定义后不能更改，也不能删除

4.列表类型

列表的概念

列表与元祖类似

列表与元祖不同

列表的操作

math库与random库

math库

| 函数 | 数学表示 |
 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

random库

| **函数** |
 |
 |
| --- | --- | --- |
|
 |
 |
 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

列表

列表用于存储多个值在一个变量中。列表在方括号中。不能改变顺序。可变。允许重复。

**tuples**

元祖用来存储多个项目在单个变量中。放在括号里。

元祖是python中用于存储数据集合的四种内置数据类型之一。其他三个是list、set和dictionary。

元祖是有序且不可更改的集合。

元祖项

元祖项是有序的、不可更改的，并且允许重复值。

元祖项是被索引的，第一项是【0】，第二项是【1】等。

有序的

当我们说元祖是有序的，这意味着这些项目被定义了顺序，并且顺序不可改变。

不可改变的

这意味着元祖被创建后，我们不能改变、增加或者删除项目

允许重复

由于元祖被索引，它们的项目可以具有相同的值

元祖长度

查看元祖长度，可使用len（）函数

创建有一个项目的元祖

你需要加一个逗号在项目后，否则python不认为它是一个元祖，而是一个字符串

元祖项目 **-** 数据类型

元祖项目可以是任意数据类型，一个元祖可以包含不同数据类型

**Tuple** （）构造函数

Tuple（（元祖））

**python** 集合（数组）

python语言有四种集合数据类型：

List：有序且可变的，允许重复。

元祖：有序但不可变，允许重复。

Set：无序、不可变（可以删除和增加）、不可索引，不可重复。

字典：有序且可变，不可重复。

## 访问元祖项

## 更新元祖项

你可以把元祖转成list，改变list，然后再转成元祖。

增加项目

## 解压元祖

当我们建立一个元祖，我们通常会分配值给元祖，这被称为打包元祖。在python，我们允许将值提取回变量，称之为解压。

注意：变量的数量必须和元祖值的数量相等，如果不等，你必须使用星号将剩余的值收集为列表。

使用星号

如果变量的数量比值的数量少，你可以增加一个星号到变量名称，值将以列表的形式分配给变量。

如果星号被加给另一个变量名而不是最后一个，python将分配值给变量，直到剩下的值的个数与剩下的变量个数相匹配。

## 循环变量

你可以通过for来循环所有元值值

通过索引号来循环

使用range（）和len（）函数来创建一个合适的可迭代对象。

## 连接元祖

使用加号

元祖相乘

## 元祖方法

python有两个元祖内置函数

| count（） | 返回指定值在元祖中出现的次数 |
| --- | --- |
| index（） | 搜索元祖中某个特定值并返回该值的位置 |

字典

字典用于存储数据值在键对值中。字典是有序、可变但不允许重复的集合。

字典写在大括号中，并且拥有键和值。

## 字典项目

字典项目是有序、可变但不允许重复的。

字典项目表现为键对值，并且可以通过键名进行引用。

重复值会被现有值代替。

## 字典长度

为了决定一个字典拥有多少个项目，使用len（）函数

## Dict（）

## 嵌套字典

**if…elif…else**

if 条件：

缩进：python需要缩进（一行最前面是空格）来定义代码范围。其他语言经常使用大括号来定义范围。

If经常与and、or、pass一起使用

通用循环构造方法

## while循环

while循环需要准备好相关变量

while循环像一个重复的if语句。只要条件为真，代码会不停重复。

**Continue**

通过continue我们可以停止现有的循环，回到循环最开始。

**Else**

## for循环

for 索引变量in 整体：

for循环不需要预先设置索引变量

for循环用于迭代序列（即列表、元祖、字典、集合或字符串）

**Break**

**Continue**

**Range** （）

range（30）不是从0到30，而是从0到29.

来循环一组代码指定的次数，我们可以使用range（）函数。

Range（）函数返回一序列默认从0开始数字，默认增加1，结束于指定数字

如果不想从0开始，可以通过增加参数来指定开始值range（2，30），表示从2到30但是不包括30.

也可以每次不增加1，而是增加指定值：range（2，30，3），表示每次增加3个。

**Else**

else不能和break同时使用

**Enumerate** （迭代对象， **start=0** ）

如果你还想访问索引信息，那么你可以在迭代的列表元素所在的位置上使用enumerate（）。

返回一个枚举对象。iterable必须是序列、迭代器或其他支持迭代的对象。

## list循环

字典循环

你需要items（）函数来进行字典循环：

For key，value in 字典名.items（）：

循环体

**Numpy** 数组循环

在一维numpy里循环：

for 变量in 数组名：

在二维numpy里循环：

For 变量in np.nditer（数组名）：

**pandas** 数据框循环

for 名1，名2 in 数据框名.iterrows（）：

类对象 **class** 和对象 **object**

类就像一个对象制造机或者是创建对象的蓝图。

**1** 、定义类

class 类名：

**2** 、建立对象

对象名=类名（想继承的类）

**3** 、 **\_init\_** （）初始化功能

def \_init\_（self，参数1：类型，参数2：类型，等）：

self.参数1=名称1

self.参数2=名称2

等

用于给对象分配值，是创建一个类对象后一定要使用的方法。

self表示对象本身，谁调用就表示谁。

参数有几个，后面的实例就有几个

## 3、其他功能：\_str\_（）功能

该函数控制当类对象表示为字符串时，应返回的内容。如果未设置该函数，则返回对象的字符串的表现形式

def \_str\_（self）：

Return f'{self.参数1}{self.参数2}等）'

**self** 参数

self参数是对类当前实例的引用，用于访问属于该类的变量。它的名字不一定是self，你可以起任何名字，但是它是类功能里第一个参数。

## 4、创建实例（绑定属性参数）

实例1=类名（实例参数1，实例参数2等）

实例2=类名（实例参数21，实例参数22等）

等

删除对象属性

Del 对象名.属性名

删除对象

Del 对象名

添加属性

给一个类添加属性

Self.属性=值

## 5、传参

## 6、调用

**python** 模块

## 模块定义

模块可以被认为是代码图书馆。是一个你想要添加给应用程序的含有一系列函数的文件

## 创造模块

存储你想要的代码到一个带有.py文件扩展名的文件

## 使用模块

Import 模块名

模块名.函数名

## 模块里的变量

模块除了函数，还可以包括所有类型的变量

## 重命名模块

Import 模块名as 重命名

## 自带模块

## Dir（）函数

这是一个内置函数，可列出一个模块内所有的函数名（或者变量名）

## 从模块里引进

使用from关键字可以选择只引进模块的一部分

From 模块名import 部分名

注意：使用from关键字引进时，在引用模块中的元素时不要使用模块名。

**python** 继承

母类是我们想要继承的类，也被称为基础类

子类是我们从母类继承的类，也被称为派生类

## 创建一个母类

任意一个类可以当作母类，创建过程和创建类一样

## 创建一个子类

要创建一个从另一个类继承其功能的类，请在创建子类时将母类作为参数。

class 子类名（母类名）

## 增加\_init\_（）功能

如果你增加了该功能，子类不再继承母类的\_init\_（）功能

## 使用super（）功能

可以使子类继承所有的功能从母类

通过使用super（）功能，你不需要使用母类的名字，它会自动继承方法。

## 添加属性

布尔表达式

布尔代数

任何数据和true操作都是真

德摩根定律

布尔代数的应用

布尔表达式作为决策

回顾交互式循环，只要用户相应一个y

对于数字（整型和浮点型）德零值被认为是false，

运算符

## 算术运算符

## 赋值运算符

## 比较运算符

## 逻辑运算符

and

or

not

## 身份运算符

is

Is not

## 会员运算符

in

Not in

函数

函数：完成特定功能的一个语句组，通过调用函数名来完成语句组的功能。你可以根据需要添加任意数量的参数，只需要逗号分隔它们即可。

创建一个函数

使用def语句

def 函数名称(参数):

函数体

## 函数的调用和返回值

调用一个函数

函数名称（）

参数

参数在函数名称后的括号内指定

参数数量

调用函数必须使用正确数量的参数。这意味着如果你的函数需要两个参数，则你必须使用2个参数调用该函数，不能多也不能少。

任意参数 **\*args**

如果你不知道有多少参数将传给你的函数，请在函数定义中的参数名称前添加一个\*，这样函数将接收一个参数元祖，并可以相应地访问项目。

关键字参数 **kwargs**

还可以使用key=value语法发送参数，这样，参数的顺序无关紧要。

任意关键字参数 **\*\*kwargs**

如果你不知道有多少关键字参数传递给函数，加\*\*在函数定义的参数名称前

默认参数值

def 函数名（参数1='值1'）

函数体

函数（）

函数（'值2'）

将列表作为参数传递

可以发送任意数据类型的参数给函数（字符，数字，列表，字典等），在函数内还是相同的数据类型。

返回值 **return**

return语句：结束函数调用，并将结果返回

无返回值的return语句等价于return None

**pass** 声明

函数定义不能为空，但是如果一定要空，可以使用pass声明来避免错误

递归

pathon也接受函数递归，这意味着定义的函数可以调用自身。

嵌套函数

**Nonlocal**

用于处理嵌套函数内的变量，该变量不应属于内部函数

**Try except**

try：

代码块

except：

代码块

Except：

代码块

等

try块让你可以测试代码是否有错误。

except块让你处理错误

else块让你在没有错误时执行代码。

finally块让你执行代码，不管try和except块的结果。

异常处理

当一个错误产生，或者我们称之为异常，python通常会停止并产生一个错误信息。

这些异常可以用try来处理

由于try块引发错误，except块将被执行。

**else**

你可以使用else关键字来定义一块代码来执行，如果try没有错误被指出

**Finally**

如果指定了finally块，无论try块是否引发错误，finally块都会被执行。这个非常有用，当你需要关闭对象和清理资源。

引发异常

Raise（）

**Lambda**

这是一个匿名的功能。

Lambda 参数：表达式

lambda函数可以接受任意数量的参数，但只能有一个表达式。

**map(**函数，顺序**)**

map() 函数为可迭代对象中的每个项目执行指定的函数。该项目作为参数发送到函数。

**Filter(**函数，序列**)**

filter() 函数返回一个经过函数过滤后的序列。

**Reduce(**函数，序列**)**

reduce() 函数接受一个函数和一个序列，并返回一个计算如下的单个值：

1、使用序列中的前两项调用该函数并返回结果。

2、使用在步骤1 中获得的结果和序列中的下一个值再次调用该函数。这个过程不断重复，直到序列中有项目为止。

用户输入 **input** （）

**Python** 图书馆

**Matplotlib**

## Pyplot

大多数matplotlib实用程序位于pyplot子模块下，通常导入为plt

Import matplotlib.pyplot as plt

## 绘图

绘制 **x** 和 **y** 点

Plot（）函数采用参数来指定途中的点

参数1=np.array（【坐标1，坐标3】）

参数2=np.array（【坐标2，坐标4】）

plt.Plot（参数1，参数2）

Plt.show（）

参数1是一个含有x轴点的数组。参数2是一个含有y轴点的数组。

无线绘图

要仅绘制标记，你可以使用快捷字符串符号参数o，意思是环。

plt.Plot（参数1，参数2，'o'）

Plt.show（）

默认 **x** 点

如果我们没有指定点在x轴，它会得到默认值0、1、2、3等（取决于y点的长度）。

## 标记

你可以使用关键字参数marker来强调有指定标记的每个点

Plt.plot（参数，marker='样式'）

## Matpjlotlib标签和标题

给点图创立标签

Plt.Xlabel（"x轴标签名"）和plt.ylabel（"y轴标签名"）

给点图创立标题

Plt.Title（"标题名"）

通过Fontdict参数给标题和标签设置字体属性

标题的位置

在title（）函数里使用Loc参数来确定标题位置。

有三种位置可选："left"，"right"，"center"。默认值是"center"

## 散点图

Matplotlib模块有一个方法来画散点图，它需要两个同样长度的数组，一个给x轴，一个给y轴。

Plt.SCATTER(参数1，参数2)

颜色

使用color或者c参数设置每个散点图的颜色。使用c来设置每个点的颜色。

尺寸

使用s参数来设置点的大小。

**alpha**

使用alpha参数来设置点的透明度

## Subplot

Plt.subplot（图位于几行，图位于几列，第几个图）

使用该函数，你可以在一个图中绘制多个图

## 柱状图plt.hist（对象）

柱状图显示频率的分布，显示每个给定间隔内的观察次数。

# 机器学习

## 标准偏差np.std（值的名）

标准偏差是一个数字，描述了值的分布情况。

标准偏差低表示大部分的数字接近于平均值。

标准偏差高表示值的分布很广。

数据分布

## 如何得到大数据集

可以使用python的Numpy模块，里面有一系列函数可以创建任意大小随机数据集。

## 柱状图

## 大数据分布

# **Python MySQL**

## 建立数据库

## Join

合并两个或多个表格

**left join**

from 文件名1 left join 文件名2 on 区域

**python** 文件处理

Open（）功能有两个参数：文件名和模式。

打开一个文件有四种模式：

r：读，默认值，如果文件不存在返回错误。

A：附录，打开一个文件进行追加，如果文件不存在则创建该文件。

W：写，打开一个文件来写，如果文件不存在则创建该文件。

x：创建，创建一个特别文档，如果文件已存在返回错误。

此外，你可以指定文件是否应作为二进制或文本模式处理

t：文本，默认值

b：二进制模式（比如图像）

open（'文件名'，模式）

如果是rt，可以省略，因为是默认值

**python** 自带函数

**python** 表单函数

## Pop（）删除指定位置的元素

表单名.pop（位置）

位置是可选的。是一个表示位置的数字，默认值为-1，表示删除最后一个。

## append（）函数

表单名.append（'元素名'）

**pythong** 关键词

## Global

global 变量

global关键字用于从非全局范围创建全局变量，例如在一个函数里面。

## Raise

raise 错误类型（'给用户的提醒'）

raise关键字用于指出异常。你可以定义什么类型的错误被指出，和给用户的文本是什么。

## Assert

调试代码时使用assert关键词。尝试如果if返回true，如果返回false，assertionError被指出

# **Pandas**

**Series** 系列

一个pandas Series相当于表格中的一列。它是一个可以包含任意数据类型的一维数组。

通过对象创建 **series**

pd.series(对象)

返回的series值都有自己的索引号

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **index** | 数组 | 创建标签（索引值），可以通过index指定包含在series里的项目 |
| --- | --- | --- |

数据框

Pd.dataframe()

一个pandas数据框是一个二维的数据结构，像一个二维数组，或者一个拥有行和列的表格。

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **ascending** | True，False | 默认true。按升序分类 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

字典到数据框

数据框是pandas最重要的数据结构。它基本上是一种存储表格数据的方法，你可以在其中标记行和列。

构建数据框的方式之一是从字典中获取。

## CSV到数据框read

把数据放到一个字典里然后建立数据框可行，但是没有有效。

大多数文件都是放在csv文件里，csv是用逗号隔开的值的缩写。

要将csv数据作为pandas数据框导入到python，你可以使用read\_csv（）

Pd.read\_csv("文件名.csv")

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **index\_col** | 整数、字符串、false | 默认为none。作为数据框标签的列。如果为false，可以强制pandas不使用第一列作为标签 |
| --- | --- | --- |
| **parse\_dates** | 布尔或列表 | 【1，2，3】表示第一二三列 |
|
 |
 |
 |
|
 |
 |
 |

## 方括号

1、用于选择列

你可以以多种形式索引并选择pandas数据框，最简单的就是使用方括号。

单方括号版本提供pandas series，双括号版本提供pandas数据框。如果在一个数据框里选择多列，必须用双方括号

2、用于选择行或对象

数据框名【数字1:数字2】

## 定位行loc和iloc

Pandas使用loc来返回一行或者多行。

loc是基于标签的，这意味着你必须根据行和列标签指定行和列。

iloc是基于整数索引的，所以你需要通过整数索引指定行和列。

数据框 **.LOC** 【】

得到某索引值相对应的值。

定位某值

数据框.loc【'行标签'，'列名'】

访问多行

数据框.loc【【'行标签1'，'行标签2'】】

访问多列

数据框.loc【【'行标签1'，'行标签2'】】，【【列1，列2】】

选择区域

数据框.loc【'行标签1'：'行标签2'】

注意：行标签1和行标签2都包括在结果中。

数据框 **.iloc**

iloc属性获取或设置指定索引的值。

定位某值

数据框.iloc【行，列】

访问多行

数据框.iloc【【行1，行2，等】】

访问多列

数据框.iloc【【行1，行2】，【列1，列2】】

要访问部分行和部分列

数据框.iloc【行1：行2，列1：列2】

使用from和to指定数据框的一部分

数据框.iloc【行1：行2】

## 比较运算符

当两个字符串进行比较时，python根据字母顺序确定大小。

## 布尔运算符and，or，not

布尔值为0或1，true或false。

not等级比and和or高，会先执行。

布尔运算符和 **Numpy**

为了和Numpy使用这些运算符，我们需要np.logical\_and（）、np.logical\_or（）、np.logical\_not（）

**Iterrows** （）

每次运行时Iterrows（）产生的行数是pandas系列。

增加行

方法一

For lab,row in 数据框名.iterrows（）：

数据框名.loc[lab,增加行名]=增加行的内容

方法二

Apply（）

数据框名["增加行名"]=数据框名["列名"].apply（增加行的内容）

**Merge()**

数据框1.merge（数据框2，可选参数）

| 参数 | **值** | **描述** |
| --- | --- | --- |
| **how** | left','right','outer','inner','cross' | 默认是'inner'。指定如何合并 |
| --- | --- | --- |
| **on** | 字符串列表 | 指定在哪个区域进行合并 |
| **left\_on** | 字符串列表 | 指定在哪个级别对左侧的数据框进行合并。 |
| **suffixes** | 列表 | 指定要为重叠列添加的字符串列表。 |
| **left\_index** | True，False | 默认false。是否使用左边数据框的索引作为共同索引 |
| **indicator** | True，False，字符串 | 默认false。是否增加带有每列资源的一列 |
| **validate** | 字符串 | 检查合并是否为指定类型 |

merge()函数通过合并两个数据框的内容来做一个新的数据框

（）查询数据框

数据框名.query（条件必须有）

Query（）方法允许你查询数据框。返回一个新数据框或者None。

**isnull** （）找空值

数据框名.isnull（）

**count** （）

计算非空值的行数，返回带有计算结果的series

数据框名.count（axis，level，numeric\_only）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **axis** | 0，1，'index'，'columns' | 可选的，默认值是0 |
| --- | --- | --- |
| **leve** | 数字，level名 | 可选 |
| **numeric\_only** | True','False' | 可选的，默认值是false |

**sum** （）

**Agg** （）

数据框名.agg（函数）

Agg（）允许你应用一个函数或函数list沿着数据框的一个轴执行。默认值是0，也就是按行执行。如果是numpy里的函数，记得在函数前加np点。

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **函数** |
 | 必须的。 |
| --- | --- | --- |
| **axis** | 0，1，'index'，'columns' | 可选的，哪个轴来执行函数。默认0 |
| **args** |
 | 可选的，发送给函数的参数 |
| **kwarg** |
 | 可选的，发送给函数的关键字参数 |

**sort\_values** （）

数据框.sort\_values（by=条件）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **ascending** | True，False | 默认true。按升序分类 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

数据框 **.sort\_index** （）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **ascending** | True，False或True和False的列表 | 默认true。按升序分类 |
| --- | --- | --- |
| **Level** | 字符串、数字、字符串和数字的列表 | 指定要排序的索引级别 |
|
 |
 |
 |
|
 |
 |
 |

**isin** （）

数据框.isin（值）

查看数据框是否含有某个特定值。返回一个类似于原数据框的数据框，但是原始数据已经被true或false代替。

值可以是列表、字典、series和数据框。

**groupby** （）

数据框名.groupby（【标签】）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **as\_index** | True，False | 默认为true。设置为false如果结果不是用组标签作为索引。 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**concat** （）

竖着串联多个表。

pd.concat（【表1，表2，等】，参数）

ignore\_index=True参数表示不是用原表的索引

**append** （）添加数据框

现有数据框.append（添加数据框）

把一个类数据框对象添加到现有数据框后面。

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **sort** | true，false | 默认false。如果是true，分类列 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**merge\_ordered** （）

pd.merge\_ordered（数据框1，数据框2）

用于合并两个之间存在完全匹配的，并且有有序数据的表，

fill\_method参数'ffill'表示向前填充

**Merge\_asof** （）

pd.merge\_asof（数据框1，数据框2）

类似于merge\_odered（）左合并。根据最近的关键列来合并，而且不完全合并。

用于合并有序数据，但是表格之间不需要完全匹配。

on=的列名必须是已分类的。

**Pivot** （）

Pivot（）函数用于重塑一个给定的由索引/列值组织的数据框。无法聚合。

数据框.pivot（columns=''）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **index** | 字符串或对象 | 用于创建新框架索引的列。如果没有，则使用现有索引 |
| --- | --- | --- |
| **values** | 字符串、对象或表单 | 用于填充新框架值的列。如果未指定，则使用所有剩余的结果有分层索引的列 |
| **margins** | 布尔 | 增加一行/列 |

**pivot\_table(**数据**)**可以聚合

| 参数 | 值 | 描述 |
| --- | --- | --- |
| aggfunc | 函数，函数列表，字典 | 默认mean |
| values | 要聚合的列 |
 |
| Index | 列，组 |
 |
| columns | 列，组，数组，列表 | 列表 |
| fill\_value | 标量 | 默认值为None |
| margins | bool | 默认False。增加一行或列。 |
|
 |
 |
 |

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **directions** | forward'，'nearest'，'backward' | 向前搜索选择右侧数据框的第一行向后搜索选择右侧数据框中的最后一行 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

Melt（）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **id\_vars** | 元祖、列表、数组 | 指定要用做标识符的一列或多列，保持原样的列 |
| --- | --- | --- |
| **value\_vars**
 | 元祖、列表、数组 | 指定要逆透视的列 |
| **var\_name** | 字符串 | 指定variable列的标签，默认variable |
|
 |
 |
 |

**pd.to\_datetime()**

把一个类标量类数组series或者数据框转化成pandas日期时间格式。

| **参数** | **值** | **描述** |
| --- | --- | --- |
|
 |
 |
 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**Dropna()**

dropna() 方法删除包含NULL 值的行。

**Value\_counts** （）

数据框.value\_counts（）

该函数用于获取包含唯一独特值计数的series

结果对象是降序的，那么第一个元素会是最频繁发生的元素（包括空值）

列名可以放在数据框名后面，则对该列进行计数。

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **normalize** | 布尔 | 如果为真对象返回每个不一样值的出现频率 |
| --- | --- | --- |
| **Sort** | 布尔 | 按频率陪列 |
| **ascending** | 布尔 | 按升排列，默认是降序（多的在前面） |
| **dropna** | 布尔 | 不包括空值 |
| **bins** | 整数 | IR而不是计数值，将它们分组到半开箱中，这是pd.cut的便利，仅适用于数字数据。 |

**index** （）

返回数据框的索引信息，包括行标签。如果行没有名字标签，返回系列索引对象（start，stop和step values）。

数据框**.Set\_index(**'索引值'**)**

让一列或多列的值成为行索引。

数据框 **.Sample** （）

返回一个特定数的随机列。

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **数字** |
 | 返回几列。默认值是一列 |
| --- | --- | --- |
| **replace** | 布尔 | 默认false。是否要重复返回统一列 |

数据框 **. reset\_index** （ **'** 列名 **'** ）

把索引值从新设回到默认的0、1、2等。

该函数默认将老索引存储在一列名为'index'的列，为了避免，可以使用drop参数。

| Drop | True，False | 默认false |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

数据框 **.Cumsum** （）

返回一个数据框，其中包含每一行的累计和。

| **参数** | **值** | **描述** |
| --- | --- | --- |
|
 |
 |
 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

数据框 **.Astype** （数据类型）

返回一个新的数据框，它所有列的数据类型都被设为某个或某些特定类型.

你可以把整个数据框设为同一类型，或者你可以使用字典功能来给每列设定类型。

调取帮助

Help（np.函数名）

数据框 **.mode** （）

返回每列的模式值。模式值是一组中最常出现的值，可以是多个值。并且会带上索引值。

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **Axis** | 0,1,索引，列名 | 默认0 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**Quantile** （）

计算给定轴中值的分位数。

数据框 **.Drop\_duplicates** （）

从数据框里去除重复行

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **Subset** | 列标签 | 包含找重复值的列的字符串或者列表。没有该项则应用于所有行。 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**any()**

any() 方法为每一列返回一个值，如果该列中的任何值是True，则为True，否则为False。

数据框 **.Sample** （）

返回一个随机行里的随机数，如果没有指定则返回随机行

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **N** |
 | 返回几行，默认为1 |
| --- | --- | --- |
| **replace** | TrueFalse | 默认False。 |
|
 |
 |
 |
|
 |
 |
 |

清洁数据

清洁错误数据

相关性

## 寻找关系

df.corr（）

Corr（）计算每列之间的关系，会忽略非数字值

## 解释结果

corr（）的结果是一个有很多数字的表格

数字是在-1到1之间

1表示这是一个1对1的关系（完美相关）。每次一列的值增加，另外一列也会增加。

-0.9表示相关性很大，但是是负相关。

0.2几乎没有相关性。至少要0.6才能算有相关性。

画图

数据框.Plot（）

**Plt.legend()**

在轴上放置图例

1. 自动检测要在图例中显示的元素
2. 在图例中明确列出艺术家和标签

Plt.legend（【标签1，标签2】）

1. 明确列出传说中的艺术家
2. 标记现有绘图元素

| 参数 | 值 | 描述 |
| --- | --- | --- |
| handles | 艺术家序列 | 要添加到图例的艺术家（线条、补丁）列表。 |
| labels | 字符串列表 | 显示在艺术家旁边的标签列表。 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

## 散点图

使用kind='scatter'参数

散点图需要x轴和y轴：x=""，y=""

## 柱状图

数据框【'列名'】.plot（kind='hist'）

柱状图只需要一列。

# **Numpy**

**Numpy** 规则

Numpy用于数组

Numpy具有线性代数、傅里叶变换和在矩阵领域工作的功能。

为什么要使用 **Numpy** ？

在Python中，我们有用于数组用途的列表，但它们的处理速度很慢。Numpy快50倍。

**Numpy** 使用什么语言？

部分用Python，但是大多数需要更快算法的部分使用c或c++

数组

数组的形状是每个维度中元素的数量

Numpy里的数组被称为ndarray。

从列表创建数组**np.array(**列表名）

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **dtype** | 数据类型 |
 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

## 数组的维度

1、向量数组vector arrays：一维数组

2、矩阵数组matrix arrays：二维数组

3、张量数组tensor arrays：三维数组

数组属性

得到数组的形状 **.shape**

数组名.shape

返回一个元祖，有几个数字就有几维，每个数字表示该维度包含元素的个数

**Np.array** （） **.dtype** 得到数组里数据的类型和大小

数组函数

数组名 **.flatten** （）

展平数组，把数组变成一维。

数组名 **.reshape** （）

如果是二维，参数为（行数，列数）

如果是高维，参数为（维度，行数，列数）

**np.zeros** （（行数，列数））得到一个只有 **0** 的数组

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **dtype** | 数据类型 | 默认float64 |
| --- | --- | --- |
|
 |
 |
 |

**Np.mean** （数组名）

改变数组类型

数组名.as（'新类型'）

或使用python字典来定义每一列

**Sort**

Np.sort（数组名）

这个函数返回一个数组的拷贝，不会改变原数组。

**Np.where(**条件**,x,y)**

返回ndarray

如果只有条件，则该函数等同于np.asarray（条件）.nonzero（）

| 参数 | 值 | 描述 |
| --- | --- | --- |
| 条件 | 类数组，布尔 | 如果是真进入x，如果是假进入y |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

**Np.delete(**要删除的数组，要删除的对象，轴**)**

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **要删除的数组** | 类数组 |
 |
| --- | --- | --- |
| **被删除的子数组** | 切片、整数或整数数组 | 指示要沿指定轴删除的子数组的索引 |
| **轴** | 整数 | 删除子数组的轴。如果axis=None，相当于从展平数组删除。axis=0表示按行操作，axis=1表示按列操作。axis=2相当于3d的立体轴 |

##

## 数组连接

**Np.concatenate((**数组 **1** ，数组**2)**，参数**)**

**Np.stack** （（数组 **1** ，数组 **2** ））

stack和concatenate几乎一样，唯一的区别是stack使用一个新轴来连接。

**np.split** （数组名，分几份）

Axis

随机

Numpy里有一个random包

**Np.random.seed** （参数）

设置随机种子，以便你的结果在模拟之间可重现。作为参数，它需要你选择的整数。如果你调用该函数，不会产生任何输出。

**Np.random.rand** （）

如果你不指定任何参数，它会生成一个介于0和1之间的随机浮点数。

**Np.random.randint** （起始数，结束数）

产生一个随机整数。结束数是不包括的。

**np.Random.random** （）

产生一个在半开放区间【）里的随机小数

对象名 **.Sample** （顺序， **k** ）

随机产生一个含有k个项目的列表

**np.** 用于获取给定区间内均匀分布的值。

结束值不包括在区间里。

返回ndarray（结束值）返回一个规定区间内的整数数组

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **start** |
 | 该值包括在数组中，默认值为0 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

## 正态分布

Numpy.random.normal（）

它有三个参数：

Loc-（平均）峰值

Scale-（正态分布）图分布应该有多平坦

Size-返回数组的形状

Mean deviation平均偏差

standard deviation标准偏差

标准正态分布

标准正态分布是平均值为0标准差为1的正态分布。

**z** 值

z值表示一个值与均值的标准差有多少。

寻找 **z** 值的 **p** 值

比z值小的可能性：正态分布累积概率密度函数

norm.cdf（数字，均值，标准差）

百分比点函数（cdf的逆函数—百分位数）

norm.ppf（数字，均值，标准差）

## 二项分布random.binomial(n=尝试的次数，p=每次尝试的发生概率，size=返回数组的形状）

二项分布是一种离散分布，它描述了二进制场景的结果。

离散分布：分布是在独立的事件上定义的。

正态分布和二项分布的区别

主要区别是正态分布是持续的，二项分布是离散的。但是如果数据量足够大，它将非常类似于具有特定位置和规模的正态分布。

二项式离散随机变量

scipy.stats.binom.rvs（试验次数，实验成功的概率，size=返回数组的形状）

概率质量函数

scipy.stats.binom.pmf（头数，试验次数，试验成功的概率）

累积分布函数

scipy.stats.binom.cdf（头数，试验次数，试验成功的概率）

## 泊松分布random.poisson(lam=平均发生次数，size=返回数组的形状）

泊松分布是一种离散分布，用来估计一件事情在某一时间段发生的次数。事件发生有一定的概率，但是是完全随机的。

lam是lambda的缩写，用来描述泊松分布的形状。Lambda是分布的顶峰。

正态分布和泊松分布的区别

正态分布是连续的，泊松分布是离散的。

但是我们可以看到，就像二项分布一样，对于足够大的泊松分布，它会变得类似于具有特定标准差和均值的正态分布。

二项分布和泊松分布的区别

二项分布只有两种可能的结果，而泊松分布有无限可能的结果。但是足够大的n和接近于0的p，二项分布与泊松分布几乎相同，也就是nxp几乎等于lam

## 均匀分布uniform distribution

又分为离散均匀分布和持续均匀分布

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **size** | 数组 | 返回数组的形状 |
| --- | --- | --- |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

数据框 **.sum** （【数组 **1** ，数组 **2** 】）

把每列相加并返回列的和

| **参数** | **值** | **描述** |
| --- | --- | --- |
| **axis** | 0、1，'index'，'columns' | axis=0表示把每列的所有行相加（列总和）（默认）axis=1表示把每行的所有列相加（行总和） |
| --- | --- | --- |
| keepdims | 布尔 | 如果将其设为true，则纵向排列 |
|
 |
 |
 |
|
 |
 |
 |

p.vectorize(python功能)

用于把非数组函数转化为数组函数。

向量化方法需要将对象类型放在方法名称之前。

| 参数 | 值 | 描述 |
| --- | --- | --- |
| Doc= | str | 函数的文档字符串 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

Broadcast广播

广播是numpy对不同形状的数组进行数值计算的方式。

当运算中两个数组的形状不同时，numpy将自动触发广播机制。

广播的规则：

-Numpy是从右向左比较数组。

-二维数组可兼容当：一方长度为1或长度相同

如果两组数据都

数据框**.mean()**

| 参数 | 值 | 描述 |
| --- | --- | --- |
| Axis | 0、1、'index'、'columns' | 默认为算展平数组的平均数 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |
|
 |
 |
 |

## 数组转换

下载 **npy** 文件

With open('名.npy','rb') as 缩写：

新文件名=np.load（缩写）

保存数组为 **.npy** 文件

With open('名.npy','wb') as 缩写：

np.save（缩写，数组名）

Np.flip（数组）

用于沿给定轴翻转数组中元素的顺序。

默认参数Axis=None，则翻转所有轴。axis=0沿x轴翻转，axis=3则翻转rgb值。axis为一个元祖时，则翻转元祖中涉及的轴。

np.transpose（数组）

用来置换一个数组的维度（行变列，列变行）

参数axes默认情况下反转维度，否则根据给定值排列轴。

# 统计方法

# **Django**

# 创造虚拟空间

虚拟空间

每个django项目最好单独建立一个虚拟环境。我们可以使用python自带的venv来管理虚拟空间。

Py -m venv 虚拟环境名

**scipy**

scipy是一个科学计算库，它基于Numpy。

scipy提供我们一个模块，叫scipy.stats，它有执行统计显着性检验的功能。

# **Sqlite3**

把数据库和 **sqlite3** 连接

连接名=Sqlite3.connect（'数据库名'）

创建指标

指标名=连接名.cursor（）

执行操作

指标名.execute（sql命令）

返回所有结果行

指标名.fetchall（）

提交事务

指标名.commit（）

关闭现有连接

指标名.close（）

# **FastAPI**

POST创造

GET读取

PUT更新

DELETE

# **SciPy**

SciPy（Scientific Python）是一个基于Numpy的科学计算图书馆。它为优化、统计和信号处理提供了更多实用功能。

## SciPy统计显著性检验scipy.stats

在统计学中，统计显著性意味着产生的结果背后是有原因的，他不是随机产生的，也不是偶然产生的。

**P** 值

P值表示数据实际接近极端的程度。

比较P值和阿尔法值以确定统计显著性。

如果p值《=阿尔法值，我们拒绝零假设并说数据具有统计显著性，否则我们接受原假设。

**Stats.poisson** 的方法

Pmf概率质量函数