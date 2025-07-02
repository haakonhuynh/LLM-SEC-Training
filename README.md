# SEC-Based Prompt Collection for LLMs

A system for generating high-quality financial Q&A data from SEC filings. Built for scale, precision, and real-world evaluation of large language models.

---

## 📌 Why This Exists

Most language models still struggle with financial reasoning grounded in real documents. This project tackles that by creating a scalable, quality-first pipeline to extract factual, well-cited prompts and answers directly from SEC filings (10-Ks and 10-Qs). The goal is simple: enable LLMs to read complex financial disclosures with a human in the feedback loop. 

---

## 🧠 What Makes It Different

This isn’t another annotation project. It’s designed from the ground up to ensure:
- **Contributor stratification** by skill level  
- **Prompt diversity** across formats and complexity  
- **Multi-tiered peer review** with actionable QA feedback  
- **Compensation tied to difficulty and accuracy**  
- **Coverage across industries and filing types**

---

## 🧭 Table of Contents

1. [Qualification Framework](#1-qualification-framework)  
2. [Annotation Workflow](#2-annotation-workflow)  
3. [Quality Assurance Process](#3-quality-assurance-process)  
4. [Compensation Model](#4-compensation-model)

---

## 1. Qualification Framework

Contributors are onboarded via a two-phase system that tests both financial literacy and synthesis ability.

- **Phase 1 – Baseline Skills**  
  Create factual prompts from a single 10-K (e.g., NVIDIA).  
  ✦ Goal: test comprehension, citation accuracy, and structure.

- **Phase 2 – Multi-Document Analysis**  
  Analyze and compare filings across General Motors, Ford, and Tesla.  
  ✦ Goal: evaluate reasoning depth, synthesis, and attention to nuance.

---

## 2. Annotation Workflow

Prompts fall into three categories:

| Category | Description                             | Type     | Time (est.) |
|----------|-----------------------------------------|----------|-------------|
| A        | Factual from a single document          | Easy     | 6–8 mins    |
| B        | Analytical from one document            | Moderate | 10–12 mins  |
| C        | Comparative across 2–5 filings          | Advanced | 20–25 mins  |

Each prompt must be grounded in a real filing, selected from a vetted sheet organized by:
- Company  
- Filing type (10-K or 10-Q)  
- Filing date (Oct 2023 or later)  
- Direct SEC link and saved PDF

---

## 3. Quality Assurance Process

We built the QA system with a reviewer-tiered structure to prioritize consistency without sacrificing throughput:

- **Peer Review:** All submissions are reviewed by trained annotators with category-specific approval  
- **Spot Audits:** Random checks by the project lead for quality control  
- **Structured Feedback:** Submissions rated "3" (mid-tier) are returned for revision with guidance  
- **Accountability:** Repeated low performance leads to temporary suspension or removal  

---

## 4. Compensation Model

| Category    | Rate   | Hourly (est.) |
|-------------|--------|---------------|
| A (Easy)    | $2.00  | ~$17/hr       |
| B (Moderate)| $3.25  | ~$17.75/hr    |
| C (Advanced)| $8.25  | ~$22/hr       |

**Bonuses:**  
🎯 *Accuracy Bonus* – $5 for 5+ prompts rated ≥ 4.5  
⚙️ *Complexity Bonus* – $10 for 5+ Category C completions

This model rewards both speed and thoughtfulness. Because real-world QA is more than just a numbers game.

---

## 🔗 License

This project is proprietary and shared for demonstration and hiring purposes only.  
Please do not reproduce or distribute without written permission.

