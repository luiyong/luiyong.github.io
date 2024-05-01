---
title: EBPF学习系列(零)：环境准备
date: 2024/05/01 13:46
tags: 内核
categories: EBPF
---

### 环境
- 使用libbpf-bootstrap仓库创建一个自己的仓库
- 创建一个Github codespace
### 编译运行

#### 系统更新
```shell
sudo apt-get update 
sudo apt-get install linux-generic
```

#### 安装依赖
- 参考README
#### 编译
- 参考README

#### 挂载Ftrace
```shell
sysctl -q kernel.ftrace_enabled=1

mount -t debugfs debugfs /sys/kernel/debug/
mount -t tracefs tracefs /sys/kernel/debug/tracing
```
#### 运行示例
