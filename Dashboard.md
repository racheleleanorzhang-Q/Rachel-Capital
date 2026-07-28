# Dashboard

This file now routes current portfolio review to the dedicated portfolio dashboard.

This is the single entry point for current portfolio review in Rachel Capital.

Last Updated: `2026-07-28`

## Summary

| Field | Value | Notes |
| --- | ---: | --- |
| Total Assets | ¥460,000 | Latest synchronized portfolio baseline from the July 24 holdings snapshot; the July 28 Inspur starter position is recorded below, while full account totals remain pending the next reconciliation. |
| Cash | ¥85,000 | Cash baseline remains unchanged here because the latest reliable post-trade cash figure and actual transaction fees are not yet confirmed. |
| Stock Assets | ¥375,000 | July 24 synchronized stock-asset baseline; the July 28 Inspur starter position is recorded as a new holding, not yet folded into the next full account snapshot. |
| Cash Ratio | 18.5% | Cash / total assets. |
| Equity Exposure | 81.5% | Stock assets / total assets. |
| Number of Holdings | 7 | Current live holdings, including the new Inspur starter position. |
| Largest Position | 美团 (`33.9%` of total assets) | Continues as the first portfolio repair engine. |
| Biggest Unrealized Loss | 理想汽车 (`-¥105,000`) | Still the largest unresolved drawdown. |
| Best Performer | 紫金矿业 (`+¥10,000`) | Largest current profit contributor. |

## Holdings

| Holding | Market Value | Accumulated P/L | Return Rate | Weight In Total Assets | Role | Current View |
| --- | ---: | ---: | ---: | ---: | --- | --- |
| 美团 | ¥156,000 | -¥39,000 | -20% | 33.9% | 核心修复仓 | Continue holding as the first repair engine and keep using T-trading to lower cost. |
| 理想汽车 | ¥70,000 | -¥105,000 | -60% | 15.2% | 观察修复仓 | Hold only; no active averaging down until thesis quality improves. |
| 三花智控 | ¥31,000 | -¥8,400 | -20% | 6.7% | 制造成长仓 | Position size has declined; there is no thesis change at this stage. |
| 紫金矿业 | ¥56,000 | +¥10,000 | +22.5% | 12.2% | 资源配置仓 | Continue holding as the portfolio stabilizer; add only if thesis stays intact and pullback improves entry. |
| 北京银行 | ¥25,000 | +¥1,700 | +7% | 5.4% | 防御收益仓 | Continue holding as a defensive yield balance position. |
| 腾讯控股 (`0700.HK`) | ¥37,000 | -¥1,000 | -3% | 8.0% | 第二增长引擎 | Base position is live; combine trend confirmation, phased adds, and future T-trading rather than chasing strength. |
| 浪潮信息 (`000977.SZ`) | 建仓金额 ¥16,440 | 待更新 | 待更新 | 待更新 | 第二增长引擎 / 初始观察仓 | 持有中；`2026-07-28` 以 `82.20元` 买入 `200股`，当前仅作为初始观察仓/试仓，不属于做T交易。 |

## Current Allocation

| Asset Class | Current Weight | Target Weight | Gap |
| --- | ---: | ---: | ---: |
| Technology | 30.0% | 30.0% | 0.0% |
| Consumer Internet | 33.9% | 30.0% | +3.9% |
| Resource Equities | 12.2% | 15.0% | -2.8% |
| Gold (`积存金` / Gold ETF) | 0.0% | 10.0% | -10.0% |
| Banks / High Dividend | 5.4% | 10.0% | -4.6% |
| Cash | 18.5% | 5.0% | +13.5% |

## Investment Committee Comment

- 腾讯正式进入组合，成为第二增长引擎首个核心资产。
- 美团继续作为组合第一修复引擎，做T策略继续有效。
- 紫金矿业继续承担组合稳定器角色。
- 现金下降至 `¥85,000`，但仍保持良好的资金灵活性。
- 理想汽车仍为组合最大风险来源，维持观察策略。

## Pending Decisions

| Item | Status | Why It Is Pending |
| --- | --- | --- |
| Direct gold accumulation first entry | Open | Gold target remains unfilled even after the latest portfolio repair. |
| Li Auto review | Open | It remains the biggest unrealized loss and weakest current role. |
| Meituan T-trading execution | Open | The core holding should keep lowering cost without weakening the base position. |
| Second growth engine scaling | Open | Tencent is now the first live growth-engine core asset; the next decision is how to add and trade it without weakening portfolio liquidity. |

## Source Documents

- `account/Current.md`
- `weekly/2026/W30.md`
- `decisions/Decision_Log.md`
- `strategy/Asset_Allocation.md`
- `watchlist/Watchlist.md`
- `institution-tracker/README.md`
