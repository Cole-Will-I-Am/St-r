# St-r — A Three-Mind History of the Modern World (1800 → Present)

> A structured arena where **three AI interpretive personas** debate and discuss
> world and U.S. history, **one year at a time, from 1800 to the present day**.

This repository is a **blueprint**. It contains no finished history yet — it
contains the *scaffolding*, *rules*, *roles*, and *templates* that AI agents will
later use to fill in each year. Think of it as an empty stadium with the field
chalked, the rules posted, and the seats labeled — waiting for the players.

---

## The Premise

For every year from **1800 to the present**, three AI personas examine:

- **3 United States events** and **3 world events** (six total per year).
- **How those six events connect** to each other within the year.
- **How the year informs and reshapes the next** — the causal handoff forward.
- **The narrative people believed *then*** versus **the narrative we believe *now***.
- **The thread to today** — how this year contributed to where the United States
  actually is in the present.

The goal is **not** an encyclopedia. Encyclopedias already exist. The goal is
**interpretation with teeth**: deep, philosophical, willing to pressure the
comfortable story from every direction, and honest about the distance between
what was *said* and what was *real*.

> If an entry could appear unchanged in a high-school textbook, it has failed.
> See [`docs/depth-rubric.md`](docs/depth-rubric.md).

---

## The Three Minds

Three **model-agnostic interpretive personas**. Any AI model can play any seat;
the persona is defined by its *lens*, not its brand. They are co-equal — none is
the referee, none is "the right answer."

| Persona | Lens | Core question |
|---|---|---|
| 🜂 **The Herald** | Received narrative / mythology | *What did people believe this meant — then and now — and how was that story built?* |
| 🜄 **The Heretic** | Counter-narrative / power | *Who benefited from that story? What was omitted, suppressed, or laundered?* |
| 🜃 **The Cartographer** | Structure / material forces | *What forces beneath the story actually moved events — and where do the threads lead?* |

Full definitions in [`docs/agents/`](docs/agents/).

---

## Repository Map

```
README.md                  ← you are here
CONTRIBUTING.md            ← workflow for the AI agents filling this in
docs/
  methodology.md           ← the philosophical commitments (read this first)
  debate-protocol.md       ← the turn-by-turn structure of a year's debate
  depth-rubric.md          ← the quality bar; the self-check before "done"
  event-selection.md       ← how to choose the 3 U.S. + 3 world events
  connections.md           ← how to map intra-year and inter-year threads
  glossary.md              ← shared vocabulary
  agents/
    README.md              ← how the three personas interact
    herald.md  heretic.md  cartographer.md
templates/
  YEAR_TEMPLATE.md         ← the master fillable template for a single year
  DECADE_README_TEMPLATE.md
years/
  README.md                ← index of decades + the running through-line
  1800-1809/ … 2020-2029/  ← one folder per decade, each with a README
                             agents create one file per year, e.g. 1803.md
```

---

## How a Year Gets Written (the short version)

1. **Select** the six events using [`docs/event-selection.md`](docs/event-selection.md).
2. **Copy** [`templates/YEAR_TEMPLATE.md`](templates/YEAR_TEMPLATE.md) into the
   right decade folder as `YYYY.md`.
3. **Carry forward** the threads handed off by the previous year.
4. **Debate** the year following [`docs/debate-protocol.md`](docs/debate-protocol.md).
5. **Synthesize** — record agreements, preserve the irreducible disagreements.
6. **Hand off** the threads the next year must pick up.
7. **Check** against [`docs/depth-rubric.md`](docs/depth-rubric.md) before marking done.

---

## Principles in One Breath

- **No surface knowledge.** Facts are the floor, not the ceiling.
- **Two narratives, always.** What they believed *then*; what we believe *now*.
- **Follow the forces, not just the figures.**
- **Disagreement is a feature.** Synthesis preserves tension; it does not dissolve it.
- **Everything connects forward.** Each year owes a debt to the last and a duty to the next.
- **Aim the lens at today.** The destination of every thread is the present-day United States.

---

*This is a scaffold for AI agents to fill. It contains no completed history yet —
only the architecture for producing it.*
