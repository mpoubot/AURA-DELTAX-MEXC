# Competition Code Sources

This file records the exact code repositories to inspect for the AURA-DELTAX investigation.

**Important:** These are external source repositories. They are intentionally referenced rather than blindly copied into AURA-DELTAX. Before importing third-party source code, verify the repository license, attribution requirements, ownership, and implementation quality. Codex can inspect these repositories directly when access is available.

## Top submissions

| Project | GitHub source | Investigation focus |
|---|---|---|
| Alpha Hunter — Autonomous AI Trading Scientist | https://github.com/irishkiwi007/hackathon-SUMANSHAKTI-alpaca | Research loop, OOS validation, adversarial testing, Edge Score, adaptive allocation, risk, trailing protection, reconciliation |
| TradePilot AI — Autonomous AI Trading Agent | https://github.com/irishkiwi007/hackathon-divine308-Tradepilot | End-to-end agent loop, market analysis, risk, position protection, Alpaca execution |
| QASIX-Alpaca AI Trading Agent | https://github.com/irishkiwi007/hackathon-isianioui-Alpaca-AI-Trading-Agent | Covered calls/CSPs, deterministic risk manager, exit engine, approval/blocked logging |
| AlphaPilot AI | https://github.com/irishkiwi007/hackathon-ibrahimjatt1313-prog-AlphaPilot | Signal confidence, option ranking, quote validation, duplicate protection, position monitoring, SL/TP |
| SentryTheta AI | https://github.com/irishkiwi007/hackathon-abdullasibghat-SentryTheta-AI | News/sentiment, option-chain analysis, Risk Officer, position cap, drawdown breaker, SL/TP harvesting, state persistence |
| VegaGuard | https://github.com/irishkiwi007/hackathon-arywk40-hue-alpaca | ETF scanning, defined-risk spreads, deterministic risk gates, lifecycle monitoring, audit trail |
| Elite-Bot | https://github.com/irishkiwi007/hackathon-rudrakshmala-legendary-octo-invention | Crypto + equities, statistical strategies, multi-agent validation, news/sentiment, dynamic trade management |

## Additional high-value candidates

These should also be audited if their source repositories are available:

- BABIL — deterministic G0-G5 gates, explicit human approval, fail-closed execution, kill switch.
- Magno — deterministic risk gates and continuous delta-hedging.
- PrintRunner — earnings-driven options strategy, hard gates, cost breaker, hash-chained journal.
- REGRET — defined-risk credit spreads and deterministic hard risk gates.
- KRYPTA — thesis + adversarial invalidation + deterministic risk gate + human approval.
- QuantNova — multi-agent research/strategy/risk pipeline, deterministic veto, dry-run/backtesting.

## Recommended audit order

1. Alpha Hunter
2. SentryTheta AI
3. TradePilot AI
4. AlphaPilot AI
5. QASIX
6. VegaGuard
7. Elite-Bot
8. BABIL / KRYPTA / QuantNova / other strong risk-governance implementations

## Rule for AURA-DELTAX

Do not merge a project wholesale. For each capability use:

**FIND → COMPARE → REUSE → ADAPT → TEST → INTEGRATE**

The target is one authoritative implementation per capability, not a collection of competing bots.
