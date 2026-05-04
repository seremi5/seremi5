## What I'm Building

### Public

| Project | Description | Stack |
|---|---|---|
| [investing-ai](https://github.com/seremi5/investing-ai) | Long-term stock risk analyzer. Quantitative scoring + 4-agent AI debate (Bull / Bear / Skeptic / Judge) + probabilistic 12-month forecast | Python · Gemini AI · Alpha Vantage · yfinance |
| [ai-forge](https://github.com/seremi5/ai-forge) | Standards and patterns I use to build AI pipelines. Templates, agent contracts, and conventions | Python · Gemini AI |

### In Progress *(private)*

| Project | Description |
|---|---|
| **Team Booking System** | Live scheduling and team management platform |
| **Expense Management** | Automated expense tracking, categorization, and reporting |
| **Secure File Transfer** | Private, end-to-end file transfer solution |

---

## How I Build AI

All my AI projects follow a shared architecture:

```
CLI entry point
    │
    ├─ Data layer     → external APIs wrapped as typed services
    ├─ Scoring layer  → quantitative signal, no AI
    ├─ Agent layer    → multi-agent debate: Bull / Bear / Skeptic / Judge
    └─ Output layer   → self-contained HTML report
```

Each agent has a single responsibility. Data flows forward only. The AI writes analysis — it never controls flow.

Full patterns and conventions → [ai-forge](https://github.com/seremi5/ai-forge)

---

## Stack

`Python` · `Gemini AI` · `Alpha Vantage` · `yfinance` · `SEC EDGAR` · `Claude Code`
