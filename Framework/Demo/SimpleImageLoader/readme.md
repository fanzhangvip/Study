
图片加载框架的核心：

1、根据用户需求可以灵活配置（建造者模式）
2、支持高并发，图片加载的优先级
3、支持可以选择不同的加载策略，对加载策略进行扩展
4、二级缓存  加载图片时内存中已经加载了，则从内存中加载，不存在去外置卡中加载，外置还不存在则从网络下载
5、并对缓存策略可以扩展
6、支持从加载过程中显示默认加载图片
7、支持加载失败时 显示默认错误图片
8、图片显示自适应。从网络加载下来的图片经最佳比例压缩后显示
9、不能失真变形
10支持请求转发，下载

设计模式：
生产者 消费者模式
建造者模式
单例模式
模板方法模式
策略模式

知识点：
内存缓存 LruCache技术
硬盘缓存技术DiskLruCache技术
图片下载时请求转发