# Asset Allocation

This document defines the long-term asset allocation framework for Rachel Capital.

It exists to keep asset-class decisions separate from single-stock decisions.

## Role

Rachel Capital remains a personal real-account long-term investment decision system.

The portfolio is no longer treated as equities-only. It now includes:

- equities
- gold accumulation
- cash

Asset allocation decisions should be made before individual position sizing decisions whenever the two are in tension.

## Long-Term Target Allocation

| Asset Class | Target Weight | Role |
| --- | ---: | --- |
| Technology | 30% | Long-term growth engine tied to AI, software, hardware, and industrial upgrading. |
| Consumer Internet | 30% | Core compounder bucket for high-quality platform and consumption assets. |
| Resource Equities | 15% | Cyclical and structural resource exposure through listed companies. |
| Gold (`积存金` / Gold ETF) | 10% | Portfolio stabilizer and macro hedge. |
| Banks / High Dividend | 10% | Defensive income and balance to growth concentration. |
| Cash | 5% | Optionality, defense, and rebalancing reserve. |

This is a long-term target architecture, not a requirement to force immediate one-step implementation.

## Gold Is A Separate Asset

Gold accumulation and Zijin Mining must not be merged into one bucket.

| Asset | Classification | Why It Is Separate |
| --- | --- | --- |
| Gold (`积存金` / Gold ETF) | Non-equity allocation asset | Used for hedging, stability, and long-term reserve behavior. |
| Zijin Mining | Equity position | Still depends on company execution, capital allocation, and commodity-cycle equity beta. |

Gold performance and Zijin Mining performance should be recorded, evaluated, and rebalanced separately.

## Gold Investment Rules

- Use long-term accumulation as the default approach.
- Add on meaningful pullbacks rather than on short-term upside spikes.
- Do not chase gold after rapid short-term rallies.
- Do not treat gold as a short-term trading instrument.
- Gold should primarily serve as a portfolio stabilizer and risk hedge.

## Rebalancing Rules

- Rebalancing should respond to material drift, not to noise.
- A rebalance is justified when asset-class weights drift far enough to distort portfolio role clarity.
- Rebalancing can also be triggered when thesis quality changes more than price changes.
- Any material asset-allocation change should be recorded in `decisions/Decision_Log.md`.

## Deployment Rules

- New cash should first be evaluated at the asset-class level, then at the individual-asset level.
- A strong single-stock thesis does not override the need for asset-class balance.
- Gold accumulation should be paced over time unless a clear macro dislocation justifies a larger buy.
- Cash should remain available when no asset class offers acceptable risk-adjusted deployment.

## Operating Rule

Before adding to any position, confirm:

1. Which asset class is being increased.
2. Whether that asset class is below, near, or above target weight.
3. Whether the move improves or weakens overall portfolio balance.
4. Whether the decision belongs in `Decision_Log.md`.
