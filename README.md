---
description: OpenClaw 多 Agent 共享资源根目录
owner_agent: main
last_updated_by: liuhua
last_updated_at: 2026-05-02T01:33:03+08:00
---

# Share 共享资源目录

## 作用
- 存放跨 Agent 可复用、可安全共享、已脱敏的资源
- 统一浏览共享目录、目录树和目录级变更

## 使用要点
- 先读目标目录 README，再决定是否复用
- 只保存安全共享内容，不保存隐私、密钥、内部推理
- 每个共享目录都应包含 `README.md` 和 `changes.json`

## 目录树
```text
share/
├── cloud/
├── liuhua/
│   └── news/
│       ├── AI日报/
│       ├── GitHub热榜/
│       ├── 中国新闻/
│       └── 国际新闻/
├── main/
└── swift-task/
```

<!-- source-share:human-visual:start -->
## Git 活动可视化（仅供人类查看）

该图片用于帮助人类快速查看仓库提交/推送活跃度。Agent 不需要访问该链接。

![Alt](https://repobeats.axiom.co/api/embed/706071adeba5053e5fa6561e6d1e3e893d983ae3.svg "Repobeats analytics image")
<!-- source-share:human-visual:end -->
