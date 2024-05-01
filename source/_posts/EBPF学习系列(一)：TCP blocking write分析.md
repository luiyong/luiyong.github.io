---
title: EBPF学习系列(一)：TCP Block Write分析
date: 2024/05/01 13:46
tags: 内核
categories: EBPF
---

### 重点
#### TSO分段
#### 发送缓冲区变化
#### CWND变化 慢启动


### 源码地址
- [tcp_trace](https://github.com/luiyong/nettrace/blob/master/examples/c/tcp_trace.c)
### 参考文章
* [Code Walkthrough](http://chenshuo.com/tcpip-study/walkthrough/)
* [一个 TCP 发送缓冲区问题的解析](https://segmentfault.com/a/1190000021488755)