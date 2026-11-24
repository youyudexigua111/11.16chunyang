### 什么是Hermes Agent?
Hermes Agent 是美国开源 AI 实验室 **Nous Research** 于 **2026 年 2 月 25 日**开源的自主 AI 智能体框架，MIT 协议、可自托管，官方口号是 "The agent that grows with you"（和你一起成长的智能体）。它主打的不是"更好的对话"，而是**长期在线、有持久记忆、能从经验里自己沉淀技能的"数字员工"**。
**Hermes Agent 属于 Harness 层，是 Harness 的一个具体开源实现（而且是"产品级"的实现），不是 LLM。** 它自己不带模型权重，模型是外接的、可一键切换的。
**Hermes 是 Harness（框架/运行时），当我们把它连上某个模型跑起来，得到的那个东西才叫 Agent。***Hermes 是一个"开箱即用的 Harness 发行版 / Agent 运行时产品"**，和 OpenClaw 是同一梯队的同类产品。"open source agent harness"。

## Hermes Agent和workbuddy的区别
**Hermes 是"自己搭、自己养"的开源智能体框架（Harness），WorkBuddy 是"装完就能替你干活、交付成品"的职场智能体工作台（产品）。**
**交付形态**：Hermes Agent 直接装在自己的服务器或者本地的常驻Agent，需要自己配置。Work Buddy是桌面客户端，免部署，装完就可以用。
**交互入口**：Hermes Agent：终端 TUI + 自己配消息网关。WorkBuddy：桌面端 + 打通微信、企微、QQ、飞书、钉钉等
**产出物导向不同**  
Hermes 的产出偏"工程物"：代码、脚本、配置、日志分析、自动化流程。WorkBuddy 的产出偏"业务物"：一份能直接发的方案文档、表格、PPT、报告，强调交付可验收结果而非建议。