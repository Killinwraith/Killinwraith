<div align="center">

# Hetang Mehta

Computer Engineering @ UAlberta · Lead Developer (co-op) @ CNRL · ML Team Lead @ Alberta BIONIX

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=95BF47&center=true&vCenter=true&width=700&lines=I+turn+10-day+UATs+into+4-minute+coffee+breaks.;I+teach+LLMs+not+to+make+up+numbers.;Fluent+in+TypeScript%2C+Python+and+VB.NET+(yes%2C+VB.NET).;Weekdays%3A+shipping.+Weekends%3A+summits." alt="I turn 10-day UATs into 4-minute coffee breaks. I teach LLMs not to make up numbers. Fluent in TypeScript, Python and VB.NET (yes, VB.NET). Weekdays: shipping. Weekends: summits." />

[![Website](https://img.shields.io/badge/hetangmehta.ca-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.hetangmehta.ca/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hetang-mehta/)

</div>

---

```console
hetang@calgary:~$ whoami
computer engineering student who ships production code and then writes the tests for it

hetang@calgary:~$ cat ./currently.txt
→ building Store Copilot, a Shopify admin app that answers merchants in plain English
→ leading ML for a powered prosthetic knee (the control loop has 10 ms. no pressure.)
→ wrapping up co-op term #3 as lead developer at CNRL

hetang@calgary:~$ cat ./off_screen.txt
→ hiking the Rockies, camera in hand
→ collecting passport stamps and trail photos

hetang@calgary:~$ cat ./philosophy.txt
LLMs plan. Deterministic code executes. Evals prove it. Vibes are not a test suite.
```

## 🎮 Current stats

<div align="center">
<img src="./assets/stats.svg" width="100%" alt="Player stats: level 3 (co-op terms cleared), 24 months of production code. Achievements unlocked: Lead Developer, Speedrunner (117s to 22s), Test Wizard (10 days to 4 min), Hallucination Hunter (0 made-up numbers), Bionic Engineer (10 ms control loop), Polyglot. Side quests: hiking, photography, travel." />
</div>

## 💼 Experience

<table>
<tr><td>

### 🛢️ Canadian Natural Resources (CNRL), Calgary
**Systems Developer Student · 3 co-op terms, 24 months**

**Term 3 · May–Dec 2026: the "you're the lead now" term**
- Took over as **lead developer** of a production capital-budgeting app (VB.NET, Oracle) when the previous lead moved teams, keeping a release every **3–4 weeks** and getting a new developer to production in **2 months**
- Cut asset loads from **90–160 → 5–20 minutes** by building an API import for 900+ assets per load, with version locks and a per-asset audit trail
- Sped up worst-case load time **81%** (117s → 22s) by profiling and moving a 59s step off the critical path
- Put every database object under version control after missed edits caused hotfixes. Found the gap in standups I started.

**Term 2 · Jan–Aug 2025: the "rebuild it properly" term**
- Rebuilt the economics engine after 4 years of tech debt, fixing outdated math and adding a new major-project level
- Cut release validation from **10 days of manual testing → 4 minutes** with 300+ automated tests
- Built a golden well-production database **and** the PWA portal for it (C#, Blazor), removing reconciliation work that ate **a third** of analysis time for 500+ engineers

**Term 1 · Jan–Aug 2024: the "learn the codebase" term**
- Reduced database tickets **33%** vs. the prior 24 months by redesigning Oracle schemas and tuning queries
- Shipped 15+ hotfixes and small features to production

</td></tr>
<tr><td>

### 🦿 Alberta BIONIX, Edmonton
**ML Team Lead · Sep 2025 – Present**
- Lead a 2-engineer ML team building control models for a powered prosthetic knee
- Cut model inputs from **24 → 7 features** while keeping **87%** accuracy, from a **26GB** EMG gait dataset
- Co-designed a **10 ms** on-leg control loop: swapped a CNN too big for the onboard chip for an LDA classifier, a small MLP and PID control
- Leading design of an RL tuner that adjusts PID gains each stride, so learned models never drive the motor directly

</td></tr>
<tr><td>

### ⚙️ Suncor Energy, Fort McMurray
**Data Analyst Intern · Sep–Dec 2023**
- Saved **30+ hours/week** and **$26K/year** with 3 Python automation tools for SAP workflows

</td></tr>
</table>

## 🛠️ Things I've built

| Project | What it does | Receipts 🧾 |
|---|---|---|
| 🛍️ **[Store Copilot](https://github.com/Killinwraith/ShopifyStoreCopilot)** | Embedded Shopify admin app that answers merchants' sales and inventory questions. The LLM fills a typed query plan; deterministic code executes it. | **29/30** evals · **0** hallucinated numbers · **1.8s** median latency |
| 🧠 **[Batch Normalization](https://github.com/Killinwraith/BatchNormalization-ReduceInternalCovariateShift)** | Reproduction of Ioffe & Szegedy (2015) in PyTorch on MNIST and CIFAR-10. | MNIST **73–84% → ~98%** · survived LR 0.1 while the baseline diverged |
| 🦿 **[EMG Viability Model](https://github.com/albertabionix/EMG_Viability_ML_Algorithm)** | Classifies prosthetic-trial candidate viability from EMG sensor data. | **26GB** dataset · Random Forest feature ranking |
| 🔎 **[RagApp](https://github.com/Killinwraith/RagApp)** | RAG from scratch, no LangChain, grounded in a local LLM. | ~**50 lines** of Python · NumPy cosine search |

## 🧰 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

## 🎲 Fun facts

- I've read more Oracle execution plans than novels this year
- I wrote 300 tests so nobody ever has to click through 10 days of UAT again. You're welcome, business team.
- My camera roll is 80% mountains, 20% screenshots of stack traces
- 日本語も話せます (yes, I speak Japanese)

<div align="center">
<sub>Made in Calgary · Powered by coffee, trail mix and well-typed query plans</sub>
</div>
