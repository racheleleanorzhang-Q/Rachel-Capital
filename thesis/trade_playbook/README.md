# Trade Playbook

## Purpose

The trade playbook defines execution rules for active positions and trading decisions.

It is separate from the investment thesis.

## Thesis vs. Playbook

- The thesis explains why a business deserves long-term ownership.
- The playbook explains how to execute buys, adds, trims, and trading discipline around that position.
- The thesis focuses on business quality, capital allocation, and long-term conviction.
- The playbook focuses on position structure, price zones, execution rules, and consistency.

## Scope

The trade playbook is for trading execution only.

It does not debate long-term investment logic.

If the long-term logic changes, update the relevant file in `thesis/`.

If the execution rules change, update the relevant file in `thesis/trade_playbook/`.

## Operating Rule

All trades should follow the playbook before execution.

The goal is to keep execution consistent across adds, reductions, and tactical trades.

## Reusable Rules

### 1. 市场分析顺序

所有交易执行之前，先按以下顺序完成判断：

1. 资金流向
2. 板块强弱
3. 个股评分
4. Trade Playbook Trigger
5. 组合仓位 / 资金效率
6. 执行

### 2. 资金流优先

任何个股交易之前必须先判断市场资金方向。

如果出现以下情况，应暂停低吸补仓：

- 资金持续流出
- 所属板块弱于基准指数
- 个股成交量放大下跌

### 3. 相对强弱

买入判断不能只看绝对价格。

如果指数明显下跌，而个股明显强于指数并率先止跌，可以提高交易机会评分。

反之，如果指数跌幅有限而个股明显弱于指数，应降低评分，不机械抄底。

### 4. 价格观察区不等于自动买卖

预设价格区只代表 Observation Zone。

不代表自动执行。

交易执行仍需结合：

- 分时止跌 / 止涨结构
- 成交量
- 板块资金
- 指数强弱
- Trade Playbook

### 5. 核心仓 / 交易仓分离

核心仓用于获取中期趋势收益，不因普通日内波动卖出。

交易仓用于日内T或波段T，用于锁定利润和降低持仓成本。

禁止为了做T而卖飞核心仓。

### 6. 日内T / 波段T统一标记

以后所有交易记录统一标记：

- 日内T（Intraday T）
- 波段T（Swing T）

并统一记录：

- Date
- Stock
- Action
- Price
- Quantity
- Strategy
- Status
- Reason
- Next Action
- Result（闭环后填写）

### 7. 利润兑现规则

对于已经连续上涨且接近明显压力位的交易仓，不要求卖在最高点。

达到压力区并出现以下任一信号时，可以分批兑现交易仓：

- 冲高回落
- 放量滞涨
- 长上影
- 板块资金转弱

### 8. 不追跌卖出规则

普通回调阶段，不因为价格快速下跌而追跌卖出。

只有当以下条件成立时，才升级为风险减仓：

- 趋势结构破坏
- 关键支撑有效跌破
- 板块 / 资金同步恶化
