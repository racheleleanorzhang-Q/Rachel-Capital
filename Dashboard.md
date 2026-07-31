# Dashboard

This file now routes current portfolio review to the dedicated portfolio dashboard.

This is the single entry point for current portfolio review in Rachel Capital.

Last Updated: `2026-07-31`

## Summary

| Field | Value | Notes |
| --- | ---: | --- |
| Total Assets | ¥480,500 | Latest synchronized portfolio snapshot after the July 31 Zijin Mining T-trade sell execution. |
| Cash | ¥63,640 | Cash increased after Zijin Mining completed one T-trade sell leg and the proceeds returned to cash. |
| Stock Assets | ¥416,860 | Stock assets declined after the completed Zijin Mining T-trade lot was sold back into cash. |
| Cash Ratio | 13.2% | Cash / total assets. |
| Equity Exposure | 86.8% | Stock assets / total assets. |
| Number of Holdings | 7 | Current live holdings. |
| Largest Position | 美团 (`34.8%` of total assets) | Continues as the core repair position. |
| Biggest Unrealized Loss | 理想汽车 (`-¥95,000`) | Still the largest unresolved drawdown. |
| Best Performer | 紫金矿业 (`+¥12,000`) | Continues as the largest current profit contributor. |

## Holdings

| Holding | Asset Class | Market Value | Accumulated P/L | Return Rate | Weight In Total Assets | Role | Current View |
| --- | --- | ---: | ---: | ---: | ---: | --- | --- |
| 美团 | Consumer Internet | ¥167,000 | -¥28,000 | -14.4% | 34.8% | 核心修复仓 | Continue holding as the first repair engine and keep using T-trading to lower cost. |
| 理想汽车 | Technology | ¥80,000 | -¥95,000 | -54.3% | 16.6% | 观察修复仓 | Hold only; no active averaging down until thesis quality improves. |
| 腾讯控股 (`0700.HK`) | Consumer Internet | ¥40,000 | +¥2,000 | +5.3% | 8.3% | 第二增长引擎 | Tencent has turned profitable and the second growth engine is starting to prove itself in live capital. |
| 紫金矿业 | Resource Equities | ¥51,360 | +¥12,000 | +26.1% | 10.7% | 资源配置仓 | Continue holding as the portfolio stabilizer while executing disciplined T-trading on the trading tranche. |
| 浪潮信息 (`000977.SZ`) | Technology | ¥27,500 | -¥5,000 | -15.4% | 5.7% | 第二增长引擎（AI） | Inspur is now in the live portfolio as an important AI observation target; keep position sizing cautious. |
| 北京银行 | Banks / High Dividend | ¥26,000 | +¥2,000 | +8.3% | 5.4% | 防御收益仓 | Continue holding as a defensive yield balance position. |
| 三花智控 | Technology | ¥25,000 | -¥8,000 | -24.2% | 5.2% | 制造成长仓 | Continue holding while using partial T-trading to improve capital efficiency and lower cost. |

## Current Allocation

| Asset Class | Current Weight | Target Weight | Gap |
| --- | ---: | ---: | ---: |
| Technology | 27.6% | 30.0% | -2.4% |
| Consumer Internet | 43.1% | 30.0% | +13.1% |
| Resource Equities | 10.7% | 15.0% | -4.3% |
| Gold (`积存金` / Gold ETF) | 0.0% | 10.0% | -10.0% |
| Banks / High Dividend | 5.4% | 10.0% | -4.6% |
| Cash | 13.2% | 5.0% | +8.2% |

Allocation mapping: `Technology = 理想汽车 + 浪潮信息 + 三花智控`; `Consumer Internet = 美团 + 腾讯控股`.

## Investment Committee Comment

- 总资产维持在约48万元水平，组合继续修复。
- 腾讯已由浮亏转为盈利，第二增长引擎开始发挥作用。
- 浪潮信息已进入组合，作为AI方向的重要观察标的。
- 紫金矿业完成一笔标准做T闭环（31.30 买入 → 33.20 卖出），符合既定交易纪律，成功锁定短线收益，同时保留核心底仓。
- 现金回升至约6.36万元，组合短线灵活性有所改善，但新增仓位仍需保持谨慎。

## Pending Decisions

| Item | Status | Why It Is Pending |
| --- | --- | --- |
| Direct gold accumulation first entry | Open | Gold target remains unfilled even after the latest portfolio repair. |
| Li Auto review | Open | It remains the biggest unrealized loss and weakest current role. |
| Meituan / Zijin / Sanhua T-trading execution | Open | Three active repair or cost-reduction positions still require disciplined execution quality and capital protection. |
| Second growth engine scaling | Open | Tencent has turned profitable and Inspur is now live, but future adds must stay consistent with liquidity constraints. |

## Source Documents

- `account/Current.md`
- `weekly/2026/W30.md`
- `decisions/Decision_Log.md`
- `strategy/Asset_Allocation.md`
- `watchlist/Watchlist.md`
- `institution-tracker/README.md`
