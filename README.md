# 🚀 System Design Course

> 从零到一的系统设计学习路径 | A Comprehensive System Design Learning Path

## 📖 课程简介

这是一个系统化的系统设计学习课程，通过 12 周的学习，从基础到进阶，帮助你掌握大规模分布式系统的设计能力。

## 🎯 学习目标

- 理解系统设计的核心概念和原则
- 掌握常见系统组件的使用场景
- 学会设计可扩展、高可用的系统
- 通过实战项目巩固知识
- 为系统设计面试做好准备

## 📚 课程大纲

### 第一阶段：基础知识（Week 1-3）

#### Week 1: 系统设计基础概念
- [ ] 系统设计面试流程
- [ ] 可扩展性（Scalability）
- [ ] 可靠性（Reliability）
- [ ] 可用性（Availability）
- [ ] 性能指标（Latency, Throughput）
- [ ] CAP 定理
- [ ] 一致性模型

📂 [Week 1 学习资料](./week-01-fundamentals/)

#### Week 2: 网络与协议基础
- [ ] HTTP/HTTPS
- [ ] TCP/UDP
- [ ] DNS
- [ ] WebSocket
- [ ] REST vs GraphQL vs gRPC
- [ ] API 设计最佳实践

📂 [Week 2 学习资料](./week-02-networking/)

#### Week 3: 数据库基础
- [ ] SQL vs NoSQL
- [ ] 关系型数据库（MySQL, PostgreSQL）
- [ ] NoSQL 数据库（MongoDB, Cassandra）
- [ ] 数据库索引
- [ ] 数据库复制（Replication）
- [ ] 数据库分片（Sharding）
- [ ] ACID vs BASE

📂 [Week 3 学习资料](./week-03-databases/)

---

### 第二阶段：核心组件（Week 4-6）

#### Week 4: 缓存系统
- [ ] 缓存策略（Cache Strategies）
- [ ] 缓存失效策略（LRU, LFU, FIFO）
- [ ] Redis 深入理解
- [ ] Memcached
- [ ] CDN 缓存
- [ ] 缓存雪崩、穿透、击穿

📂 [Week 4 学习资料](./week-04-caching/)

#### Week 5: 负载均衡与 CDN
- [ ] 负载均衡算法
- [ ] Layer 4 vs Layer 7 负载均衡
- [ ] Nginx 实战
- [ ] CDN 工作原理
- [ ] 反向代理
- [ ] 健康检查

📂 [Week 5 学习资料](./week-05-load-balancing/)

#### Week 6: 消息队列
- [ ] 消息队列基础
- [ ] Kafka 深入理解
- [ ] RabbitMQ
- [ ] 发布-订阅模式
- [ ] 消息可靠性
- [ ] 事件驱动架构

📂 [Week 6 学习资料](./week-06-message-queues/)

---

### 第三阶段：实战项目（Week 7-10）

#### Week 7: 设计 URL 短链接服务
- [ ] 需求分析
- [ ] 容量估算
- [ ] API 设计
- [ ] 数据库设计
- [ ] 生成短链接算法
- [ ] 完整系统架构图
- [ ] 代码实现

📂 [Week 7 项目](./week-07-url-shortener/)

#### Week 8: 设计社交媒体信息流
- [ ] 推送模式 vs 拉取模式
- [ ] Feed 生成算法
- [ ] 时间线设计
- [ ] 扇出（Fan-out）策略
- [ ] 热点用户处理
- [ ] 完整系统架构图
- [ ] 代码实现

📂 [Week 8 项目](./week-08-social-feed/)

#### Week 9: 设计聊天系统
- [ ] 实时通信（WebSocket）
- [ ] 消息存储
- [ ] 在线状态
- [ ] 群组聊天
- [ ] 消息推送
- [ ] 完整系统架构图
- [ ] 代码实现

📂 [Week 9 项目](./week-09-chat-system/)

#### Week 10: 设计视频分享平台
- [ ] 视频上传流程
- [ ] 视频转码
- [ ] CDN 分发
- [ ] 流媒体协议
- [ ] 推荐系统
- [ ] 完整系统架构图
- [ ] 代码实现

📂 [Week 10 项目](./week-10-video-platform/)

---

### 第四阶段：高级主题（Week 11-12）

#### Week 11: 微服务架构
- [ ] 单体 vs 微服务
- [ ] 服务发现
- [ ] API Gateway
- [ ] 服务间通信
- [ ] 分布式追踪
- [ ] 熔断器模式

📂 [Week 11 学习资料](./week-11-microservices/)

#### Week 12: 分布式系统与一致性
- [ ] 分布式锁
- [ ] 分布式事务
- [ ] 共识算法（Paxos, Raft）
- [ ] 最终一致性
- [ ] 分布式 ID 生成
- [ ] 限流与降级

📂 [Week 12 学习资料](./week-12-distributed-systems/)

---

## 🛠️ 技术栈

在学习过程中，你将接触到以下技术：

- **编程语言**: Python, Go, Java（选择你熟悉的）
- **数据库**: PostgreSQL, MySQL, MongoDB, Redis, Cassandra
- **消息队列**: Kafka, RabbitMQ
- **缓存**: Redis, Memcached
- **Web 服务器**: Nginx
- **容器化**: Docker, Kubernetes（可选）
- **监控**: Prometheus, Grafana（可选）

## 📖 推荐学习资源

### 书籍
- 📕 **Designing Data-Intensive Applications** by Martin Kleppmann
- 📗 **System Design Interview Vol 1 & 2** by Alex Xu
- 📘 **Database Internals** by Alex Petrov
- 📙 **Microservices Patterns** by Chris Richardson

### 在线资源
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [ByteByteGo Newsletter](https://blog.bytebytego.com/)
- [High Scalability Blog](http://highscalability.com/)

### 视频课程
- [Gaurav Sen - System Design](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
- [System Design Interview](https://www.youtube.com/c/SystemDesignInterview)

## 💡 学习建议

1. **循序渐进**: 按照周次顺序学习，不要跳过基础部分
2. **动手实践**: 每个项目都要自己动手实现
3. **画图**: 系统设计重在架构图，多练习画图
4. **提问思考**: 每个设计都要问"为什么"
5. **复习总结**: 每周结束后总结核心要点
6. **面试准备**: 熟悉常见面试题的答题框架

## 🎯 学习检查清单

每周学习后，检查是否完成：

- [ ] 阅读完本周所有学习资料
- [ ] 理解核心概念并能用自己的话解释
- [ ] 完成本周的练习题
- [ ] （如有）完成本周的项目实现
- [ ] 画出完整的系统架构图
- [ ] 在 issues 中记录学习笔记和疑问

## 📝 学习笔记

建议为每周学习创建独立的学习笔记，可以：

1. Fork 这个仓库
2. 在每周文件夹中添加你的笔记
3. 提交你的代码实现
4. 在 Issues 中提问和讨论

## 🤝 贡献

欢迎提出建议和改进！

- 发现错误？提交 Issue
- 有更好的解决方案？提交 Pull Request
- 想分享学习心得？欢迎在 Discussions 中交流

## 📜 License

MIT License

---

**开始你的系统设计学习之旅吧！🚀**

如有任何问题，欢迎在 Issues 中提问。