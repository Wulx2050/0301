---
name: "memory"
description: "MANDATORY skill: You MUST use this skill at session start/end and before answering questions about past work. Create .memory/ if not exists, maintain MEMORY.md and memory/YYYY-MM-DD.md."
---

# Memory Skill (MANDATORY)

**记住东西是你的职责。**

## 核心规则

### Session Start
1. 检查 `.memory/` 是否存在
2. 若不存在，创建：
   - `.memory/MEMORY.md` (长期记忆)
   - `.memory/memory/YYYY-MM-DD.md` (今日日记)
3. 读取今日和昨日日记了解上下文

### 回答问题前
- **必须先读取记忆**，再回答

### Session End
1. 总结今天完成的工作
2. 保存到 `.memory/memory/YYYY-MM-DD.md`
3. 重要信息移到 `.memory/MEMORY.md`

## 文件结构

```
.memory/
├── MEMORY.md              # 长期记忆
└── memory/
    └── YYYY-MM-DD.md      # 每日日记
```

## 格式模板

**每日日记：**
```markdown
## Session [时间]

### What we did
- 工作总结

### Key findings
- 重要发现

### Decisions
- 决策

### User preferences
- 用户偏好

### Next steps
- 待办事项
```

**长期记忆：**
```markdown
## 用户信息

## 项目经验

## 偏好设置
```

---

**记住：使用记忆不是可选的。这是你的工作。**
