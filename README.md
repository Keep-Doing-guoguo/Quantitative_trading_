# 量化交易金融知识库（股票 + 期货）

本项目用于在正式编码前，快速建立一套面向量化系统开发的金融知识底座。
目标不是覆盖所有金融理论，而是形成一套可直接映射到系统模块的知识结构。

## 项目定位

- 面向人群：计算机背景、准备做量化系统开发的学习者
- 市场范围：股票 + 期货
- 深度定位：开发可用深度（能支撑后续回测、风控、执行、监控开发）
- 文档风格：每个知识点都包含
  - 正式介绍（概念严谨）
  - 通俗介绍（直觉解释）
  - 开发映射（在代码里会用到哪里）

## 目录结构

```text
.
├── README.md
├── docs
│   ├── 00-roadmap.md
│   ├── 01-market-basics
│   │   └── overview.md
│   ├── 02-instruments
│   │   └── overview.md
│   ├── 03-trading-mechanics
│   │   └── overview.md
│   ├── 04-risk-and-money
│   │   └── overview.md
│   ├── 05-portfolio-and-metrics
│   │   └── overview.md
│   ├── 06-strategy-finance-core
│   │   └── overview.md
│   ├── 07-real-world-constraints
│   │   └── overview.md
│   ├── 08-glossary.md
│   └── 09-dev-mapping.md
└── templates
    └── chapter-template.md
```

## 推荐学习顺序（4 周）

1. 第 1 周：`docs/01-market-basics/overview.md` + `docs/02-instruments/overview.md`
2. 第 2 周：`docs/03-trading-mechanics/overview.md`
3. 第 3 周：`docs/04-risk-and-money/overview.md` + `docs/05-portfolio-and-metrics/overview.md`
4. 第 4 周：`docs/06-strategy-finance-core/overview.md` + `docs/07-real-world-constraints/overview.md`
5. 收尾：`docs/08-glossary.md` + `docs/09-dev-mapping.md`

## 使用方式

1. 先按路线图学习，再按模板补充你自己的理解。
2. 每看完一个知识点，必须回答对应自测题。
3. 将关键参数整理到你后续代码配置中（例如保证金率、手续费、止损阈值、滑点模型参数）。

## 质量标准（文档验收）

- 每个主题文档包含模板 8 字段
- 每个主题文档包含正式版 + 通俗版
- 每个主题文档包含开发映射
- 每个主题文档有 3 道自测题与答案
- 术语统一使用 `docs/08-glossary.md`
