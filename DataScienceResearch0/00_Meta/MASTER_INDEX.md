# 🎯 MASTER INDEX — DataScienceResearch Vault

**Root:** `/home/lap-19/Desktop/DataScience-Reseach/DataScienceResearch/`  
**Obsidian Vault:** Open this folder in Obsidian → all notes, links, graph view work instantly.

---

## 📁 VAULT STRUCTURE

```
DataScienceResearch/
├── 00_Meta/                    # System config, hardware limits, rules
│   ├── MASTER_INDEX.md         # This file
│   ├── HARDWARE_LIMITS.md      # GTX 1650 honest assessment
│   ├── READING_MODES.md        # 3 reading modes reference
│   └── WEEKLY_REVIEW.md        # Sunday review checklist
│
├── 01_Papers/                  # 4-tier paper management
│   ├── 00_Inbox/               # ← DROP NEW PAPERS HERE
│   │   └── README.md           # Processing rules
│   ├── 01_Tier1_Core/          # Implement from scratch (15-20 total)
│   ├── 02_Tier2_Important/     # Full read, implement if building
│   ├── 03_Tier3_Specialized/   # Survey read only
│   └── 04_Tier4_Reference/     # Bookmarks only
│
├── 02_Concepts/                # Personal knowledge graph
│   ├── 00_Index/README.md      # Concept index + workflow
│   ├── 01_Math_Stats/
│   ├── 02_ML_Classical/
│   ├── 03_DL_Foundations/
│   ├── 04_Architectures/
│   ├── 05_Training_Opt/
│   ├── 06_Generative/
│   ├── 07_LLM_RAG/
│   ├── 08_MLOps_Prod/
│   └── 09_Research_Frontier/
│
├── 03_Projects/                # All implementations
│   ├── 00_Index/README.md      # Project index + standards
│   ├── 01_From_Scratch/
│   ├── 02_Replications/
│   ├── 03_Original_Work/
│   └── 04_Kaggle/
│
├── 04_Weekly_Log/              # Weekly reviews (one file/week)
│
├── 05_Questions/               # Accumulated questions
│
├── 06_Templates/               # Note templates
│   ├── paper_note.md
│   ├── concept_note.md
│   ├── project_log.md
│   └── weekly_log.md
│
└── 07_Resources/               # Shared assets
    ├── Datasets/               # Symlink actual data here
    ├── Models/                 # Saved model weights
    ├── Code_Snippets/          # Reusable components
    └── Links/                  # Curated URLs
```

---

## 🔄 DAILY WORKFLOW

### Monday (Planning)
1. Open `04_Weekly_Log/Week_XX.md` (create from template)
2. Select 3 papers for week → drop in `01_Papers/00_Inbox/`
3. Pick 1 concept to deepen → create/expand in `02_Concepts/`
4. Set coding goals for active project

### Tuesday-Thursday (Deep Work)
- **Paper sessions:** Mode 2 reading + note writing
- **Coding sessions:** Implement, debug, document in project log
- **Concept work:** Add connections, math, cheatsheet entries

### Friday (Build)
- Implementation from most important paper (Mode 3 or library experiment)
- Run experiments, log in project log

### Saturday (Synthesize)
- Write 200-300 word summary of week's learning
- Push to GitHub/private blog
- Update concept connections in graph view

### Sunday (Review + Revise)
- **Weekly review:** Open `04_Weekly_Log/Week_XX.md` → fill metrics
- **Revision:** Open notes from 4 weeks ago → 3-question check
- **Landscape scan:** Mode 1 on 2-3 new papers → drop in Inbox
- **Monthly (1st Sunday):** Teach-back one Tier 1 paper from 2 months ago
- **Quarterly (Jan/Apr/Jul/Oct):** Re-implement one Phase 3 algorithm from scratch

---

## 🎯 CURRENT STATE

| Item | Value |
|------|-------|
| **Current Phase** | 0 — Mathematical & CS Foundations |
| **Current Concept** | *Not started* |
| **Active Project** | *None* |
| **This Week's Papers** | *None selected* |
| **Week Number** | 1 (2026-07-30 start) |

*Update this section every Monday.*

---

## 📊 PROGRESS TRACKING

### Papers (Cumulative)
| Tier | Completed | Target |
|------|-----------|--------|
| 1 Core | 0 | 15-20 (career) |
| 2 Important | 0 | ~100 |
| 3 Specialized | 0 | ~200 |
| 4 Reference | 0 | Unlimited |

### Concepts by Status
| Status | Count |
|--------|-------|
| seed | 0 |
| growing | 0 |
| solid | 0 |
| teaching | 0 |

### Projects
| Type | Active | Completed |
|------|--------|-----------|
| From Scratch | 0 | 0 |
| Replication | 0 | 0 |
| Original | 0 | 0 |
| Kaggle | 0 | 0 |

---

## 🔗 QUICK NAVIGATION

### System Files
- [[HARDWARE_LIMITS|GTX 1650 Limits]]
- [[READING_MODES|3 Reading Modes]]
- [[WEEKLY_REVIEW|Sunday Review Checklist]]

### Workspaces
- [[../01_Papers/00_Inbox/README|Paper Inbox]]
- [[../02_Concepts/00_Index/README|Concept Index]]
- [[../03_Projects/00_Index/README|Project Index]]
- [[../04_Weekly_Log|Weekly Logs]]
- [[../06_Templates|Templates]]

### Roadmap
- [[Complete-Ai-world-Version|Complete AI World Version (Mentor Prompt)]]
- [[How-To-Read-Papers|How To Read Papers]]
- [[Learn-Read-Practice-System|Learn/Read/Practice System]]
- [[Research-Level-Full-RoadMap|20-Phase Roadmap]]

---

## ⚡ OBISDIAN SETUP NOTES

### Required Plugins (Enable in Settings → Community Plugins)
- **Dataview** — query notes as tables (progress tracking)
- **Templater** — advanced templates with variables
- **Calendar** — daily/weekly notes navigation
- **Graph Analysis** — better knowledge graph
- **Kanban** — project task boards (optional)
- **Excalidraw** — hand-drawn diagrams in notes

### Recommended Settings
- **Files & Links:** Always update internal links on rename
- **Editor:** Spell check on, line wrap on
- **Appearance:** Dark mode, minimal theme
- **Core Plugins:** All on except Audio recorder, Slides

### Graph View Filters (Save as presets)
1. **Papers Only:** `tag:#paper`
2. **Concepts Only:** `tag:#concept`
3. **Projects Only:** `tag:#project`
4. **Current Phase:** `tag:#phase0` (add phase tags to notes)

---

## 📝 TEMPLATE VARIABLES (for Templater)

When creating new notes from templates, these auto-fill:
- `{{date}}` → 2026-07-30
- `{{title}}` → filename without extension
- `{{week_num}}` → ISO week number
- `{{year}}` → 2026
- `{{time}}` → current time

---

## 🚀 STARTUP COMMAND

```bash
# Open vault in Obsidian
obsidian /home/lap-19/Desktop/DataScience-Reseach/DataScienceResearch/

# Or in VS Code (for coding)
code /home/lap-19/Desktop/DataScience-Reseach/DataScienceResearch/
```

---

## 📌 REMINDERS

> **Completeness over speed.** One deep implementation beats 10 shallow reads.
>
> **Connect everything.** Isolated notes are forgotten notes.
>
> **Hardware honesty.** GTX 1650 = 4GB VRAM. Use Colab for big stuff. No shame.
>
> **Revision is where learning sticks.** Sunday review is non-negotiable.
>
> **Build before you need it.** Implement the concept before the project requires it.

---

*Last updated: 2026-07-30 — Vault initialized*
