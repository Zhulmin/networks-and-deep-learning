# networks-and-deep-learning

###### 神经网络和深度学习笔记
   
   
sigmoid 用于修正W权重,  W`
```Python3
output' = W'x + b
output  = Wx + b
```

sigmoid 神经元对每个输入值有对应的权值w1,w2,w3... 偏移量b则是定值, 
但是定义为δ(Wx+b)时, δ为sigmoid函数, 貌似对W和b都作出调整

sigmoid神经元和感知机(线性)的函数:

![image](https://github.com/Zhulmin/networks-and-deep-learning/raw/master/images/c1f1.png)            ![image](https://github.com/Zhulmin/networks-and-deep-learning/raw/master/images/c1f2.png)

   
   
###### z = Wx + b
当z的值很大的时候, δ(z) = 1
当z的值很小的时候, δ(z) = 0
即 output = e^z 
δ函数其实可以表示为  
   
   
![image](https://github.com/Zhulmin/networks-and-deep-learning/raw/master/images/c1f0.png)
   
   
   
δ函数也称为 logistic function 
多层网络也称为多层感知机（multilayer perceptron，MLP)

输入神经元为输入值, 输出神经元为输入种类, 隐层神经元的个数是自定义的
