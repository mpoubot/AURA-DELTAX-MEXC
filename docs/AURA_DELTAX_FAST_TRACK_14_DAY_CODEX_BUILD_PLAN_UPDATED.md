# AURA-DELTAX Fast-Track 14-Day Codex Build Plan — UPDATED

Updated 5 September 2026.

## Purpose
Integrate existing AURA, Deltax, Deltax V2 and competition implementations quickly. Do not rewrite the platform.

## Day 1
Read-only audit of AURA, Deltax, Deltax V2 and every populated competition source folder. Build a KEEP / ADAPT / TAKE / REJECT / BUILD matrix using code, tests and presentation evidence.

## Day 2–14
1. Shared typed contracts
2. Deterministic Risk Gate + ABSTAIN
3. Position/Exit Manager
4. News/events/sentiment/analyst/rotation
5. Crypto regime/rotation
6. MEXC paper adapter
7. PostgreSQL + decision ledger
8. Reconciliation + restart recovery
9. OOS/walk-forward/permutation/cost/MAE-MFE validation
10. End-to-end paper cycle
11. Adversarial testing
12. Stabilization
13. Paper release candidate + demo evidence

## Position/Exit minimum
- Protective stop persisted before activation.
- Long trailing stop never decreases; short trailing stop never increases.
- TP and partial exits are deterministic and persisted.
- Every exit has a structured reason.
- Capture MAE/MFE and R-multiple.

## Competition evidence
Leaderboard hearts are community engagement, not technical judge scores. Top Builder points are a separate platform metric. Verify competitor code before adopting features.

## Codex rules
FIND → COMPARE → REUSE → ADAPT → TEST → INTEGRATE.

AI/LLM may research and propose but never directly authorize broker execution. Risk Authority is deterministic and fail-closed. ABSTAIN/REJECT is first-class. Unknown/stale critical data causes refusal. Existing MEXC live workflow is protected. Live trading is disabled by default.

## Success
A paper trade is reproducible from Market State → Proposal → Risk → Position/Exit → ExecutionIntent → MEXC → Fills → Reconciliation → PostgreSQL/Ledger.
