"所有的数学对象都有物理意义"个命题是否正确暂且不管, 但我们不需要对所有的数学对象都知道其物理意义, 这是一个学习上的窍门, 有的时候shut up and calculating才是更正确的学习方式. 知识是无穷尽的, 什么事情都要刨根问底会花很多时间, 在学习时间有限的情况下(这也是最常见的情况), 只需要弄清本专业的东西就行了; 对于数学对象来说, 只需要知道它们在本专业的意义. 弄不清楚的就直接当作工具, 不要深究, 以后有缘自会知道其意义的.

举个例子, 大二学习微积分时遇到了虚数\\(i\\), 那时只觉得它很神秘, 不明白其用处. 后来学习欧拉公式:
$$
e^{iθ} = \cos θ+i \sin θ
$$
知道\\(i\\)可以帮助计算三角函数, 总算有点理解, 但物理意义依然无法构成, 因为我从未在工作中遇到过三角函数, 也就不需要用\\(i\\)来辅助计算. 后来在DSP(Digital System Processing)中了解到信号可以被表达为一个关于时间的三角函数:
$$
x(t) = A \cos (\omega _0 t+φ)
$$
而三角函数的计算可以通过欧拉函数来转化成通用的代数计算, 我总算知道了\\(i\\)的作用: 将三角函数转换为指数函数, 在后者上我们已经有更多的结论, 因此处理起来更方便. \\(i\\)可以辅助画图, 在极坐标系和复平面表示信号. 

到这一步虽然还没有领会到直接意义, 但总算领会到一些间接意义了. 我把它当作一个方便的工具, 用于理解一些物理量以及简化计算. 我还不知道它的直接意义, 也许(很可能)\\(i\\)在别的领域有更清晰更符合直觉的物理定义, 但那不是现在的我该知道的.

同样的还有矩阵, 我一直搞不明白各种矩阵的作用, 正则矩阵, 合同矩阵, 逆矩阵... 有的出现在一些机器学习的公式证明中, 有的从未没遇到. 后来学习了图形学, 在一个投影操作的证明中用到了合同矩阵的性质, 突然觉得很兴奋, 这个东西总算有用了. 现在想来当初学习线性代数应该懒一些, 对一些复杂的数学对象和证明过程没必要死记硬背, 知道有这个东西, 后面在其他领域学习时触发关键字再回去查就行了.

请告诉我下面这个定义有什么"用":

Two square matrices **A** and **B** over a field are called **congruent** if there exists an invertible matrix **P** over the same field such that


$$
P^T AP = B
$$


我曾经花大量时间记忆这些东西, 因为我觉得它们是“知识”, 是"真理", 总会有意义的, "现在遇不到以后总会遇到吧", 结果就是浪费了许多时间, 而且由于一直遇不到应用, 最后也没有真的记住.

再举个例子, 关于科学研究, 我的理解是分为三步:

1. 将要研究的物理对象用数学对象A定义.
2. 将要实现的目标(某种状态, 某个系统)用数学对象B来定义.
3. 然后在数学领域内用A推导出B, 期间可能会用到一些数学对象C, 或许是辅助证明, 或许是方便计算. 过程中间也会产生一些数学对象. (BTW, 对于电气工程来说, 这些数学对象和计算过程都可以被实现为电路.)

**千万不要**想对象C的物理含义, 它们只是一些辅助的工具, 要么是一些中间结果. 例如对如下代码:

```c++
int a=1, b=3, c=5;
c = a + b;
```

编译器(我们假设在编译时计算)会先创建一个临时变量`tmp`作为`a+b`的中间结果, 再把`tmp`赋值给`c`, 我们能说`tmp`本身有什么**意义**吗?

这个例子有些牵强, 但我想表达的是: **不是所有的东西都有意义, 即使有, 它的意义也不一定大. 而只有足够大的意义才值得我们理解**. 

数学家可能不用关心这些, 数学对象本身就具有数学意义, 他们也不需要其具有物理意义和实用价值. 但对于其他领域的人, 无论是scientist还是engineer, 了解这一点会大大地加快学习效率以及减少不必要的困惑. 也许很多人早就知道这一点, 但我没有. 

我的数学学得和比白蚁蛀过的木头还烂. 直到今晚才明白随机变量和事件的区别. 这还得感谢我的信息论老师, 信息论是统计学的一个分支, 是概率论的进阶内容, 现在我发现自己连概率论都没弄清楚. 我做了一些笔记来讲这些事情.