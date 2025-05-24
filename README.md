# 🔍 Prompt‑Driven Deep Research Playbook

A lightweight framework for _evidence‑backed_ prompt engineering research across four disciplines:

- **Software Engineering**
- **UI / UX Design**
- **Technical Product Management**
- **Academic Research**

Use this repo to **compare prompting patterns, run controlled experiments, and publish repeatable findings** — all under a shared rubric and citation style.

---

## 🚀 Quick Start

1. **Clone** this repository (or fork for your team).  
2. Read the **[Citation Guide](./CITATION_GUIDE.md)** and **[Evaluation Criteria](./EVALUATION_CRITERIA.md)**.  
3. Copy **`report_template.md`** into `discipline-reports/` and rename it (e.g., `software-eng.md`).  
4. Fill in each section as you complete Phase 1 research.  
5. Commit your report and open a pull request using the PR template (coming soon).

> **Tip:** keep raw prompt / response pairs in `prompt_log.yaml` for auditing.

---

## 🗂️ Folder Layout

```text
.
├── CITATION_GUIDE.md          # APA‑7 rules & examples
├── EVALUATION_CRITERIA.md     # Rubric used for scoring reports
├── report_template.md         # Skeleton for each deep‑dive report
├── discipline-reports/        # <- add one file per discipline
│   └── (example) software-eng.md
├── synthesis/                 # Cross‑discipline summaries
├── assets/                    # Figures, prompt logs, datasets
│   └── prompt_log.yaml
└── README.md
```

Feel free to create additional sub‑folders (e.g., `scripts/`, `notebooks/`) as the project evolves.

---

## 📏 House Rules

| Topic | Standard |
|-------|----------|
| **Citation Style** | APA‑7 inline parenthetical (see guide) |
| **Source Recency** | Primary sources **≥ March 2025** |
| **Word Cap** | ≤ 2 500 words per report |
| **Depth Target** | ≥ 3 novel insights per prompting pattern |
| **Verification** | Spot‑check ≥ 10 % of references |

---

## 🛠️ Automation (Optional)

We recommend adding:

* **markdownlint** – style guard  
* **lychee‑link‑checker** – broken URL detection  
* **CI badge** – show lint status in this README

---

## 📅 Project Phases

| Phase | Purpose |
|-------|---------|
| **0. Setup** | _✅ You are here_ — structure, guides, rubric |
| **1. Deep‑Dive Runs** | Gather & test prompting tactics per discipline |
| **2. Synthesis** | Compare findings, extract universal heuristics |
| **3. Gap‑Fill** | Patch weak areas with focused mini‑research |
| **4. Packaging** | Publish playbook & cheat‑sheet |

---

## 🤝 Contributing

1. Fork → Branch → PR.  
2. Follow the Evaluation Criteria for self‑scoring.  
3. Be kind: constructive reviews only.

---

## 📜 License

Code is released under the **MIT License**.  
Documentation is **CC BY 4.0** unless noted otherwise.
