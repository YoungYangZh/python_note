# **SciPy**

SciPy（Scientific Python）是一个基于Numpy的科学计算图书馆。它为优化、统计和信号处理提供了更多实用功能。

## SciPy统计显著性检验scipy.stats

在统计学中，统计显著性意味着产生的结果背后是有原因的，他不是随机产生的，也不是偶然产生的。

**P** 值

P值表示数据实际接近极端的程度。

比较P值和阿尔法值以确定统计显著性。

如果p值《=阿尔法值，我们拒绝零假设并说数据具有统计显著性，否则我们接受原假设。

**Stats.poisson** 的方法

Pmf概率质量函数：求某数发生的概率
stats.poisson.pmf(某数，平均数）
cdf累积分布函数：求发生某数以下的概率
stats.poisson.cdf(某数，平均数）

**Stats.expon** 的方法
cdf累积分布函数：求发生某数以下的概率
expon.cdf(某数，scale=平均值）

**Stats.t** 的方法
找到比某t值小的概率
t.cdf（某t值，自由度）

t.ppt（自由度）
