# AI Rater Portfolio

A focused portfolio of **AI evaluation** work: search-quality style ratings, LLM response grading, safety evaluation, and dataset labeling artifacts—organized like a real rater/evaluation ops project.

> If you’re reviewing this repo for hiring: start with **“Start Here”** and the **Case Study** below.

---

## Start here (best proof)

### 1) Search Quality / Intent Evaluation
- **Search Quality Rater Simulation** (rubric + templates + rated examples)  
  https://github.com/Parker-Bakken/search-quality-rater-simulation
- **Search Intent Dataset** (taxonomy + ambiguous set + calibration artifacts)  
  https://github.com/Parker-Bakken/search-intent-dataset
- **AI Search Quality Evaluator (Python)** (reproducible scoring baseline)  
  https://github.com/Parker-Bakken/ai-search-quality-evaluator

### 2) LLM Truthfulness / Hallucination
- **LLM Hallucination Detection Benchmark (Mini)** (labels + guidelines + tooling)  
  https://github.com/Parker-Bakken/llm-hallucination-detection-benchmark

### 3) General AI Response Grading + Safety
- **AI Response Evaluation** (rubric + templates + examples)  
  https://github.com/Parker-Bakken/ai-response-evaluation
- **AI Evaluation Examples** (prompt quality / safety / hallucination cases)  
  https://github.com/Parker-Bakken/ai-evaluation-examples

### 4) Dataset Labeling Samples
- **Dataset Labeling Examples** (ML-ready CSVs + guidelines patterns)  
  https://github.com/Parker-Bakken/dataset-labeling-examples

---

## What this portfolio demonstrates

- **Rubric design** for consistent, repeatable evaluation
- **Intent interpretation** (what the user is *actually* trying to do)
- **Correctness + grounding** (supported vs unverifiable vs fabricated claims)
- **Safety evaluation** (appropriate refusals, risk-aware grading)
- **Operational thinking**: calibration, QA logging, adjudication, and reporting

---

## Case Study: How I evaluate (rater workflow)

### 1) Interpret the user intent
- Identify the task type (informational / navigational / transactional / local)
- Note constraints (format, tone, scope, safety, time sensitivity)

### 2) Judge usefulness + completeness
- Does the response solve the user’s problem?
- Is anything missing that a high-quality answer should include?

### 3) Verify correctness & grounding
- Are claims supported by the prompt/context?
- If not verifiable, is uncertainty clearly stated (instead of guessing)?

### 4) Apply a rubric consistently
Typical dimensions:
- Intent match
- Helpfulness / completeness
- Correctness
- Grounding / evidence quality
- Safety / refusal quality
- Clarity / structure

### 5) QA & calibration (portfolio-grade approach)
- Double-pass review on a subset
- Log disagreements + reasons
- Adjudicate edge cases
- Convert recurring disagreements into rubric clarifications + gold set examples

---

## Repo structure (recommended)

This repository is intended as an index + packaging layer for the portfolio.  
If present, these folders support a rater ops workflow:

- `CASE_STUDY.md` — deeper narrative of my evaluation process
- `rubrics/` — reusable rubrics and scoring guidance
- `templates/` — copy/paste evaluation templates
- `examples/` — curated “best of” evaluation writeups
- `qa/qa_log.csv` — disagreement/adjudication tracking
- `gold/gold_set.csv` — finalized edge-case examples for calibration
- `reports/scorecard.md` — metrics snapshot for quick review

---

## Notes for reviewers

- This portfolio is designed to be **auditable**: clear criteria, labeled examples, and reproducible artifacts.
- Where uncertainty exists, I prefer **transparent reasoning** over confident guessing.
- I treat “edge cases” as first-class: they’re documented, adjudicated, and used to improve rubric clarity.

---

## Contact
- GitHub: https://github.com/Parker-Bakken
- (Add email / LinkedIn here if you want fast recruiter contact.)
