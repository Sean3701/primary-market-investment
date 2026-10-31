# 已有 skill 的方法复用与边界

本包在制作时审阅了下列本地 skill 的相关部分。它们是分析方法来源，不是公司事实来源；不需要同时安装。本包不改动原 skill，也不将其全部流程设为依赖。

| 方法来源 | 复用内容 | 一级市场改造 |
|---|---|---|
| private-company-research | 信息稀缺与投资质量分离、事实与推断、冲突数据、信号一致性、失败与退出路径 | 以用户 BP 为入口；从实际成熟度出发；不强制六角色团队或完整公开信息 |
| investment-research | 客户与赚钱方式、竞争优势、逆向检验、商业价值、可核验的计算 | 允许早期尚无利润或护城河；不要求上市价格与五年财报 |
| management-deep-dive | 承诺与兑现、真实决策人、执行和危机处理、利益相关方与治理 | 重视创始人与问题匹配、学习和交付；不把履历直接等于能力，也不机械沿用兑现率评分 |
| financial-data | 口径、币种、日期、多源与工具验算 | 原始证据优先；单源诚实标注，不伪造第二来源；不强制沿用上市财经数据站和固定误差阈值 |
| investment-checklist | 理解生意、经济特征、价格与风险纪律 | 原版跳过未上市公司，不能直接调用作为本项目检查；不套固定ROE、毛利、利润或星级门槛 |
| thesis-tracker | 可验证核心假设、红线、逐条复核、估值更新 | 跟踪私人公司里程碑、融资与条款；不把触发风险写成可立即卖出，不自动启动监控 |

如果这些 skill 可用且用户要求专项深研，可加载相应部分补充；它们的上市数据、脚本路径、团队规模和保存规则不是本包的默认执行要求。仅复用适合当前项目的方法。

## 本轮整合（2026-10-31）

本地 investment-memo-craft 提供生意机制、反方论证和估值转行动的写作思路；本包以个人首轮判断为主，保留摘要在前，不沿用上市股买卖价位、固定历史年限或无依据的风险概率。

| 外部来源 | 吸收的方法 | 取舍 |
|---|---|---|
| [Investor Perspective](https://github.com/mengbao/investor-perspective/blob/main/SKILL.md) | 明确是否继续接触，结构化审视需求与项目 | 不复制创业导师职责或固定19节要求 |
| [D-kart investor-skill](https://github.com/D-kart/investor-skill/blob/main/SKILL.md) | 事实、推理、判断分层，主动找反证 | 不完整串行运行六套机构流程 |
| [D-kart BP Analysis](https://github.com/D-kart/investor-skill/blob/main/references/03-bp-analysis.md) | BP美化识别、关键问题与下一步材料 | 扩为完整报告；不机械要求10倍优势、统一财务指标或按正向项数量决定推荐 |
| [Anthropic DD Checklist](https://github.com/anthropics/financial-services/blob/main/plugins/vertical-plugins/private-equity/skills/dd-checklist/SKILL.md) | 分领域、优先级、状态及风险对交易的影响 | 个人可执行清单，不默认团队工作簿；办理状态与证据状态分离 |
| [Investment Memo](https://github.com/claude-office-skills/skills/blob/main/investment-memo/SKILL.md) | 投资逻辑、风险、交易和行动的报告结构 | 不预设投委会、机构目标仓位或 office-mcp 依赖 |

以上是方法来源，不是标的事实来源。吸收判断原则，未复制外部整份模板；使用本包不要求访问或安装这些项目。外部 main 可能变化，以上描述对应本次审阅，不是长期兼容承诺。
