# NLP_LSTM
本项目基于pytorch，在不使用对应库中LSTM相关函数，手工构建单层&双层LSTM的语言模型，更深入的理解工作原理

## 相关原理
项目主要运用PyTorch中提供的LSTM模型相关公式，如下图所示：
![](https://github.com/Ethereal913/NLP_LSTM/blob/main/LSTM/公式.png)
没一个小的LSTM循环单元如图所示：
![](https://github.com/Ethereal913/NLP_LSTM/blob/main/LSTM/LSTM循环单元.png)
单层的LSTM模型结构图如图：
![](https://github.com/Ethereal913/NLP_LSTM/blob/main/LSTM/单层LSTM结构.png)
双层的LSTM模型结构图如图：
![](https://github.com/Ethereal913/NLP_LSTM/blob/main/LSTM/堆叠的LSTM.png)

## 运行环境
* Python 3.8.0
* PyCharm 2021.1.2
* PyTorch 1.9.0

## 文件分类
LSTM.py 是调用PyTorch中已经设置完成的相关函数，来完成的已经LSTM模型
LSTMLM.py 是不使用对应库中LSTM相关函数，对单层的LSTM模型进行手工构建
doubleLSTM.py 是不使用对应库中LSTM相关函数，对双层的LSTM模型进行手工构建

## 心得体会
通过自然语言处理这门课程，我学习到了有关自然语言处理的一些基础算法模型以及常用的深度学习方法，在NLP相关领域的知识上小有收获。并且本次实践课程之后，我从没有接触过Python到开始学习如何自己实现LSTM的核心算法内容，对RNN模型以及LSTM模型有了更加深刻的认识；同时通过这次实践，我还浅略地了解了GitHub上README写法，以及小部分GFM语法学习，同时也学到了许多深度学习的前沿知识，受益匪浅，收获颇丰。
