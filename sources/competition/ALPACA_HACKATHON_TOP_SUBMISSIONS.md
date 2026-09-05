# Alpaca AI Trading Agents Hackathon — Competition Investigation Targets

**Purpose:** Candidate competition projects to audit before selecting functionality for AURA-DELTAX.

**Rule:** These are investigation targets, not code dependencies. Do not copy or merge external code until its repository/source, license, architecture, tests, and implementation quality have been reviewed.

## Current Top Submissions shown on the Lablab live page

1. **Alpha Hunter — Autonomous AI Trading Scientist** — crazyxyz
2. **TradePilot AI — Autonomous AI Trading Agent** — TradePilot
3. **QASIX-Alpaca AI Trading Agent** — QASIX
4. **AlphaPilot AI** — Quantum Coders
5. **SentryTheta AI — Autonomous Options Trading Agent** — SentryTheta AI
6. **VegaGuard: Auditable AI Options Agent** — OSTER
7. **Elite-Bot: Multi-Asset AI Trading Hub** — Team_Bhairava

## Why each is included

### 1. Alpha Hunter
Investigate especially:
- autonomous quantitative research loop
- strategy discovery and validation
- out-of-sample / robustness analysis
- adversarial strategy challenge
- Edge Score / strategy ranking
- adaptive capital allocation
- portfolio risk and correlation
- deterministic risk layer between AI and execution
- adaptive trailing protection
- broker reconciliation

### 2. TradePilot AI
Investigate especially:
- autonomous end-to-end trading loop
- live market analysis
- AI decision architecture
- risk management
- automated position protection
- Alpaca execution
- monitoring/dashboard design

### 3. QASIX
Investigate especially:
- options strategy selection
- covered calls / cash-secured puts
- deterministic risk manager
- deterministic exit engine
- logging of both approved and blocked decisions
- transparency/auditability

### 4. AlphaPilot AI
Investigate especially:
- technical signal stack
- confidence scoring
- deterministic option-contract ranking
- entry safety checks
- existing-position detection
- duplicate-order protection
- quote validation
- position limits
- continuous position monitoring
- stop-loss / take-profit management

### 5. SentryTheta AI
Investigate especially:
- multi-agent separation of market analysis and volatility strategy
- news/sentiment ingestion
- option-chain analysis
- deterministic Risk Officer
- position premium cap
- daily drawdown circuit breaker
- automated stop-loss / take-profit harvesting
- Copilot vs Autopilot operating modes
- persistent state
- MCP integration

### 6. VegaGuard
Investigate especially:
- auditable options lifecycle
- ETF scanning
- defined-risk debit spreads
- deterministic risk gates
- Alpaca MCP execution
- position monitoring
- decision/audit trail

### 7. Elite-Bot
Investigate especially:
- multi-asset architecture
- crypto + equities + FX coverage
- multi-agent validation
- statistical mean reversion
- momentum strategies
- large-universe scanning
- news/event awareness

## Additional high-value competition projects discovered during research

These are not necessarily in the screenshot's top-seven list, but are strong candidates for the same investigation because their published descriptions contain potentially valuable risk/execution patterns:

- **BABIL** — human-in-the-loop, fixed AI proposal schema, deterministic G0-G5 risk gates, immutable authorization/consumption/pre-execution chain, fail-closed execution, static security tests.
- **Option Alpha Agent** — defined-risk spreads/iron condors with explicit checks and reasons for trade/watch/decline.
- **Magno** — deterministic risk gates and continuous dynamic delta-hedging loop.
- **PrintRunner** — earnings-season options agent, deterministic verticals/condors, hard gates, hash-chained journal, cost breaker, hypothesis graph.
- **REGRET** — defined-risk credit spreads with deterministic hard risk gates.
- **KRYPTA** — thesis + adversarial invalidation + deterministic risk gate + human approval.
- **QuantNova** — multi-agent research/strategy/risk pipeline with deterministic veto and dry-run/backtesting.

## AURA-DELTAX investigation matrix

For every candidate implementation, compare:

- Market data
- News
- Sentiment
- Analyst expectations
- Earnings/events
- Sector/ETF rotation
- Crypto regime/rotation
- Signal generation
- Strategy research
- Adversarial validation
- Position sizing
- Risk Gate
- Hard stop
- Trailing stop
- Take profit
- Partial exits
- Time exits
- Signal invalidation
- Emergency exit
- Order lifecycle
- Fill handling
- Duplicate protection
- Reconciliation
- Restart recovery
- Kill switch
- Database/state persistence
- Decision ledger
- Backtesting
- Walk-forward testing
- Permutation/surrogate testing
- MAE/MFE
- Transaction-cost modeling
- Monitoring/dashboard
- Explainability/auditability

## Important

The Lablab leaderboard is a community-facing ranking and should **not** be treated as proof that a project has the best technical implementation. The purpose of this file is to make the strongest/most visible submissions easy to investigate systematically.

Source: Lablab Alpaca AI Trading Agents Hackathon live/recap pages and individual submission descriptions, reviewed September 2026.
