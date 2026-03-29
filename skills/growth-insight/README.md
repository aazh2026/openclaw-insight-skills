# 📚 Daily Growth - 每日精进与认知突破

一个用于 OpenClaw AI Agent 的 Skill，帮助 Agents 协作生成每日学习总结和认知升级报告。

## 🎯 核心功能

- **每日精进**：从当日对话、阅读、思考中提炼关键学习点
- **认知突破**：识别并记录思维模式的升级和心智模型的更新
- **多 Agent 协作**：支持多个人格化 Agent 从不同视角贡献精进内容
- **结构化输出**：标准化的日报、周报、月报模板

## 📦 安装

```bash
# 下载 skill 文件
wget https://github.com/aazh2026/daily-growth-skill/raw/main/daily-growth.skill

# 安装到 OpenClaw
openclaw skills install daily-growth.skill
```

## 🚀 使用

在 OpenClaw 中，当用户说以下任一指令时触发：
- "每日精进"
- "认知突破"
- "今日复盘"
- "学习总结"

### 多 Agent 协作示例

```
@warren @drucker @paulgraham 每日精进
```

每个 Agent 会从自己专业领域提炼精进：
- **Warren**：投资思维、商业逻辑
- **Drucker**：管理原则、组织效能
- **Paul Graham**：创业思维、技术趋势
- ...

## 📁 文件结构

```
daily-growth/
├── SKILL.md                 # 核心技能定义
└── references/
    └── templates.md         # 日报/周报/月报模板
```

## 🧠 认知突破判定标准

满足以下任一即视为认知突破：
- 🧠 **心智模型更新**：用新模型替代旧模型
- 🔗 **跨域连接**：建立不同领域间的新联系
- ❓ **问题重构**：对问题的定义方式发生改变
- 🎯 **优先级重构**：价值判断标准发生变化
- 🚫 **去伪存真**：识破并摒弃错误认知

## 📝 输出示例

详见 [references/templates.md](daily-growth/references/templates.md)

## 📄 License

MIT
