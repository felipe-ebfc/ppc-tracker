# PPC Tracker — Simple Mode Spec

## Mode Toggle
- Shown at project creation, prominent and obvious
- Default = Full Mode (all features)
- Simple Mode = streamlined entry for teams who want less friction
- **Locked for the week** — no switching mid-week (teams build habits)

## Work Period
- Day selector (like Scrum Burndown — pick which days of the week)
- 5, 6, or 7 day weeks
- Locked in at project creation

## Daily Entry (Simple Mode)
- Enter per day across the work period:
  - **Commitments Planned:** [number]
  - **Commitments Completed:** [number]
  - **Variance reasons** for each missed commitment (dropdown, LCI categories)
- **Daily PPC shown per day** so teams see each day's reliability (not just a running average that confuses on Monday)
- **Weekly PPC left blank** until the last work day is entered — then it calculates from all daily totals
- **Explainer tile** showing how PPC is calculated
- All numbers stay visible — daily planned, completed, daily PPC, variance
- Team sees the week building up day by day — live feedback loop

## Variance Tracking (Simple Mode)
- Entered daily alongside the numbers
- Each day's missed commitments get tagged with variance reason
- Weekly view shows pattern: which reasons, which days, frequency
- Example:
  - Mon: 4 planned, 3 completed → 1 × Prerequisite work not complete
  - Tue: 3 planned, 3 completed → ✅
  - Wed: 5 planned, 4 completed → 1 × Information not complete
  - Week PPC: 10/12 = 83.3% (Green zone)

## LCI-Standard Variance Categories
1. Prerequisite work not complete
2. Materials not available
3. Labor not available
4. Equipment / tools not available
5. Information not complete (drawings, RFIs, design)
6. Space conflict / access issue
7. Weather
8. Safety / inspection issue
9. Planning error / overcommitment

## Key Lean Insights (bake into UX)
- **Top causes are almost always:** Prerequisites + Information — most failures happen before work starts
- PPC is about **learning from variance patterns**, not the percentage
- Team-level only — individual PPC is weaponized and not respectful
- Once teams track variance honestly, PPC jumps from 50-60% → 75-85% within months
- GCs who punish low PPC without tracking variance are missing the point

## Audience
- PMs and Superintendents
- Construction teams practicing Last Planner System

## Print
- B&W optimized (@media print) — many small teams don't have color printers
- Patterns/hatching instead of color-only differentiation

## Philosophy
- Audience: PMs and Superintendents
- Team PPC only — no individual tracking (anti-weaponization)
- Variance is the point — PPC without variance is just blame
- LCI Communities of Practice standard

---
*Source: Felipe Engineer-Manriquez, March 6 2026*
*Reference: GPT Sara (LCI variance research), Lean Construction Institute*
