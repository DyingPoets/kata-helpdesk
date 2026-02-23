# Helpdesk Ticket System — Work Orders + Metric Intent

> **Branch:** `skill/wos-metric-intent`
> **Skills:** W1 · M5 · D4
> **Audience:** PM · Eng

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 5: Helpdesk Ticket System |
| **Session** | Work Orders + Metric Intent |
| **Skills** | W1 · M5 · D4 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/nxmqoqutbtdao8k |
| **Miro Board** | https://miro.com/app/board/uXjVG8Qut6E%3D/ |

### Session Timing

| Time | Activity |
|------|----------|
| 0:00–0:15 | Concept framing — open the Gamma slide deck and walk through each slide |
| 0:15–0:30 | Orient to Miro board + this starting state |
| 0:30–1:05 | Step 1 exercise (Miro — Context frame) |
| 1:05–1:25 | Step 2 exercise (Miro — Exercise frame) |
| 1:25–1:30 | Step 3 wrap-up |
| 1:30–1:50 | Debrief — use Miro Debrief frame prompts |
| 1:50–2:00 | Extension brief — point to Extension Zone in Miro |

### What to Watch For

- Metric intent statements that are activity metrics ("number of WOs completed") not outcome metrics
- Agent config that's too permissive — what happens if the agent implements the wrong thing?
- WOs without acceptance criteria — "how would you know it's done?" is the key question

### Facilitation Tips

- For each metric: "If this number is perfect but users are unhappy, what went wrong?" — reveals activity vs. outcome
- On agent config: "What is the single most dangerous thing the agent could do here?" — inspires the constraints
- Pair engineers and PMs — PM writes metric intent, engineer writes acceptance criteria, then swap to review

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-helpdesk
git checkout skill/wos-metric-intent
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/nxmqoqutbtdao8k
- **Miro Board:** https://miro.com/app/board/uXjVG8Qut6E%3D/

### What You'll Practice

- W1
- M5
- D4

### Your Starting State

You have:
- `wos/work-order-stubs.md` — 4 partially completed Work Orders
- `reference/metric-intent-guide.md` — guide to writing metric intent statements

Your goal: complete the WOs, validate metric intent, and write agent config for WO 2.

### Step by Step

**Step 1:** Complete the 4 WO stubs: fill in goal, acceptance criteria, and metric intent for each.

**Step 2:** For each metric intent statement: complete "If this metric moves as intended, it proves ____." Rewrite any that you can't complete.

**Step 3:** Write the `.cursorrules` constraints for WO 2. What must the agent never do? What assumptions must it state before acting?

### What Good Looks Like

WOs where a PM and an engineer independently read the acceptance criteria and agree on what "done" means. Metric intent statements that prove user value, not delivery activity.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Write a drift detection check for WO 2: what output signals would tell you the agent went off-track?
- Explain metric intent in one paragraph to a PM who's never heard of it — no jargon
- Bring your WOs + the metric intent you're most uncertain about to Office Hours

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
