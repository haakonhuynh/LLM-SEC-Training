SEC-Based Prompt Collection for LLMs

This repository outlines a scalable, quality-first data collection system designed to generate high-quality financial prompts and answers from U.S. SEC filings (10-K and 10-Q). The project supports the development and evaluation of large language models (LLMs) by producing document-grounded, factual QA pairs with verifiable reasoning across corporate financial reports.

📌 Overview

This project addresses the growing need for complex, real-world prompt–response datasets grounded in regulated financial disclosures. The design prioritizes:

Worker stratification by skill level
Prompt variety and complexity
Peer-reviewed QA pipelines
Compensation aligned with task difficulty and quality
Topical coverage across industries and filing types

🧭 Table of Contents

Qualification Framework
Annotation Workflow
Quality Assurance Process
Compensation Model

1. Qualification Framework

Contributors are stratified through a two-phase qualification system:

Phase 1 – Baseline Skills
Simple factual prompts from a single 10-K filing (e.g., NVIDIA)
Tests document literacy and financial comprehension
Phase 2 – Multi-Document Analysis
Complex comparison prompts using 10-Qs from General Motors, Ford, and Tesla
Evaluates analytical depth, synthesis, and precision
🔍 Pass Criteria: Citation accuracy, clarity of reasoning, and structure

2. Annotation Workflow

Workers generate prompts in three categories:

Category	Description	Task Type	Time (est.)
A	Simple factual questions from 1 document	Easy	6–8 mins
B	Analytical prompts from 1 document	Moderate	10–12 mins
C	Comparative questions across 2–5 docs	Advanced	20–25 mins
A centralized Google Sheet provides vetted SEC filings by:

Company
Filing type (10-K or 10-Q)
Filing date (Oct 2023 or later)
Direct SEC URL and saved PDF
3. Quality Assurance Process

The QA system includes:

Peer Review: Tiered reviewer qualifications for each category
Spot Audits: Random audits by the project manager to ensure consistency
Reviewer Ratings: 1–5 scale with clear revision guidance
Corrective Action: Feedback, temporary suspensions, and deactivation for low-performing workers
🔁 Mid-quality submissions (rated 3) are returned for revision with structured feedback.

4. Compensation Model

Task Type	Rate	Hourly (est.)
Category A	$2.00	~$17/hr
Category B	$3.25	~$17.75/hr
Category C	$8.25	~$22/hr
Bonuses:

🎯 Accuracy Bonus: $5 for 5+ prompts with average rating ≥ 4.5
⚙️ Complexity Bonus: $10 for 5+ Category C completions
This hybrid system balances fairness, performance incentives, and annotation throughput.



🔗 License

This project is proprietary and distributed solely for demonstration and hiring purposes. Do not reproduce or redistribute without written permission.
