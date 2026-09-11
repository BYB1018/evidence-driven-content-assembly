---
name: evidence-driven-content-assembly
description: |
  把真实经历或可信来源装配成可审计的视频/图文生产包，保留语音思路、资料清单、大纲、Demo、草稿与拍摄清单。适用于 AI 辅助知识内容和案例视频；不用于一键洗稿、无来源电影解说或全自动发布。Triggers: content workflow, video script, 内容生产, 视频脚本, 资料核验。
metadata:
  source: "24 条 Bilibili AI 搞钱视频证据包：视频 06、12；用户方向 8、9"
  tags: "content, evidence, video"
---
# 证据中间产物驱动的内容装配线

## R — 原文（Reading）
> 先做一个最小内容 Skill：输入一个真实搞钱实验，输出资料清单、大纲、缺失证据和拍摄清单。不要一上来自动生成完整视频。
>
> — 视频 12 分析，BV12hE16WEw9

## I — 方法论骨架（Interpretation）
可靠内容不从“一键成稿”开始，而从两种约束开始：真实语音约束观点，可信来源约束事实。AI 的主要职责是把过程装配成可检查的中间产物：问题、语音整理、资料清单、来源筛选、大纲、Demo、草稿、画面与拍摄清单。每一步都保留证据和缺口，最后由人核实事实、补个人判断并自然口述。这样既能提高速度，也能防止空泛、洗稿和无法追溯。

## A1 — 资料中的应用（Past Application）
- **半年两万粉流程**：语音输入、AI 整理、Demo/PPT、自然口述、剪辑和多平台发布分段完成。
- **知识视频 Skill**：主题、检索、来源筛选、大纲、依来源写作、格式化、文风分析与人工修改被拆成独立步骤。

## A2 — 触发场景（Future Trigger）
1. 用户要围绕 AI 搞钱实验持续录视频或发社媒。
2. 用户要制作需要事实核验的知识视频、教程或案例复盘。
3. 用户想把研究、脚本、Demo 和拍摄清单做成可复用流程。

语言信号："帮我做视频脚本"、"内容生产流水线"、"怎么避免 AI 胡写"、"evidence-backed content"、"content assembly"。

与相邻 Skill 的区分：本 Skill 负责从证据到制作包；`result-scenario-content-positioning` 决定选题和表达角度；`risk-tiered-human-approval` 约束自动发布与外部动作。

## E — 可执行步骤（Execution）
1. **锁定一手材料**：获取用户语音/经历、原始数据、可信来源和许可可用的视觉材料；把事实、主张、推断分栏。
   - 完成标准：核心事实至少有来源，个人观点明确标为观点。
2. **分层装配**：依次产出问题句、资料清单、来源筛选、大纲、Demo/示例、草稿、画面与拍摄清单；保留缺失证据。
   - 完成标准：草稿每个关键事实可回链，中间产物可单独审查。
3. **人工定稿**：核对版权、事实和隐私；改成用户自然语言并口述；发布前明确人工确认。
   - 判停条件：来源无法核验、素材无授权或主题依赖侵权片段时，不生成可发布成品。

## B — 边界（Boundary）
- 不支持搬运电影素材、规避版权识别或把洗稿包装成原创。
- 不把 AI 草稿当最终事实，也不自动发布。
- 失败模式：只保留最终稿；正文无来源；产品宣传压过问题；批量生成空泛内容。
- 盲点：不同平台的时长和视觉节奏仍需另行适配，本 Skill 不替代剪辑与版权判断。

## 相关 Skills
- depends-on: `evidence-backed-capability-portfolio`（案例型内容时）
- contrasts-with: `result-scenario-content-positioning`
- composes-with: `service-product-content-flywheel`, `risk-tiered-human-approval`

## 审计信息
- 验证通过：V1 ✓ / V2 ✓ / V3 ✓
- 测试通过率：100%（6/6，独立盲测）
- 来源单元：v06
- 蒸馏时间：2026-08-24
