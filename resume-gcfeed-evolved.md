# [你的姓名]

> <span class="icon">&#xe60f;</span> `[手机号]`&emsp;&emsp; <span class="icon">&#xe7ca;</span> `[邮箱]`&emsp;&emsp; <span class="icon">&#xe600;</span> [GitHub](https://github.com/[用户名])

## &#xe80c; 教育经历

<div alt="entry-title">
    <h3>[学校] - [学历] - [专业]</h3>
    <p>[YYYY.MM] - [YYYY.MM]</p>
</div>

## &#xe635; 项目经历

<div alt="entry-title">
    <h3>GCFeed | 可观测、可压测的短视频 Feed 工程</h3>
    <a href="https://github.com/LeoninCS/GCFeed">github.com/LeoninCS/GCFeed</a>
</div>

**项目背景：** 在基础 Feed 系统之上，面向更完整的内容供给、分发、消费、互动与治理链路，提升架构可维护性、异步扩展能力和线上性能验证能力。

**解决方案：**
- **重构**为 Domain、Application、Infrastructure、Interfaces 分层的 Go API 单体，明确领域模型、用例编排、基础设施和 HTTP 接口边界，并以 Gin + GORM + MySQL 提供 REST 服务。
- **完善** Redis Feed 缓存、热榜和互动计数；通过 RabbitMQ 异步处理互动落库、视频发布事件和向量任务，形成可扩展的事件驱动链路。
- **建设** React + Vite Web 客户端、消息中心与播放优化接入，补齐从内容生产到消费端的闭环体验。
- **补上工程验证闭环：** 提供 API 流程测试、Web 生产构建、Docker Compose 环境，以及 Prometheus 指标和 Grafana 面板，观测 API QPS、5xx、API/Feed P95、缓存命中率、上传耗时和 Worker 成功率。
- **建立** OpenSpec 变更规范、架构/优化/性能测试文档和 k6 压测流程，使新增模块、性能回归和交付验证可重复执行。

**项目成果：** 形成覆盖 API、Web、MySQL、Redis、RabbitMQ、Prometheus、Grafana 的可运行工程基线；提供健康检查、指标端点和 Compose 一键部署。审核后台、运营后台和系统治理仍列为后续能力，简历不将其包装为已完成。

## &#xecfa; 专业技能

- Go、Gin、GORM、MySQL；分层架构、领域建模、REST API 与流程测试。
- Redis Feed/热榜/计数缓存，RabbitMQ 事件驱动、异步 Worker、向量任务。
- React、Vite、Docker Compose；Prometheus、Grafana、k6、P95/QPS/错误率分析。
- OpenSpec 工程变更管理、架构文档、性能测试和可观测性建设。

