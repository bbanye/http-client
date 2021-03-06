# http-client

> 最后一次作业了解异步和同步的原理。

参考：
  + [理解 goroutine 的并发](http://blog.csdn.net/pmlpml/article/details/78850661)
  + [Reactive JAX-RS Client API](https://jersey.github.io/documentation/latest/rx-client.html)


## 作业要求

  + 依据文档图6-1，用中文描述 Reactive 动机
  + 使用 go HTTPClient 实现图 6-2 的 Naive Approach
  + 为每个 HTTP 请求设计一个 goroutine ，利用 Channel 搭建基于消息的异步机制，实现图 6-3
  + 对比两种实现，用数据说明 go 异步 REST 服务协作的优势
  + 思考： 是否存在一般性的解决方案？
