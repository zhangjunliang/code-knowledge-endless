# Redis

## Redis Module Hub

        Redis Module Hub是Redis官方的模块仓库，目前已经有将近二十个模块，其中一大半是Redis Labs自己贡献的，
    算是抛砖引玉吧，下边随便拿出几个做一下简单的介绍：
        对现有数据结构功能的扩展，如：
        rxkeys提供了按正则表达式批量获取与删除条目的功能
        rxhashes提供了在Hash中改变现有条目的值并返回原值的原子操做
        rxlists提供了7个新的列表操作方法。
        新数据结构，如：
        rejson提供了对原生JSON格式支持，允许对JSON数据内的值进行获取与修改
        Redis Graph添加了对图数据库的支持
        redisearch实现了全文搜索，使用特殊的压缩数据结构，加快了搜索的速度，并且减少了内存占用
        redis-ml实现了多个机器学习常用的数据结构及相关方法
        对功能的扩展，如：
        graphicsmagick提供类似GraphicsMagick的图片处理功能，从此生成缩略图，打水印都可以在Redis里做了
        redablooms基于RedisString的Bloom filter，可以用于ID生成
        password提供加密的密码存储