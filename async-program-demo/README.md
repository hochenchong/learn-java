## Java 异步编程实战

### 前言
该项目记录一下读《Java 异步编程实战》时，书中的代码（并不一定和书中一样）。

作者提供的 demo 地址：[https://github.com/zhailuxu/async-program-demo](https://github.com/zhailuxu/async-program-demo)

---

### 第2章 显式使用线程和线程池实现异步编程

#### 2.1 显式使用线程实现异步编程
* [SyncExample](./src/chapter02/SyncExample.java)
* [AsyncExample](./src/chapter02/AsyncExample.java)

#### 2.2 显式使用线程池实现异步编程
* [ThreadPoolExample](./src/chapter02/ThreadPoolExample.java)
* [AsyncThreadPoolExample](./src/chapter02/AsyncThreadPoolExample.java)
* 自定义 ThreadFactory 例子：[NamedThreadFactoryExample](./src/chapter02/NamedThreadFactoryExample.java)

---

### 第 3 章 基于 JDK 中的 Future 实现异步编程

#### 3.2 JDK 中的 FutureTask
* [AsyncFutureExample](./src/chapter03/AsyncFutureExample.java)

#### 3.3 JDK 中的 CompletableFuture
* [CompletableFutureExample](./src/chapter03/CompletableFutureExample.java)
* [TwoCompletableFutureExample](./src/chapter03/TwoCompletableFutureExample.java)

#### 3.4 JDK8 Stream & CompletableFuture
* [StreamTestFuture](./src/chapter03/StreamTestFuture.java)

---

### 后记

开始时间：2024-06-05

结束时间：