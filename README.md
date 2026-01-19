This is a sophisticated approach to technical hiring. By shifting the focus from "years of experience" to "forensic evidence of skill," you're addressing the core failure of modern Applicant Tracking Systems (ATS).

Below is a structured, professional, and high-impact **GitHub README.md** description tailored for this project.

---

# 🛡️ The Blind Auditor: Evidence-Based AI Recruitment Workflow

**Revolutionizing Technical Hiring through Forensic Analysis, Multi-Agent Debates, and n8n Automation.**

!

Traditional recruitment is broken. Candidates "hack" resumes with white-fonting, while brilliant engineers are often overlooked due to employment gaps or lack of buzzwords. **The Blind Auditor** is an n8n-powered workflow that treats a resume as a "claim" and external data (GitHub, portfolios) as "proof."

## 🚀 Key Features

### 🔍 Forensic Integrity Check

Automatically detects "white-fonting," metadata manipulation, and AI-generated keyword stuffing.

* **Action:** Instant rejection for fraudulent attempts.
* **Goal:** Ensure the integrity of the applicant pool from Step 1.

### 💻 The Technical Auditor (Evidence > Claims)

A specialized agent that bypasses employment dates to scrape and analyze raw external evidence.

* **Codebase Analysis:** Evaluates architecture (MVC, Clean Architecture, SOLID) and testing maturity.
* **Verification:** Cross-references resume skills against actual GitHub repository history.
* **Penalty/Boost Logic:** Heavy penalties for "ghost skills"; significant boosts for complex code found in modest resumes.

### ⚖️ The "Blind Debate" Protocol

To eliminate human and algorithmic bias, two distinct AI agents deliberate over the candidate:

* **The Skeptic:** Aggressively challenges "buzzword salad" and looks for inconsistencies.
* **The Advocate:** Identifies "Transferable Genius"—defending candidates who demonstrate high-level problem-solving despite unfamiliarity with a specific tech stack.

### 📉 Bias-Free Scoring

* **Zero-Gap Policy:** The system is programmatically forbidden from viewing or weighted employment gaps.
* **Complexity Tiers:** Candidates are categorized into tiers (Low, Mid, Senior, Elite) based on architectural depth, not tenure.

---

## 🛠️ Technical Architecture

The workflow is built on **n8n**, leveraging a multi-node architecture to ensure objective data processing.

| Stage | Tooling | Purpose |
| --- | --- | --- |
| **Ingestion** | Webhook / Google Drive | Triggers workflow on new PDF upload. |
| **Forensics** | Python / Regex Node | Scans for hidden text and metadata hacks. |
| **Audit** | GitHub API / LLM Agent | Scrapes and analyzes external proof of work. |
| **Debate** | Multi-Agent LLM (OpenAI/Anthropic) | Skeptic vs. Advocate reasoning logic. |
| **Output** | Google Sheets / Slack | Final scoring and detailed reasoning summary. |

---

## 📊 Scoring Rubric

The **Chief Technical Investigator** synthesizes the debate into a final scorecard:

| Score | Tier | Meaning |
| --- | --- | --- |
| **90-100** | **Elite** | Exceptional architectural depth; proven CI/CD and testing patterns. |
| **70-89** | **Senior** | Strong evidence of independent project delivery and clean code. |
| **50-69** | **Mid** | Competent execution; understands fundamentals but lacks scale. |
| **<50** | **Flagged** | Discrepancies between claims and evidence. |

---

## ⚙️ Setup & Installation

1. **Import Workflow:** Download the `blind_auditor_v1.json` and import it into your n8n instance.
2. **API Configuration:** * Add your **OpenAI/Anthropic** API keys.
* Connect your **GitHub Personal Access Token** for repository auditing.
* Link your **Google Sheets** for the final talent dashboard.


3. **Environment Variables:** Set your `FRAUD_THRESHOLD` and `COMPLEXITY_WEIGHTS` in the configuration node.

---

## ⚖️ Ethics & Bias Statement

This tool is designed to promote **meritocracy**. By stripping away names, dates, and gaps, it forces the evaluation to remain on the quality of logic and code.

---
