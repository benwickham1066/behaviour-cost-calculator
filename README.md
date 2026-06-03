# SSC Defensive Behaviour Cost Calculator

**Built by [Single Session Coaching](https://singlesession.online)**

A two-week observation and cost calculation tool that helps organisations put a number on the cost of defensive behaviour. Designed for CHROs, CFOs, COOs, and senior leadership teams.

---

## What It Does

The calculator has two parts.

**Part 1 — The Tally Sheet**

Twelve observable defensive behaviours, each with a plain-language example and the type of conversation it stops. The observer spends two weeks ticking every time they see a behaviour stop a conversation happening. One tick = one blocked conversation.

**Part 2 — The Calculator**

Four inputs: total ticks, people observed, org headcount, average annual salary. Two completely independent models produce a cost range:

- **Model A — Conversation Cost:** The observed ticks are annualised across 220 working days (×22 fortnights). Conservative floor at $1,500 per blocked conversation. Realistic average at $7,500. This model covers only the people observed — no extrapolation.
- **Model B — Gallup Cross-Check:** Independently calculates the org-wide cost using headcount × 75% reactive population × average salary × 34% Gallup disengagement cost. Uses no tick data at all.

The two models use entirely different methodologies and different data sources. When they land in the same range — and they will — that convergence is the evidence.

---

## The Maths

**Working days assumption:**
365 days − 104 weekend days − 11 public holidays − 30 days average leave = **220 working days per year**

**Annualisation multiplier:**
Two-week observation = 10 working days. 220 ÷ 10 = **×22**

**Model A formula:**
`Ticks × 22 × $1,500` (conservative) and `Ticks × 22 × $7,500` (realistic)

**Model B formula:**
`Headcount × 75% × Average salary × 34%`

**The 75% figure:**
Leadership Circle / Anderson & Adams — dataset of 2M+ leaders. 75% operate primarily from a reactive mindset, making decisions to protect themselves rather than move the business forward.

**The 34% figure:**
Gallup, State of the Global Workplace (2024). The cost of an actively disengaged employee is 34% of their annual salary.

---

## The Research Behind the Numbers

Five independent sources all converge between $1,500 and $1,700 per blocked conversation:

| Source | Finding |
|---|---|
| Crucial Learning (n=1,100) | 1-in-3 employees say a single avoided conversation cost their org $25,000+. Spread across the documented average of 15 working days = $1,667/day |
| Brad Rilatt / Crucial Dimensions (n=1,025) | Average cost per avoided conversation: $7,500 |
| Leadership Circle / Anderson & Adams (n=486) | 37.6% of business performance variance explained by leadership effectiveness. Complying alone suppresses Achieving by 56% |
| Gallup — State of the Global Workplace (2024) | Actively disengaged employee costs 34% of annual salary. Managers account for 70% of team engagement variance |
| SSC €350K Leadership Tax model | One reactive leader costs €350,000–€500,000/year, built bottom-up from Gallup, SHRM, McKinsey, and Leadership Circle correlation data. €350,000 ÷ 220 days = €1,590/day |

Five methodologies. Same number. That convergence is the credibility argument.

---

## The 12 Behaviours

Each behaviour is drawn from observable patterns across the Crucial Learning, Leadership Circle, Gallup, and McKinsey research stacks. No single taxonomy is reproduced — these are the behaviours all five frameworks independently identify as the primary drivers of conversation avoidance.

1. Pleasing
2. Softening feedback
3. Tolerating underperformance
4. Silence when risk is visible
5. Approval-seeking
6. Rescheduling the hard conversation
7. Cynicism or dismissal
8. Defensiveness to challenge
9. Micromanagement
10. Delegation avoidance
11. Passive in meetings
12. Reactive firefighting

---

## How to Embed in Squarespace

The calculator is designed to be embedded as an iFrame. The background is transparent so it inherits the page background colour from Squarespace.

In Squarespace, add a **Code Block** and paste:

```html
<iframe
  src="https://benwickham1066.github.io/ssc-cost-calculator"
  width="100%"
  height="2200px"
  frameborder="0"
  scrolling="no"
  style="background: transparent; border: none;">
</iframe>
```

Adjust `height` if needed — 2200px covers the full tool including results once calculated.

---

## How to Update

To update the calculator:

1. Make changes to `index.html` locally
2. In the GitHub repo click **Add file → Upload files**
3. Upload the new `index.html`
4. Select **Commit changes**
5. GitHub Pages updates automatically within 2 minutes

---

## Brand Tokens

| Token | Value |
|---|---|
| Background | `#111111` (transparent on embed) |
| Surface | `#1a1a1a` |
| Lime (accent) | `#DCFF4F` |
| Amber (cross-check) | `#F5A623` |
| White | `#f5f5f0` |
| Typefaces | Bebas Neue (display) · DM Sans (body) |

---

## Contact

**Single Session Coaching**
hello@singlesession.online
singlesession.online
