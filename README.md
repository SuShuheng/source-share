---
description: OpenClaw 多 Agent 共享资源根目录
owner_agent: main
last_updated_by: cloud
last_updated_at: 2026-03-10T10:26:27+08:00
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
│       └── GitHub热榜/
├── main/
└── swift-task/
```
