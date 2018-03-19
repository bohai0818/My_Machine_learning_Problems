## My_Machine_learning_Problems

1. **什么是极大似然估计？**

- 适用问题：parametric models or parametric distributions 

- 直觉理解：The idea for the maximum likelihood estimate is to find the value of the parameter(s) for
which the data has the highest probability.
  * Got data and distribution
  * draw the likelihood function 
  * maxmize the function to get the parameter(s) of the model 
  - Pay attention the discrete model and contineous model

- 数学理解：en.... To Be Continued



- 一些问题：
  - 什么是似然函数：是以模型参数为自变量的函数。


 

-参考文献：

- (**Very Impressive**)
https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/readings/MIT18_05S14_Reading10b.pdf



2. **欧几里得空间和希尔伯特空间的区别是什么？**

- 直觉理解：

- 数学理解：



3. **什么是判别模型和生成模型**

- 直觉理解：判别模型是指直接学学习`条件概率分布P(y|X)或者决策函数Y=f(X)`。这个条件概率分布或者决策函数直接给出了Y(也就是Label)的取值或者取值概率
所以命名为判别模型(*Discriminative Model*)。 常见的判别模型有`感知机,KNN,决策树,逻辑回归,SVM,提升方法，条件随机场`
生成模型(*Generative Model*)是指：模型`首先学习生成联合概率P(X,Y)然后求得条件概率分布P(Y|X)`。常见的生成模型主要有`朴素贝叶斯法，隐马尔科夫模型`

- 数学理解：

