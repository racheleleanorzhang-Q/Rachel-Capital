# Dashboard

This file now routes current portfolio review to the dedicated portfolio dashboard.

This is the single entry point for current portfolio review in Rachel Capital.

Last Updated: `2026-08-07`

## Summary

| Field | Value | Notes |
| --- | ---: | --- |
| Total Assets | ¥466,334 | Updated after the confirmed `2026-08-07` Zijin Mining T-sell of `400股` @ `34.63元`; the remaining recorded Zijin position is marked at the same transaction price, and transaction fees are still excluded. |
| Cash | ¥98,852 | Prior synchronized cash baseline plus the confirmed RMB sale proceeds of `¥13,852`; transaction fees are not yet deducted. |
| Stock Assets | ¥367,482 | Recomputed after reducing Zijin Mining from the recorded `1,800股` to `1,400股`; the remaining position is marked at `34.63元/股`, while the July 28 Inspur starter position is still tracked separately below. |
| Cash Ratio | 21.2% | Cash / total assets. |
| Equity Exposure | 78.8% | Stock assets / total assets. |
| Number of Holdings | 7 | Current live holdings, including the new Inspur starter position. |
| Largest Position | 美团 (`33.5%` of total assets) | Continues as the first portfolio repair engine. |
| Biggest Unrealized Loss | 理想汽车 (`-¥105,000`) | Still the largest unresolved drawdown. |
| Best Performer | 紫金矿业（累计收益待校准） | Zijin remains the strongest known profit contributor, but the cumulative P/L should be refreshed in the next full-account reconciliation. |

## Holdings

| Holding | Market Value | Accumulated P/L | Return Rate | Weight In Total Assets | Role | Current View |
| --- | ---: | ---: | ---: | ---: | --- | --- |
| 美团 | ¥156,000 | -¥39,000 | -20% | 33.5% | 核心修复仓 | Continue holding as the first repair engine and keep using T-trading to lower cost. |
| 理想汽车 | ¥70,000 | -¥105,000 | -60% | 15.0% | 观察修复仓 | Hold only; no active averaging down until thesis quality improves. |
| 三花智控 | ¥31,000 | -¥8,400 | -20% | 6.6% | 制造成长仓 | Position size has declined; there is no thesis change at this stage. |
| 紫金矿业 | ¥48,482 | 待下一次全账户对账统一校准 | 待校准 | 10.4% | 资源配置仓 | 当前记录持有 `1,400股`；`2026-08-07` 以 `34.63元` 卖出 `400股` 完成一次做T卖出，继续保留核心仓位并等待后续回补机会。 |
| 北京银行 | ¥25,000 | +¥1,700 | +7% | 5.4% | 防御收益仓 | Continue holding as a defensive yield balance position. |
| 腾讯控股 (`0700.HK`) | ¥37,000 | -¥1,000 | -3% | 7.9% | 第二增长引擎 | Base position is live; combine trend confirmation, phased adds, and future T-trading rather than chasing strength. |
| 浪潮信息 (`000977.SZ`) | 建仓金额 ¥16,440 | 待更新 | 待更新 | 待更新 | 第二增长引擎 / 初始观察仓 | 持有中；`2026-07-28` 以 `82.20元` 买入 `200股`，当前仅作为初始观察仓/试仓，不属于做T交易。 |

## Trading Tranche Status

| Holding | Status | Recent Trade | Strategy | Next Step |
| --- | --- | --- | --- | --- |
| 美团 | Waiting Buy Back | `2026-08-03` 卖出 `200股` @ `93.35 HKD` | 波段T（Swing T） | 等待 `91~92` 附近观察；`90` 附近优先买回。 |
| 腾讯控股 (`00700.HK`) | Ready For Next T | `2026-08-03` 卖出 `100股` @ `490.00 HKD` | 波段T（Swing T） | `470~475` 开始观察；`460~465` 优先建立交易仓。 |
| 三花智控 | Waiting Buy Back | 卖出 `300股` @ `26.90` | 波段T（Swing T） | `26.2` 附近开始观察；`25.3~25.6` 优先买回。 |
| 紫金矿业 | Waiting Buy Back | `2026-08-07` 卖出 `400股` @ `34.63元` | 波段T（Swing T） | 等待新的回补价格区与承接信号；在形成明确回调前不追高买回。 |

## Current Allocation

| Asset Class | Current Weight | Target Weight | Gap |
| --- | ---: | ---: | ---: |
| Technology | 29.6% | 30.0% | -0.4% |
| Consumer Internet | 33.5% | 30.0% | +3.5% |
| Resource Equities | 10.4% | 15.0% | -4.6% |
| Gold (`积存金` / Gold ETF) | 0.0% | 10.0% | -10.0% |
| Banks / High Dividend | 5.4% | 10.0% | -4.6% |
| Cash | 21.2% | 5.0% | +16.2% |

## Investment Committee Comment

- 腾讯正式进入组合，成为第二增长引擎首个核心资产。
- 美团继续作为组合第一修复引擎，做T策略继续有效。
- 紫金矿业完成一次 `400股` 做T卖出，兑现阶段性收益。
- 紫金矿业长期投资逻辑保持不变，继续保留核心仓位。
- 当前继续执行“长期持有 + 做T优化成本”策略。
- 现金提升至 `¥98,852`，组合流动性有所改善。
- 理想汽车仍为组合最大风险来源，维持观察策略。

## Pending Decisions

| Item | Status | Why It Is Pending |
| --- | --- | --- |
| Direct gold accumulation first entry | Open | Gold target remains unfilled even after the latest portfolio repair. |
| Li Auto review | Open | It remains the biggest unrealized loss and weakest current role. |
| Meituan / Tencent / Sanhua / Zijin T-trading execution | Open | The active trading tranches should keep improving capital efficiency without weakening the core holdings or forcing high-price re-entry. |
| Second growth engine scaling | Open | Tencent is now the first live growth-engine core asset; the next decision is how to add and trade it without weakening portfolio liquidity. |

## Source Documents

- `account/Current.md`
- `weekly/2026/W30.md`
- `decisions/Decision_Log.md`
- `thesis/trade_playbook/Current_T_Trading_Status.md`
- `strategy/Asset_Allocation.md`
- `watchlist/Watchlist.md`
- `institution-tracker/README.md`
