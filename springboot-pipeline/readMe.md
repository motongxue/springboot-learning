## 本示例主要演示如何利用管道模式来实现业务

实现核心步骤：

1、根据业务划分管道步骤
2、封装参数透传对象
3、封装管道抽象类
4、将每个管道步骤加入队列或者集合
5、利用递归或者循环队列或者集合，有序执行管道步骤