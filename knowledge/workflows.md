# Workflows

## 记忆写入路由
- 当前状态、优先级、阻塞、下一步 → `NOW.md`
- 当天发生的事件、操作记录、临时上下文 → `memory/YYYY-MM-DD.md`
- 长期有效的偏好、决策、规则、项目背景 → `knowledge/*.md`

## 会话启动最小读取顺序
1. `SOUL.md`
2. `USER.md`
3. `NOW.md`
4. 今天和昨天的 daily memory
5. `knowledge/INDEX.md`
6. 主会话再读 `MEMORY.md`

## Heartbeat 最小职责
1. 检查 `NOW.md` 是否需要刷新
2. 检查今天 daily 是否遗漏重要事项
3. 检查是否有内容值得提炼到 `knowledge/`
4. 检查是否有久未推进的待跟进事项
