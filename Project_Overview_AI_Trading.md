# AI‑Powered Real‑Time Trading System (BANKNIFTY) — One‑Page Overview

**Status:** Research → Live-ready prototype | **Primary target:** BANKNIFTY futures | **Last updated:** 2025-09-02

**What it is (in one line):** A modular, automated trading stack that converts live market data into ML‑filtered trade signals and executes them with strict risk controls via broker APIs.

---

## Highlights (why it matters)
- **End‑to‑end pipeline:** Data → Features → ML → Risk → Execution → Journaling.
- **Feature‑rich:** VWAP distance, Renko trend logic, OI delta, candle structure, time‑of‑day gates.
- **Model:** XGBoost binary classifier with confidence gating for signal quality.
- **Execution:** ICICI Breeze API; single‑position discipline, SL/TP and cooldowns.
- **Journaling:** Complete trade logs & runtime logs for review and iteration.

> Offline ROC‑AUC ≈ 0.7285 with confidence thresholding around 0.6 (project report). fileciteturn1file0

---

## System at a glance
![System Architecture](/mnt/data/architecture_diagram.png)

---

## Key artifacts & links
- **Project report (PDF):** `/mnt/data/Aneesh_final_project_Report.pdf`
- **Conference paper / preprint (PDF):** `/mnt/data/AI-Powered Real-Time Trading System for Financial Markets Using Machine Learning.pdf`
- **Public CV (no phone):** `/mnt/data/Aneesh_VR_Public_CV.md`
- **90‑second demo script:** `/mnt/data/90s_Demo_Script.txt`
- **LinkedIn announcement copy:** `/mnt/data/LinkedIn_Announcement_Post.txt`

> Tip: Host these on GitHub or Google Drive with “Anyone with the link can view,” then attach the links to your LinkedIn **Featured** section and **Publications/Projects** entries.

---

## 90‑second demo (outline)
- **Hook (0–10s):** The problem: fast markets, inconsistent manual execution.
- **How it works (10–40s):** Data → features → ML confidence → risk filters.
- **Execution (40–70s):** Breeze API orders; SL/TP; cooldown; single‑position rule.
- **Outcomes (70–85s):** AUC, discipline, journaling; continuous improvement loop.
- **CTA (85–90s):** “Links below; open to collaborations in ML trading systems.”

---

## Recruiter‑friendly keywords
Python · XGBoost · Feature Engineering · Real‑time Systems · Broker APIs · Risk Management · SQL · Linux · Git · AWS (optional) · Quant Research · Backtesting/Simulation
