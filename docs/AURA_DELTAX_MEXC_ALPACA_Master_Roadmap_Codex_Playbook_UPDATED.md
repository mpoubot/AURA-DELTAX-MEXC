# AURA-DELTAX MEXC + Alpaca Master Roadmap & Codex Playbook — UPDATED

Updated 5 September 2026.

## Architecture
One shared AURA Core: Intelligence → Market State → TradeProposal → deterministic Risk Authority → Position/Exit Manager → ExecutionIntent → broker adapter → reconciliation → PostgreSQL + decision ledger.

## Best-of-best source strategy
- AURA: canonical core, research and validation.
- Deltax/Deltax V2: multi-feed context, trading-cycle and position/exit candidates.
- EdgeStack: walk-forward and permutation/surrogate validation.
- Aegis/AEGIS-Q: deterministic gates, fill verification, recovery and testing.
- BABIL: fail-closed G0–G5 governance and security/testing patterns.
- Other competition projects: selectively adopt verified capabilities.

## Critical priorities
ABSTAIN; freshness/spread/slippage vetoes; order/fill/position/account reconciliation; restart recovery; autonomous exits; replayable decision journal; instrument-aware sizing; OOS/walk-forward/permutation/cost/MAE-MFE validation.

## MEXC first
Build crypto spot/futures paper execution through a new adapter. Do not modify the existing working MEXC live workflow.

## Alpaca second
Reuse the same core for stocks, ETFs, futures and options. Add broker/instrument-specific adapters and multi-leg options reconciliation.

## Codex guardrails
AI never directly calls broker endpoints. Risk is fail-closed. Protective stops cannot loosen. Unknown/stale critical data causes ABSTAIN/REJECT. Human review is required for risk, execution, reconciliation, migration and live-enablement changes.

## Competition evidence
Project-specific CODE_SOURCES.md and PRESENTATIONS.md accompany supplied source packages. Presentation claims are not implementation proof until verified in code or reliable demos.

## Live gate
Paper RC → sustained stability → research validation → adversarial/failure tests → reconciliation verification → security review → explicit human approval → small controlled live capital.
