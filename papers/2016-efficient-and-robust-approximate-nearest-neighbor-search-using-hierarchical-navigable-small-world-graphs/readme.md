论文本身内容不多，在[知乎上这篇文章](https://zhuanlan.zhihu.com/p/133526632) 中总结得比较好了。


每次插入节点时，随机取一个该节点的最高层 l，然后把这个节点加到不高于 l 的每一层。


文章中提到可以复用跳表来实现。


看算法会用到较多的集合操作，不适于张量运算。听说因为 recall 高这方法在推荐系统中用得多（取代了 LSH），不知道具体怎么实现的。
