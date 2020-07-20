### 系统设计的面试

在很多科技公司中，除了代码面试，系统设计也是**技术面试过程**中的一个**必要环节**。

**实践常见的系统设计面试题**并且把你的答案和**例子的解答**进行**对照**：讨论，代码和图表。

面试准备的其他主题：

* [学习指引](#学习指引)
* [如何处理一个系统设计的面试题](#如何处理一个系统设计的面试题)
* [系统设计的面试题，**含解答**](#系统设计的面试题和解答)
* [面向对象设计的面试题，**含解答**](#面向对象设计的面试问题及解答)
* [其它的系统设计面试题](#其它的系统设计面试题)

### 代码资源：互动式编程挑战

你正在寻找资源以准备[**编程面试**](https://github.com/donnemartin/interactive-coding-challenges)吗？

<p align="center">
  <img src="http://i.imgur.com/b4YtAEN.png"/>
  <br/>
</p>

请查看我们的姐妹仓库[**互动式编程挑战**](https://github.com/donnemartin/interactive-coding-challenges)，其中包含了一个额外的抽认卡堆：

* [代码卡堆](https://github.com/donnemartin/interactive-coding-challenges/tree/master/anki_cards/Coding.apkg)

### 微服务

与此讨论相关的话题是 [微服务](https://en.wikipedia.org/wiki/Microservices)，可以被描述为一系列可以独立部署的小型的，模块化服务。每个服务运行在一个独立的线程中，通过明确定义的轻量级机制通讯，共同实现业务目标。<sup><a href=https://smartbear.com/learn/api-design/what-are-microservices>1</a></sup>

例如，Pinterest 可能有这些微服务： 用户资料、关注者、Feed 流、搜索、照片上传等。

### 服务发现

像 [Consul](https://www.consul.io/docs/index.html)，[Etcd](https://coreos.com/etcd/docs/latest) 和 [Zookeeper](http://www.slideshare.net/sauravhaloi/introduction-to-apache-zookeeper) 这样的系统可以通过追踪注册名、地址、端口等信息来帮助服务互相发现对方。[Health checks](https://www.consul.io/intro/getting-started/checks.html) 可以帮助确认服务的完整性和是否经常使用一个 [HTTP](#超文本传输协议http) 路径。Consul 和 Etcd 都有一个内建的 [key-value 存储](#键-值存储) 用来存储配置信息和其他的共享信息。
