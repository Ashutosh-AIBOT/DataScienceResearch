# 📖 THREE READING MODES — Reference Card

**Source:** Learn-Read-Practice-System.ipynb (Part 1) + How-To-Read-Papers.ipynb

---

## MODE 1 — SURVEY READING (10-20 minutes)

**Question:** "What does this do and why does it matter?"

**Use for:**
- Every paper first pass
- All Tier 3 papers (reference)
- Landscape scanning (2-3 papers/week on Sunday)
- Deciding tier assignment

**Read in Order:**
1. Title
2. Abstract
3. Intro last 2 paragraphs (contributions)
4. Conclusion first paragraph
5. Every figure + caption
6. Section headings only

**Output:** 3-line note (problem, idea, result) OR decision to stop

**Stop Rule:** If "does this matter to me right now?" = NO → stop, 3-line note, move on

---

## MODE 2 — UNDERSTANDING READING (1-3 hours)

**Question:** "How exactly does this work and why did they make these choices?"

**Use for:**
- All Tier 1 papers (before implementation)
- All Tier 2 papers (core papers)
- When building something that needs this concept

**Rules:**
- Read entire paper
- **Never stop for math you don't understand**
- When stuck on equation: read sentence before + after → write plain English in note → keep moving
- Skip: related work (unless finding more papers), most proofs, appendix (unless implementing)

**Focus On:**
- Method section (exact mechanism)
- Key figures (architecture diagrams)
- Main results table (what number, what baseline)
- Ablation study (what actually matters vs decoration)

**Output:** Full paper note template (15-20 min to write)

---

## MODE 3 — IMPLEMENTATION READING (Full day)

**Question:** "Can I build the core idea from memory?"

**Use for:**
- Tier 1 papers ONLY (15-20 total in career)
- Foundational papers that everything builds on

**Process:**
1. Read paper (Mode 2)
2. Close paper
3. Open Jupyter notebook
4. Implement core idea from scratch
5. When stuck → open paper to EXACT part needed → close → continue
6. Verify on tiny dataset
7. Compare with library version
8. Document 3 things learned + remaining questions

**Notebook Standard:** 12-cell format (see project_log template)

**Output:** Working implementation + deep understanding

---

## TIER ASSIGNMENT (During Mode 1)

| Tier | Folder | Reading Mode | Implementation |
|------|--------|--------------|----------------|
| 1 Core | `01_Tier1_Core` | Mode 2 → Mode 3 | From scratch required |
| 2 Important | `02_Tier2_Important` | Mode 2 | Only if building |
| 3 Specialized | `03_Tier3_Specialized` | Mode 1 | None |
| 4 Reference | `04_Tier4_Reference` | None | Bookmark only |

---

## DIFFERENTIAL READING RULE

When you've deeply understood a base concept (e.g., vanilla gradient descent), variants get **differential reading** — only read the delta:

- What changed?
- Why did they change it?
- Did the result justify the change?

**Example:** After Adam deeply understood:
- AdamW → only weight decay decoupling (5 min)
- Lion → only sign update mechanism (10 min)
- Nadam → only Nesterov addition (5 min)

**Note for variants:** 3 lines — what changed from base + key result

---

## WEEKLY PAPER SCHEDULE

| Day | Activity |
|-----|----------|
| **Mon** | Mode 1 on 3 papers → assign tiers |
| **Tue-Wed** | Mode 2 on most important → write note |
| **Thu** | Mode 2 on 2nd paper if needed → quick note on 3rd |
| **Fri** | Mode 3 implementation (Tier 1) OR library experiment (Tier 2) |
| **Sat** | Write 200-300 word summary |
| **Sun** | Review + revision + Mode 1 on 2-3 new papers |

---

## MATH BLOCKING PROTOCOL

When equation stops you:

1. **What is this computing?** Read sentence before + after → plain English
2. **Inputs → Output?** Even if operation unclear, knowing "query+key → attention weights" lets you continue
3. **Blocking main idea?** 
   - YES → look up that specific math operation in isolation
   - NO → write "this equation does X" in note → keep moving

**Derive fully:** Only the 15 Tier 1 papers  
**Understand operation:** Everything else
