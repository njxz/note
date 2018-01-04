# Boosting

http://www.cnblogs.com/LeftNotEasy/archive/2011/01/02/machine-learning-boosting-and-gradient-boosting.html

通过Ensemble　learning overview，我们可以得出boosting的概念图如下

![img](https://images2015.cnblogs.com/blog/1042406/201612/1042406-20161204194331365-2142863547.png)

​    Boosting这其实思想相当的简单，大概是，对一份数据，建立M个模型（比如分类），一般这种模型比较简单，称为弱分类器(weak learner)每次分类都将上一次分错的数据权重提高一点再进行分类，这样最终得到的分类器在测试数据与训练数据上都可以得到比较好的成绩![image](https://images.cnblogs.com/cnblogs_com/LeftNotEasy/201101/201101022146263350.png)

