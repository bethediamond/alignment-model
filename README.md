# Toy 01 — Objective Class & Substrate Stability

> *Part of **The Alignment of Intelligence** — a three-article series.*
> **The article is forthcoming.** This toy is a companion to Article 1: *Constraint*.

---

## AI Alignment Simulation

A live multi-agent simulation that makes one argument visible:

> **The structure of an objective — not the capability of the agent — determines whether optimization is self-sustaining or self-terminating.**

100 steps. 20 agents. Identical starting conditions. The only variable is whether each agent's objective models the shared environment it depends on. Watch what that single structural difference produces.

---

## Objective Classes & Scenarios

Three scenarios run from the same initial state:

| Scenario | Objective Class | Behavior |
|---|---|---|
| **Narrow** | Substrate-blind | Maximizes local extraction; ignores system-wide effects |
| **System-Aware** | Substrate-aware | Models and preserves the shared substrate |
| **Mixed Population** | Both, sharing one substrate | Narrow and system-aware agents compete on the same life support |

**Side-by-Side mode** shows the two objective classes diverging in real time — same agents, same environment, same shocks — until the structural difference resolves.

**Mixed Population mode** shows the harder result: a minority of narrow agents is sufficient to collapse the substrate for everyone, including every system-aware agent that would never have caused this alone.

---

## Key Concepts in Substrate Stability

**Shared Substrate** — The non-excludable resource all agents depend on. It regenerates slowly. It does not recover from zero.

**Absorbing State** — The terminal condition. Once the substrate reaches zero, all payoffs become zero permanently — regardless of wealth accumulated before collapse. The system cannot exit this state.

**Dependency Debt** — Hidden damage accumulating below the visible substrate floor. The narrow objective produces apparent stability while systematically building toward a failure it cannot detect.

**S\*** — The minimum substrate level from which a system-aware objective can still recover. The narrow objective never reaches it.

**Best-Case Mode** — Removes environmental shocks. The narrow objective still collapses. The failure is architectural, not circumstantial.

---

## Simulation Controls

| Control | Function |
|---|---|
| **Side by Side / Mixed Population** | Switch between comparison and convergence scenarios |
| **Run / Pause** | Start or pause the simulation |
| **Reset** | Return to identical starting conditions |
| **Remove shocks** | Toggle environmental shocks off — tests the best case |
| **Speed slider** | Control simulation tick rate |
| **Narrow agents %** *(Mixed mode)* | Set the proportion of narrow agents in the shared population |

The **Causal Chain log** at the bottom traces each tick: objective → action → substrate effect → system state.

---

## The Alignment Argument: Constraint → Attractor → Crossing

This toy is the first of three. The trilogy is structured as:

```
Constraint  →  Attractor  →  Crossing
   (1)            (2)           (3)
```

**Article 1 (this toy):** Eliminates invalid objectives. Any objective that ignores system-wide effects is structurally self-terminating — not under adversarial conditions, not eventually, but as the logical completion of the optimization.

**Article 2:** Identifies the surviving region. What does optimization converge toward once self-defeating objectives have been removed?

**Article 3:** Determines reachability. The control variable governing whether real systems arrive at the attractor before encountering the states Article 1 excludes.

All three reduce to one constraint: whether capability outpaces the system's ability to model its own effects.

---

## Run Locally

No build step. No dependencies. Open `toy_01.html` in any modern browser.

```bash
open toy_01.html
# or just drag the file into a browser tab
```

---

## Article

[The Alignment of Intelligence, Article 1: Constraint](https://medium.com/@diamondlight/i-alignment-as-structural-necessity-07e38568754f)

---

*"A system that optimizes without modeling its dependencies selects for strategies that appear effective until they irreversibly fail. The failure is not an accident. It is the logical completion of the objective."*
