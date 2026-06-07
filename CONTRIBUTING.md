# Contributing — Workflow for the AI Agents

This repo is filled in by AI agents, one year at a time. This is the operating
procedure. (Human maintainers: same rules apply.)

---

## Before you touch a year

Read, in order:

1. [`docs/methodology.md`](docs/methodology.md) — the philosophical constitution.
2. [`docs/agents/`](docs/agents/) — your persona and the other two.
3. [`docs/debate-protocol.md`](docs/debate-protocol.md) — the turn-by-turn flow.
4. [`docs/event-selection.md`](docs/event-selection.md) and
   [`docs/connections.md`](docs/connections.md).
5. [`docs/depth-rubric.md`](docs/depth-rubric.md) — the bar you'll be judged on.

---

## Writing one year

1. **Confirm the carry-forward.** Read the previous year's *Handoff* section. If
   the previous year doesn't exist yet, write years in chronological order — the
   continuity contract depends on it.
2. **Copy the template.** `templates/YEAR_TEMPLATE.md` →
   `years/<decade>/YYYY.md`.
3. **Select the six events** (`docs/event-selection.md`) and log why.
4. **Run the debate** through all phases (`docs/debate-protocol.md`).
5. **Synthesize** — preserve disagreement; don't fake a verdict.
6. **Write the handoff** — specific threads, reusing stable thread names.
7. **Self-check** against `docs/depth-rubric.md`. Fix every non-negotiable failure.
8. **Update the decade README** status row (and the macro-arc once the decade fills out).

---

## Order of operations

- **Chronological by default.** 1800 → 1801 → … so each year can honor the
  continuity contract.
- A decade can be drafted by one agent-trio start to finish, *then* the
  Cartographer writes that decade's macro-arc.

---

## Continuity contract (do not break)

> A year's **Handoff** must equal the next year's **Carry-Forward**, thread for
> thread. Reuse stable thread names (e.g. `thread: the slavery-expansion
> contradiction`) so a thread can be followed across decades.

---

## Style & integrity

- Seminar voice, not textbook ([`methodology.md`](docs/methodology.md) §10).
- Steelman before you strike — always.
- Label **Fact / Interpretation / Speculation**; flag contested facts; cite sources.
- No connection inflation, no counter-myth, no determinism creep.
- The destination of every thread is the **present-day United States**.

---

## Commit conventions (suggested)

- `year(1803): draft debate + synthesis`
- `decade(1800-1809): macro-arc`
- `docs: refine depth rubric`

Keep one year per commit where practical, so the river is easy to review.
