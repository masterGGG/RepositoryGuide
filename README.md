[toc]

明哥仓库导航

1. 基础知识库
> [算法](https://github.com/masterGGG/algorithm)

> [设计模式](https://github.com/masterGGG/DesignMode)

> [网络](https://github.com/masterGGG/Network)

> [操作系统](https://github.com/masterGGG/OperateSystem)

> [数据库](https://github.com/masterGGG/DataBase)

# 分布式存储
## 常用proxy
* [codis](https://github.com/masterGGG/codis) 豌豆荚开源的proxy代理，go语言开发，支持pipeline，提供多种维度的监控数据。
* [twme_proxy](https://github.com/twitter/twemproxy)，推特开源的proxy代理，c语言开发，单线程模式，后端连接收敛，支持pipeline。
## [Tendis](https://github.com/Tencent/Tendis)
Tendis存储版是腾讯互娱CROS DBA团队 & 腾讯云数据库团队 自主设计和研发的开源分布式高性能KV存储。完全兼容redis协议，并使用rocksdb作为存储引擎。用户可以通过redis client访问Tendis存储版，几乎不用修改代码。同时，Tendis存储版支持远超内存的磁盘容量，可以大大降低用户的存储成本。

# 网络IO框架
* [muduo](https://github.com/chenshuo/muduo)
* [async_server](https://github.com/masterGGG/async_server)

# 协程
[libco](https://github.com/Tencent/libco) 是微信后台大规模使用的c/c++协程库

# Work Experience
## 18_19 components
Fouce on Community System(UCG). Including recommend, push, feed, IO components.

* [推荐系统](https://github.com/masterGGG/mifan-recommend)，根据feed权重以及用户兴趣权重打分，计算出用户兴趣feed的集合。
* [feed流](https://github.com/masterGGG/feed)相关服务，包括用户操作事件流，feed流的生成，以及feed流相关的推荐。
feed
* [图片存储]](https://github.com/masterGGG/pic_server)服务，包括图片上传，图片解析，图片缩略，图片存储。后端使用fastdfs作为存储层，lighttpd作为web端提供图片操作API，varnish用作web侧缓存。
* [个人git图片存储地址](https://github.com/masterGGG/common)
* [高并发IO网络框架](https://github.com/masterGGG/async_server)

# 运维&问题排查
* [极客时间专栏《Linux 性能优化实战》案例源码](https://github.com/feiskyer/linux-perf-examples) 

# ios开发
[网站+iOS App源码](https://github.com/michaelliao/awesome-python3-webapp) 
