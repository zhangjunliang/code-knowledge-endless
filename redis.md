# Redis

- 数据类型
    - string 字符串：最基本的数据类型，二进制安全的字符串，最大512M
    - hash 哈希
    - list 列表：可用做用作栈、队列、阻塞队列
    - set 集合
    - zset 有序集合
    ##### Redis v3.2+ 以后新增数据类型
    - geospatial  Geo类型：地理位置信息储存起来， 并对这些信息进行操作
    - hyperloglog 基数：基于概率的数据结构
    > 数学上集合的元素个数，是不能重复的。
    - bitmap 位图：更细化的一种操作，以bit为单位。 
    > btmap就是通过最小的单位bit来进行0或者1的设置，表示某个元素对应的值或者状态。
      一个bit的值，或者是0，或者是1；也就是说一个bit能存储的最多信息是2。
      bitmap 常用于统计用户信息比如活跃粉丝和不活跃粉丝、登录和未登录、是否打卡、布隆过滤器等。

- 缓存引起的问题？

    - 缓存击穿
    - 缓存穿透
    - 缓存雪崩

- Redis Module Hub
    > Redis Module Hub是Redis官方的模块仓库，目前已经有将近二十个模块，其中一大半是Redis Labs自己贡献的，算是抛砖引玉吧，下边随便拿出几个做一下简单的介绍：
   
    > 对现有数据结构功能的扩展，如：
    - rxkeys提供了按正则表达式批量获取与删除条目的功能
    - rxhashes提供了在Hash中改变现有条目的值并返回原值的原子操做
    - rxlists提供了7个新的列表操作方法。
    > 新数据结构，如：
    - rejson提供了对原生JSON格式支持，允许对JSON数据内的值进行获取与修改
    - Redis Graph添加了对图数据库的支持
    - redisearch实现了全文搜索，使用特殊的压缩数据结构，加快了搜索的速度，并且减少了内存占用
    - redis-ml实现了多个机器学习常用的数据结构及相关方法
    > 对功能的扩展，如：
    - graphicsmagick提供类似GraphicsMagick的图片处理功能，从此生成缩略图，打水印都可以在Redis里做了
    - redablooms基于RedisString的Bloom filter，可以用于ID生成
    - password提供加密的密码存储