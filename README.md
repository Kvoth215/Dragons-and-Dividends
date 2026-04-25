# 🏰 Life Quest — Personal Finance Simulation

> *A cross-curricular, D&D-influenced personal finance simulation for middle school students.*

[![PA Standards](https://img.shields.io/badge/PA%20Standards-17.1–17.6-blue)](https://www.education.pa.gov)
[![Grade Level](https://img.shields.io/badge/Grade%20Level-6–8%20(9–12%20extensions)-green)](https://www.education.pa.gov)
[![Subjects](https://img.shields.io/badge/Subjects-Math%20·%20ELA%20·%20SS%20·%20Science-orange)](https://www.education.pa.gov)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)](LICENSE)

---

## 📖 What Is This?

**Life Quest** is a browser-based personal finance simulation where students:

- **Choose a life path** (Military, 4-Year University, Trade Apprenticeship, Entrepreneur, or Community College) — each with realistic income, starting savings, and debt
- **Manage a monthly budget** across 12 simulated months (Year 1) and an optional Year 2 Hard Mode
- **Roll for random events** — medical bills, market crashes, bonuses, identity theft, and the occasional unauthorized dragon renovation
- **Complete 16 gated subject-area quests** across Math, ELA, Social Studies, and Science — students cannot advance until each quest is passed
- **Track net worth** over time and reflect on financial decisions

Progress saves automatically via `localStorage` so students can pick up across class periods.

---

## 🎯 Curriculum Alignment

Aligned to **Pennsylvania Academic Standards for Personal Finance**  
*(22 Pa. Code Chapter 4, Appendix F — effective July 1, 2026)*

| Standard | Description | Quest(s) | Events |
|---|---|---|---|
| 17.1.6-8.B | Opportunity cost | Q3, Q9 | Inflation, Scarcity |
| 17.1.9-12.A | Long-term financial goals | Q11 | — |
| 17.2.9-12.C | Education cost vs. income | Q14 | — |
| 17.2.9-12.H | Taxes and payroll deductions | Q15 | Tax refund |
| 17.3.6-8.B | Pricing methods & comparison | Q5 | Market sale |
| 17.3.6-8.D | Personal budget components | Q3 | — |
| 17.3.6-8.L | Sales tax calculation | Q5 | — |
| 17.3.9-12.E | Personal budget creation | Q2 | — |
| 17.3.9-12.K | Total cost of ownership | Q4, Q6, Q10 | — |
| 17.3.9-12.L | Taxes on financial decisions | Q9 | — |
| 17.4.6-8.C | Compound interest | Q1 | — |
| 17.4.9-12.A | Net worth calculation | Q16 | — |
| 17.4.9-12.H | Investment portfolio | Q13 | — |
| 17.5.3-5.B | Emergency savings | — | Dragon, Tooth |
| 17.5.6-8.C | Types of insurance | — | Fire, Plague |
| 17.5.6-8.H | Protecting personal information | — | Pickpocket |
| 17.5.9-12.I | Financial fraud response | — | Identity theft |
| 17.6.6-8.E | Total cost of credit | Q8 | — |
| 17.6.6-8.G | Consumer rights | Q7 | — |
| 17.6.9-12.E | Minimum payments & debt | Q12 | — |

---

## 🎮 Game Structure

### Year 1 (Months 1–12) — 11 Quests

| Month | Quest | Subject | PA Standard |
|---|---|---|---|
| 1 | The Merchant's Vault | 🔢 Math | 17.4.6-8.C |
| 2 | The Budget Proclamation | 📜 ELA | 17.3.9-12.E |
| 3 | The Scarcity Scroll | 🗺️ Social Studies | 17.1.6-8.B |
| 4 | The Candle Conspiracy | ⚗️ Science | 17.3.9-12.K |
| 5 | The Discount Dungeon | 🔢 Math | 17.3.6-8.B |
| 6 | The Artificer's Dilemma | ⚗️ Science | 17.3.9-12.K |
| 7 | The Complaint Scroll | 📜 ELA | 17.6.6-8.G |
| 8 | The Moneylender's Maze | 🔢 Math | 17.6.6-8.E |
| 9 | The King's Ledger | 🗺️ Social Studies | 17.3.9-12.L |
| 10 | The Sunstone Summit | ⚗️ Science | 17.3.9-12.K |
| 11 | The Final Chronicle | 📜 ELA | 17.1.9-12.A |

### Year 2 Hard Mode (Months 13–24) — 5 Additional Quests

| Month | Quest | Subject | PA Standard |
|---|---|---|---|
| 13 | The Debt Dragon | 🔢 Math | 17.6.9-12.E |
| 14 | The Portfolio Parchment | 📜 ELA | 17.4.9-12.H |
| 15 | The Great Career Calculus | 🗺️ Social Studies | 17.2.9-12.C |
| 16 | The Tax Tribunal | 🔢 Math | 17.2.9-12.H |
| 17 | The Net Worth Reckoning | 🔢 Math | 17.4.9-12.A |

Year 2 increases difficulty: rent +200gp/month, provisions +50gp/month, income +5% raise, and more volatile random events (market crashes, identity theft, flooding, etc.).

---

## 🎲 Random Events

### Year 1 (18 Events)
Bad events include: Molar Catastrophe (−350gp), Unauthorized Dragon Renovation (−420gp), Rogue Redistribution of Wealth (−220gp), FOMO Financially Obliterates Monthly Objectives (−170gp), and more.

Good events include: Turns Out Good Work Pays Off (+500gp), Uncle Bartholomew Delivers Again (+400gp), Guild Referral Bonus (+250gp), Legal Victory (+300gp), and more.

### Year 2 (12 Events, Higher Stakes)
Includes: Market Crash (−15% of savings), Identity Theft (−850gp), Kitchen Catastrophe (−900gp), The Promotion Arrives (+1,200gp bonus), Investment Matures (+900gp), and more.

Every event includes a PA Standards citation and a teaching tip visible to students.

---

## 🖥️ How to Use

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Share the Pages URL with students: `https://yourusername.github.io/life-quest/`

Students open the link on any device — Chromebook, phone, tablet, computer. No login required.

### Option 2: Local File

Download `index.html` and open it directly in any modern browser. Works offline.

### Option 3: Google Classroom / Canvas LMS

Upload `index.html` as an attachment or link to your GitHub Pages URL. Students access it from the assignment.

---

## 📋 Suggested Pacing

| Session | Duration | Content |
|---|---|---|
| 1 | 30–45 min | Introduction, character creation, Month 1–2 |
| 2–3 | 45 min each | Months 3–6, pause at quests for class discussion |
| 4–5 | 45 min each | Months 7–12, final results |
| 6+ (optional) | 45 min each | Year 2 Hard Mode |

**Tip:** Pause after each quest for a 5-minute class discussion. The quest completion moment is the best teaching window.

---

## 👩‍🏫 For Teachers

### Cross-Curricular Use

This simulation is designed to be used **across subjects** — not just in one class:

| If you teach... | Your quests are... |
|---|---|
| **Math** | Q1 (compound interest), Q5 (discounts/tax), Q8 (loan comparison), Q12 (minimum payments), Q15 (tax brackets), Q16 (net worth) |
| **ELA** | Q2 (budget proclamation), Q7 (consumer complaint), Q11 (financial reflection), Q13 (investment portfolio) |
| **Social Studies** | Q3 (scarcity/opportunity cost), Q9 (government budgets), Q14 (education ROI) |
| **Science** | Q4 (break-even: candles), Q6 (total cost of ownership), Q10 (renewable energy break-even) |

### ELA Quest Design

ELA quests use a **self-check rubric** — students confirm they've addressed each required element before submitting. The submission is flagged *"Stamped for Teacher Review"* so you can collect and discuss the writing. No AI scoring is used.

### Teacher's Guide

Download `teacher-guide.html` for:
- Complete worked solutions for all 16 quests with accepted answer ranges
- Common student errors flagged per quest
- ELA writing rubric with exemplars
- All 24 random events with PA standard citations
- Discussion questions by month
- Differentiation strategies

---

## 📁 File Structure

```
life-quest/
├── README.md              ← You are here
├── index.html             ← The simulation (fully self-contained)
├── teacher-guide.html     ← Printable teacher reference (NOT for students)
└── LICENSE                ← CC BY-NC 4.0
```

Both HTML files are **fully self-contained** — no external dependencies, no CDN, no API keys, no server required.

---

## 💾 Save System

Progress is saved automatically to `localStorage` in the student's browser after every action. Students can:

- Close the tab and return later — progress is preserved
- Click **"Continue Saved Adventure"** on the welcome screen
- Reset with the **"Play Again"** button at the end (intentional — try a different life path!)

**Note:** `localStorage` is browser-specific. Students should use the same browser on the same device each session. If your school uses Chromebooks, Chrome's profile sync may persist saves across devices — but this is not guaranteed.

---

## 🛠️ Customization

The simulation is intentionally built in a single HTML file with no framework dependencies so teachers can modify it directly.

**To change income values:** Find the `PATHS` array near the top of the `<script>` section and edit the `income`, `debt`, and `gold` properties.

**To add random events:** Add objects to the `EV1` (Year 1) or `EV2` (Year 2) arrays following the existing format: `{e:'emoji', t:'Title', d:'Description', g:goldChange, typ:'good'|'bad'|'neutral', tip:'Teaching tip (PA Standard)'}`.

**To add quests:** Add objects to `Q1` (Year 1) or `Q2` (Year 2) arrays. Set `tm` to the trigger month (0-indexed), `type` to `'number'`, `'nc'` (number + choice), or `'writing'`.

---

## 🏛️ Background & Philosophy

This simulation was developed by a Pennsylvania middle school BCIT (Business, Computers, and Information Technology) teacher with background in D&D-based education and certified in elementary and middle school mathematics.

The design is influenced by research on game-based learning and the documented benefits of Dungeons & Dragons as an educational tool for:
- Social-emotional learning (SEL)
- Critical thinking and decision-making
- Cross-curricular engagement
- Supporting neurodivergent learners

**Key design principle:** Real financial concepts with a fantasy skin. "The King's Tax" is income tax. "The Merchant's Vault" is a savings account. "The Debt Dragon" is minimum payment math. The fantasy framing lowers resistance to engagement while the content is entirely standards-aligned and real-world applicable.

### References

- Cicchino, M. M. (2015). Using Game-Based Learning to Foster Critical Thinking. *Interdisciplinary Journal of Problem-Based Learning, 9*(2).
- Bowman, S. (2010). *The Functions of Role-Playing Games.* McFarland & Company.
- Pennsylvania Department of Education. (2026). *Academic Standards for Personal Finance.* 22 Pa. Code Chapter 4, Appendix F.
- AdventuringPortal.com — D&D for Kids educational resources

---

## 📄 License

This project is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](LICENSE).

**You are free to:**
- Share and redistribute the material
- Adapt, remix, and build upon it
- Use it in your classroom

**Under these conditions:**
- **Attribution** — Credit the original project and author
- **NonCommercial** — Not for commercial use or sale

---

## 🤝 Contributing

Contributions welcome! Especially:
- Additional quests aligned to other PA standards
- Translations or accessibility improvements
- Additional life paths or random events
- Bug reports

Open an issue or submit a pull request.

---

*Made with 🎲 for Pennsylvania middle schoolers — and the teachers brave enough to bring D&D into the classroom.*
