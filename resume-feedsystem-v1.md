# [你的姓名]

> <span class="icon">&#xe60f;</span> `[手机号]`&emsp;&emsp; <span class="icon">&#xe7ca;</span> `[邮箱]`&emsp;&emsp; <span class="icon">&#xe600;</span> [GitHub](https://github.com/[用户名])

## &#xe80c; 教育经历

<div alt="entry-title">
    <h3>[学校] - [学历] - [专业]</h3>
    <p>[YYYY.MM] - [YYYY.MM]</p>
</div>

## &#xe635; 项目经历

<div alt="entry-title">
    <h3>FeedSystem Video Go | 短视频 Feed 流系统</h3>
    <a href="https://github.com/[你的仓库地址]">github.com/[你的仓库地址]</a>
</div>

**项目背景：** 面向短视频内容发布、分发和互动场景，构建具备登录、上传、Feed 浏览与社交互动能力的全栈系统，解决视频上传可靠性、Feed 分页和互动事件实时反馈等问题。

**解决方案：**
- **设计** Go + Vue 3 前后端架构，以 MySQL 持久化业务数据，使用 Redis 承载 Token、视频详情、Feed 时间线和热榜窗口缓存，按 API 与 Worker 拆分运行职责。
- **实现** 5MB 分片上传链路，支持文件 MD5、分片 MD5 校验、断点续传、状态查询与合并，覆盖最多 200MB 视频文件的发布流程。
- **构建**推荐流、关注流、点赞榜、热榜和话题流，采用冷热分离、游标分页与复合游标，降低深分页对数据库的压力。
- **引入** RabbitMQ Topic Exchange 异步处理点赞、评论、关注、热度和视频时间线事件，并配置死信交换机；通过 SSE 推送通知、未读计数和已读标记。

**项目成果：** 交付账号、视频、点赞、评论、关注、Feed、私信和通知八大业务模块；提供 Docker Compose 与 `start.sh` 一键启动，接入健康检查、限流和 pprof；GitHub Actions 自动执行 `go vet`、竞态测试和前端生产构建。

## &#xecfa; 专业技能

- Go、Gin、GORM、MySQL；能够按 Domain/Application/Infrastructure/Interfaces 思路拆分后端职责。
- Redis 缓存与时间线设计，RabbitMQ Topic Exchange、异步 Worker、死信队列和最终一致性处理。
- JWT Access/Refresh Token、SSE 实时推送、分片上传与断点续传、游标分页。
- Vue 3、Docker Compose、GitHub Actions、pprof、Go 测试与 race 检测。

