# Focused Execution

一个帮助 Codex 用户启动困难任务、减少拖延、保护专注并完成复杂工作的执行教练 Skill。

它不会把“拖延”简单归因于懒惰，而是根据当前任务识别具体卡点，例如：过度规划、先做容易的小事、细节打磨过早、新想法频繁抢占注意力、临近截止时间才启动，以及受挫后推翻重来。

## 能做什么

- 把模糊或复杂的任务转成一个可以立即开始的主任务
- 用“最低 / 可用 / 理想”三级质量标准控制完美主义
- 按“骨架 → 可用版本 → 选择性优化”推进复杂产物
- 生成一个约 10 分钟内可以留下的可见成果
- 用切换闸门和想法停车场减少任务漂移
- 在卡住、受挫或进度落后时缩小范围并恢复执行
- 根据实际产物、切换次数和启动延迟进行复盘

## 四种工作模式

| 模式 | 适用场景 |
| --- | --- |
| Launch | 新任务迟迟没有开始，需要生成第一轮执行卡 |
| Guard | 正在执行，但被新想法、小任务或范围扩张干扰 |
| Rescue | 卡住、受挫、落后，或者想把现有方案全部推翻 |
| Review | 复盘一轮执行，并为下一轮只调整一个变量 |

## 安装

将仓库克隆到 Codex Skills 目录：

```bash
git clone https://github.com/changtianjiao39-lab/focused-execution-skill.git ~/.codex/skills/focused-execution
```

重新打开 Codex 对话后，即可通过 `$focused-execution` 调用。

## 使用示例

```text
使用 $focused-execution：进入专注模式。
我要在周五前完成一份产品方案，但一直在补资料，还没有开始写正文。
```

```text
使用 $focused-execution：我现在突然想切换到另一件事，帮我判断是否真的应该切换。
```

```text
使用 $focused-execution：这个任务被我越做越复杂了，帮我收缩成今天能交付的版本。
```

```text
使用 $focused-execution：复盘刚才的执行，下一轮只调整一个变量。
```

## 工作原则

1. 一次只保护一个主任务。
2. 按影响、截止后果和依赖价值排序，不按容易程度排序。
3. 先形成完整骨架，再处理局部细节。
4. 通过早期可见成果替代最后时刻的压力启动。
5. 缩小范围优先于延长工作时间，不把通宵作为常规方案。
6. 用行为证据复盘，不把一次执行困难解释为人格问题。

## 项目结构

```text
focused-execution/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── coaching-patterns.md
    ├── evidence-and-methods.md
    └── templates.md
```

- [`SKILL.md`](SKILL.md)：核心工作流和执行护栏
- [`coaching-patterns.md`](references/coaching-patterns.md)：常见执行模式与干预方法
- [`evidence-and-methods.md`](references/evidence-and-methods.md)：研究依据与证据边界
- [`templates.md`](references/templates.md)：启动、切换、救援和复盘模板

## 使用边界

本 Skill 提供的是行为层面的执行支持，不构成医疗诊断或治疗，也不会仅凭拖延、分心等表现推断 ADHD 或其他疾病。持续且明显影响多个生活领域的问题，应考虑寻求专业评估。

## License

[MIT](LICENSE)
