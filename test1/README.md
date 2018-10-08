# 实验1 LCS算法的实现源码
LCS（Longest Common Subsequence）最长公共子序列，它是求两个字符串最长公共子序列的问题。

## 实验目的和要求
- 基于参考网站的算法，通过泛型实现任何对象的LCS。
- 编写代码实现下面的“老师源码的实验结果”。
- 训练解决复杂问题的设计能力。

## 知识点
- 泛型
- 运算符重载
- 二维数组
- 递归调用

## 运行结果

下载LCS目录，用VS2017打开LCS.sln，运行，即可看见下面的结果：

```java
类型System.Int32演示：
=========================================================
list1:
34  72  13  44  25  30  10
list2:
34  13  44  7  25

LCS结果:
  34
- 72
  13
  44
+ 7
  25
- 30
- 10

类型System.String演示：
=========================================================
list1:
abc  def  gh  zwd
list2:
abc  2  def  gh  zwd

LCS结果:
  abc
+ 2
  def
  gh
  zwd

类型LCS.Rectangle演示：
=========================================================
list1:
1.4m*2m=2800000mm2  1.4m*2m=2800000mm2  1m*2m=2000000mm2  1.4m*2m=2800000mm2
list2:
1.4m*2m=2800000mm2  140cm*200cm=2800000mm2  1.4m*2m=2800000mm2  1.4m*2m=2800000mm2

LCS结果:
+ 1.4m*2m=2800000mm2
  1.4m*2m=2800000mm2
  1.4m*2m=2800000mm2
- 1m*2m=2000000mm2
  1.4m*2m=2800000mm2

```