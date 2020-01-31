### RNN (循环神经网络)
RNN是一种具有长时记忆能力的神经网络模型，被广泛用于序列标注问题。
序列标注问题中，模型的输入是一段时间序列，记为

$$ x={x_1,x_2,...,x_T} $$

我们的目标是为输入序列的每个元素打上标签集合中的对应标签，记为**y**={y_1,
y_2,...,y_T}。

### RNN结构图
- RNN结构图-抽象
    ![sigmoid](./pics/RNN-diagram.png)
- RNN结构图-具体
    ![sigmoid](./pics/RNN-diagram_2.png)
### 符号说明
![sigmoid](./pics/symbol.png)

## 附录
### 常用激活函数及其到导数
- sigmoid

    ![sigmoid](./pics/sigmoid.png)
- relu

    ![relu](./pics/relu.png)
- tanh

    ![tanh](./pics/tanh.png)

## 参考资料
- [1] [Recurrent Neural Networks Tutorial, Part 3 – Backpropagation Through Time and Vanishing Gradients
](http://www.wildml.com/2015/10/recurrent-neural-networks-tutorial-part-3-backpropagation-through-time-and-vanishing-gradients/)

