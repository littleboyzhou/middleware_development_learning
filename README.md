# middleware_development_learning
手把手教你做中间件、高性能服务器、分布式存储等(redis、memcache、pika、rocksdb、mongodb、wiredtiger、高性能代理中间件)二次开发、性能优化，逐步整理文档说明并配合demo指导  
  
近期抽业余时间来总结多年工作中学习到的各种中间件、分布式存储、高性能服务端等技术，通过文章博客和程序demo等方式呈现给大家，暂定分享思路如下：
  
分阶段分享  
===================================  
第一阶段：手把手教你做分布式缓存源码学习、二次开发、性能及稳定性优化  
主要涉及网络实现、memcache redis重要模块源码分析、memcache redis性能稳定性优化及二次开发等  
  
  
第二阶段：手把手教你做高性能代理中间件开发(主要结合高性能web服务器nginx、缓存代理中间件twemproxy、mysql代理中间件dbproxy、mongodb代理中间件mongos等源码进行二次开发)  
主要涉及代理中间件源码分析、性能优化、二次开发等  
  
  
  
第三阶段：手把手教你做分布式大容量nosql存储系统二次开发(突破缓存内存容量限制)  
主要涉及pika源码、rocksdb存储引擎源码分析及pika性能优化等  
  
  
  
第四阶段：手把手教你做mongodb数据库内核开发(突破redis、pika只支持redis协议限制，学习更复杂查询、索引、更多数据库相关等实现原理)  
主要涉及mongodb源码、mongos源码、rocksdb存储引擎源码、wiredtiger存储引擎源码分析及二次开发  
  
  
第一阶段：手把手教你做分布式缓存开发、性能稳定性优化
===================================  
借助redis已有的网络相关.c和.h文件，半小时快速实现一个epoll异步网络框架，程序demo如下：  
https://github.com/y123456yz/middleware_development_learning/tree/master/%E7%AC%AC%E4%B8%80%E9%98%B6%E6%AE%B5-%E6%89%8B%E6%8A%8A%E6%89%8B%E6%95%99%E4%BD%A0%E5%81%9A%E5%88%86%E5%B8%83%E5%BC%8F%E7%BC%93%E5%AD%98%E4%BA%8C%E6%AC%A1%E5%BC%80%E5%8F%91%E3%80%81%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96/%E5%BC%82%E6%AD%A5%E7%BD%91%E7%BB%9C%E6%A1%86%E6%9E%B6%E9%9B%B6%E5%9F%BA%E7%A1%80%E5%AD%A6%E4%B9%A0/asyn_network



