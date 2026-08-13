# 📅 SUNDAY WEEKLY REVIEW CHECKLIST

**Time:** 30-45 minutes every Sunday  
**Purpose:** Consolidate learning, catch gaps, plan next week

---

## 1. REVIEW LAST WEEK (10 min)

### Weekly Log
- [ ] Open `04_Weekly_Log/Week_XX.md`
- [ ] Fill all metrics: Papers (1-pass / 2-pass / implemented), LOC, Concepts
- [ ] Write 2-3 sentences on "What actually stuck?"

### Paper Progress
| Paper | Tier | 15-min | Full | Implemented | Notes |
|-------|------|--------|------|-------------|-------|
|  |  | ☐ | ☐ | ☐ |  |

### Code Progress
| Project | Sessions | Goal Met? | Blockers Resolved? |
|---------|----------|-----------|-------------------|
|  |  | ☐ | ☐ |

---

## 2. REVISION: 4-WEEK LOOKBACK (10 min)

Open notes from **4 weeks ago** (check `04_Weekly_Log/Week_XX.md` for date).

For each concept/paper from that week, answer **without looking at notes**:

> **"What was the key idea and when would I use it?"**

| Concept/Paper | Can Explain in 30s? | Action Needed |
|---------------|---------------------|---------------|
|  | ☐ Yes / ☐ No | Re-read note / Re-run notebook / Add comment |

**If NO on any:** Spend 5-10 min re-engaging with that notebook/note. Add one clarifying comment.

---

## 3. MONTHLY TEACH-BACK (1st Sunday only — 30 min)

Pick **one Tier 1 paper from 2 months ago**.

**Teach it out loud** to an empty room (or record yourself):
1. What problem did it solve?
2. What was the key insight?
3. How does the method work? (walk through steps)
4. What was the main result?
5. What are the limitations?
6. What came after it?

**If you stumble anywhere:** That's a real gap.
- Re-run your implementation notebook
- Add a comment explaining the part you stumbled on
- Update the concept note

---

## 4. QUARTERLY FOUNDATIONS RECHECK (Jan/Apr/Jul/Oct — 1 hour)

Pick **one Phase 3 (Classical ML) algorithm**.

**Re-implement from scratch WITHOUT looking at old code.**

Compare with your old implementation:
- What did you forget?
- What do you understand better now?
- What was wrong in the old version?

---

## 5. GRAPH HEALTH CHECK (5 min)

Open Obsidian Graph View with these filters:

### Check 1: Orphaned Concepts
- Filter: `tag:#concept` AND NOT `tag:#project` AND NOT linked to any paper
- **Action:** Either delete (unimportant) or connect (important but isolated)

### Check 2: Phase Coverage
- Filter by phase tags (`#phase0`, `#phase1`, etc.)
- **Action:** Are you building concepts in the current phase? Or jumping ahead?

### Check 3: Project-Concept Links
- Filter: `tag:#project`
- Click each project → see linked concepts
- **Action:** Every active project should link to 3+ concepts

---

## 6. PLAN NEXT WEEK (10 min)

### Select 3 Papers for Inbox
| Paper | Why This Week | Expected Tier |
|-------|---------------|---------------|
| 1. |  |  |
| 2. |  |  |
| 3. |  |  |

### Pick 1 Concept to Deepen
| Concept | Area | Current Status | Target Status |
|---------|------|----------------|---------------|
|  |  |  |  |

### Set Coding Goals
| Project | This Week's Target | Definition of Done |
|---------|-------------------|-------------------|
|  |  |  |

### Update Master Index
- [ ] Current Phase / Concept / Project in `00_Meta/MASTER_INDEX.md`
- [ ] Week number incremented

---

## 7. QUICK ADMIN (2 min)

- [ ] Git commit & push any code changes
- [ ] Backup Obsidian vault (if not auto-synced)
- [ ] Clear Jupyter output cells in finished notebooks (save space)
- [ ] Check disk space: `df -h /home/lap-19`

---

## TEMPLATE FOR NEXT WEEK'S LOG

Create `04_Weekly_Log/Week_XX.md` from template:
```bash
cp 06_Templates/weekly_log.md 04_Weekly_Log/Week_$(date +%V).md
# Then edit with week number, year
```

---

## RED FLAGS — INVESTIGATE IF YOU SEE

| Flag | Meaning | Action |
|------|---------|--------|
| 0 papers implemented this month | Not doing Mode 3 | Schedule implementation Friday |
| >5 concepts at "seed" for 4+ weeks | Not growing concepts | Pick one, deepen this week |
| No questions accumulated | Not reading deeply enough | Re-read with "what don't I understand?" |
| Graph has many isolated nodes | Not connecting ideas | Add connections during review |
| Always using Colab, never local | Avoiding local constraints | Build something small locally |

---

*Non-negotiable. This 30 minutes is what makes the other 20 hours of the week compound.*
