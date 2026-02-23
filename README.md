# Helpdesk Ticket System — Discovery Before Building

> **Branch:** `skill/jtbd-prioritization`
> **Skills:** D4 · S2 · R1
> **Audience:** PM · UX

---

## For the Facilitator

### Session Overview

| | |
|---|---|
| **Kata** | 5: Helpdesk Ticket System |
| **Session** | Discovery Before Building |
| **Skills** | D4 · S2 · R1 |
| **Duration** | 2 hours (facilitated) + self-directed extension |
| **Slide Deck** | https://gamma.app/docs/tyw9vh64n5tw1xp |
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

- JTBD statements that are really features in disguise ("I want to track ticket status" ≠ JTBD)
- RICE scoring without evidence — Confidence scores should reflect what you actually know vs. assume
- Teams that never cut anything — prioritization means saying no

### Facilitation Tips

- For each JTBD: "Is that what they want to DO, or what they want to ACHIEVE?" Push to the deeper motivation
- When RICE scores are all high: "If budget was cut 50%, which 3 do you ship first?" Forces real trade-offs
- At debrief: compare the manager's wishlist to the JTBD-ranked list — the gap is the insight

### Extension / Coaching Office Hours

Participants can continue extension work independently and bring it to **Coaching Office Hours**.
At Office Hours, focus on: what decision did they make, why, and what would they change?

---

## For Participants (Developer · PM · UX)

### Getting Started

```bash
git clone https://github.com/DyingPoets/kata-helpdesk
git checkout skill/jtbd-prioritization
```

Open the Miro board and the Gamma slide deck — have both visible during the session.

- **Slides:** https://gamma.app/docs/tyw9vh64n5tw1xp
- **Miro Board:** https://miro.com/app/board/uXjVG8Qut6E%3D/

### What You'll Practice

- D4
- S2
- R1

### Your Starting State

You have:
- `research/manager-wishlist.md` — IT manager's 12-feature wishlist
- `research/support-agent-interviews.md` — 5 support agent interview quotes

Your goal: extract JTBDs from the interviews and score the features against RICE.

### Step by Step

**Step 1:** For each of the 5 interview quotes, extract the Job-to-be-Done. Format: "When [situation], I want to [motivation], so I can [outcome]."

**Step 2:** Score each of the manager's 12 features using RICE. Rank them. Identify top 3 and the 3 to cut.

**Step 3:** Write 3 discovery questions that would change your prioritization if answered.

### What Good Looks Like

JTBD statements that describe outcomes, not features. A RICE matrix where the Confidence column honestly reflects uncertainty.

See the `solutions/` directory for reference examples — but try the exercise first.

### Extension Work

- Design a 30-minute discovery session to validate your top JTBD with a support agent
- Map your top 3 features to OKRs — what business outcome does each advance?
- Write a one-page discovery summary you'd present to the engineering team before sprint planning

Bring your extension work to **Coaching Office Hours**. You'll get 15 minutes of focused feedback.

---

Part of the [PDLC Training Katas](https://github.com/DyingPoets) series.
