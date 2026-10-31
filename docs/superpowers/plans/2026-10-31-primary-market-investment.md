# Primary Market Investment Implementation Plan

> **For agentic workers:** Use superpowers:executing-plans to implement task-by-task.

**Goal:** 全阶段个人 BP 首轮判断默认交付完整长报告及省流版。
**Architecture:** 保留现有单入口，新增研究执行参考，扩展报告模板与阶段规则，共用证据底稿派生双报告。
**Tech Stack:** Markdown、YAML、本地 Python 校验、合成案例行为测试。
**Spec:** ../specs/2026-10-31-primary-market-investment-design.md（用户已批准）。

## Global Constraints

默认中文、全阶段、个人使用、首轮判断；不把资料不足包装成完成尽调；两份报告事实和限制一致；不编数字。当前仓库为编辑目标，不覆盖全局副本，不处理无关 tmp 内容。

## Review Focus

1. B 轮标签但无付费客户：按实际成熟度判断。
2. 一次性资本支出：不能仅现金除月消耗。
3. 未披露估值：不能用预测收入硬估价格。
4. 优先权与中间现金流：不能简单持股乘退出价值。
5. 省流版：不能删除关键条件或提升结论确信度。

## Tasks

- [x] 1. 基线：独立代理执行旧 skill 的合成 BP 请求，记录默认输出与批准设计的差距。阅读本地及外部参考，保留适用方法及明确取舍。
- [x] 2. 修改 SKILL.md 的默认路由与双报告交付；新增 references/research-workflow.md；扩展 stage-frameworks.md、diligence.md、valuation-and-terms.md；替换 report-template.md，保留更新判断能力。
- [x] 3. 同步 agents/openai.yaml、使用说明.md、README.md、CHANGELOG.md、method-sources.md；不添加重复技能入口。
- [x] 4. 独立代理在相同早期案例及成熟条款案例上执行新技能；审查双报告、数字、缺失信息处理。验证元数据、相对链接、公式、git diff --check；记录真实测试结果。
- [x] 5. 修正发现的问题，交付源文件及测试记录，明确未进行真实 BP/OCR 的端到端测试。

## Execution decisions

已获批准的设计授权本地实现；主代理连续实施，独立代理用于行为测试及最终审阅。不为流程选择再打断用户。现有工作区只编辑明确任务文件，不创建另一个工作树或覆盖全局安装。
