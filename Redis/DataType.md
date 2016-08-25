# Redis安装

***

## 安装

1. 安装 Ubuntu 系统
    > 略
2. 下载安装包    
   > wget http://download.redis.io/releases/redis-3.0.6.tar.gz

   等待下载完成。
3. 解压
    > tar xzf redis-3.0.6.tar.gz

    > 完成后

    > cd redis-3.0.6
4. 编译
    > make  (未安装make时，需apt-get install make)
    
    如果失败，则可能是有些依赖包需要安装，如gcc。
    安装完相应的依赖包之后，需清理再重新make。
    
    > make distclean
    
    > make
5. 运行
    > src/redis-server
    > src/redis-cli
    > ping
    如果显示pong,则说明安装成功。

## 配置

* redis.config
    redis的默认配置文件在安装目录下的redis.config.
    可以使用命令 
    > config set [key] [value]

    或者直接编辑config文件来修改配置。