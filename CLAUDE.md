# CLAUDE.md — Fintrac
Canadian AML/FINTRAC compliance tooling.

---

## Global Standards

- Global rules: `brainframe-public/GLOBAL_RULES.md` — load at session start
- Style rules: `brainframe-public/STYLE_RULES.md` — load at session start
- Token optimization: `brainframe-public/docs/TOKEN_OPTIMIZATION.md` — load on demand
- Tool routing: `brainframe-public/MODEL_ROUTING.md` — load on demand

## Token Optimization

Priority: quality > speed > cost. Default model: Sonnet 4.6. Escalate to Opus for architecture/deep reasoning. Downgrade to Haiku for structured/data ops. Full standard: `brainframe-public/docs/TOKEN_OPTIMIZATION.md`.

## Decision States

- CONFIRMED — locked, verified
- PROVISIONAL — working assumption, not validated
- SUPERSEDED — replaced by newer decision

Always tag decisions. Never let state change silently.

## Open Items

Unresolved items → KNOWN_UNKNOWNS.md. Never drop silently. If deferred twice → escalate.

---

_Stub created April 2026. Expand with project-specific context as needed._
