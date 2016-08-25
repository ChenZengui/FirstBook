Set 集合类型
***
- 说明：
    set集合为无序集合，通过哈希表实现

- 命令：

    > sadd [key] [member] *(将成员member 插入的集合key中，成功返回1，已存在返回0，失败返回错误)*

    >smembers [key]     *(读取集合)*