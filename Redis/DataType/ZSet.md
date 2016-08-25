ZSet (Sorted set) 有序集合
***
- 说明：
    zset集合与set集合不同的是每个元素都会关联一个double类型的分数。

- 命令：

    > zdd [key] [score] [member] *(score为自定义数据，需要传入)*
    > zrangebyscore [key] [range]