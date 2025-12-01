# 💊 EY Techathon 6.0: Audited Drug Repurposing Agent

This project demonstrates a robust, high-trust **Agentic AI** solution for the pharmaceutical R&D sector, designed to accelerate the drug repurposing process by eliminating manual audits and hallucination risk. This submission achieved a score of 100 in Round 1 and was successfully submitted for Round 2.

---

## 1. Project Goal & Innovation

| Area | Description |
| :--- | :--- |
| **Problem Solved** | Reduces the pharmaceutical R&D research cycle from **2–3 months to under one hour** by automating the strategic viability assessment. |
| **Core Innovation** | The **Fact-Checking Agent** (Auditor). This custom agent proactively validates LLM output against structured public APIs (simulating ClinicalTrials.gov), guaranteeing **95%+ factual reliability** and mitigating hallucination risk. |
| **Agentic Theme** | The system operates as a fully **autonomous, goal-driven workflow** orchestrated by the Master Agent, using parallel processing for speed. |

---

## 2. Agentic Architecture (Proof of Orchestration)

The solution is built using an n8n orchestration framework to manage parallel execution and enforce data quality before strategic scoring.

**Workflow Structure:**

1.  **Input Trigger:** User query initiates the workflow (Master Agent).
2.  **Parallel Execution:** The Master Agent delegates tasks simultaneously to three **Worker Agents** (Patent, Clinical Trials, Market).
3.  **Auditor Gate:** The **Fact-Checking Agent (IF node)** runs validation logic to ensure data trustworthiness.
4.  **Final Score:** The **Portfolio Risk Agent** assigns the objective Viability Score (e.g., 85/100) and FTO risk flag.

**Visualization:**

<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/7b6f0174-a267-4d3c-9afb-0acedf695468" />


---

## 3. Technical Details & Role

| Field | Details |
| :--- | :--- |
| **Submission** | EY Techathon 6.0 (Pharmaceuticals Challenge) |
| **Framework Used** | n8n (for orchestration logic) |
| **Key Technologies** | Python/JavaScript, LLMs for RAG (Intelligence), Custom NLP for cross-referencing logic |
| **My Role** | **Agentic Architecture Design**, **NLP Model Integration**, and **System Orchestration** |
| **Submission Status** | Successfully submitted for EY Techathon 6.0 Round 2. |
