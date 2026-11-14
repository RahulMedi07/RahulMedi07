<h1 align="center">Rahul Medi</h1>
<p align="center">
  Software engineer from Bangalore who likes software that still works on a bad day.<br>
  Full-stack · GenAI · testing &amp; reliability
</p>

```text
$ pytest rahul_medi/ -v

test_shipped_to_production_at_global_saas ............ PASSED
test_load_tested_apis_at_200_virtual_users ........... PASSED
test_contract_tests_catch_breaking_changes ........... PASSED
test_ai_pipeline_survives_llm_outage ................. PASSED
test_can_explain_every_line_of_my_resume ............. PASSED

5 passed, 0 failed, 1 pending: your_team.py
```

<p align="center">
  <a href="https://www.linkedin.com/in/rahul-medi7/">LinkedIn</a> ·
  <a href="mailto:rahulmedi33@gmail.com">rahulmedi33@gmail.com</a> ·
  Bangalore, India · Open to entry-level Software Engineer, Full-Stack and AI Engineer roles
</p>

---

## The short version

I'm a 2026 B.E. graduate (Information Science & Engineering, CGPA 8.8). I spent six months at **Diligent Corporation**, a global SaaS company, where my work was less about writing new features and more about making sure existing ones didn't fall over. Outside work, I build AI tools that have to be honest about what they know.

I care about three things: **evidence** (an AI answer should point to its source), **resilience** (a system should degrade, not crash), and **proof** (if I say it works, there's a test or a load run behind it).

---

## What I built

### CareerPilot AI
*Paste a CV and a job advert. Get a match score, the skill gaps, a tailored CV rewrite and interview prep.*

**[View the repo →](https://github.com/RahulMedi07/CareerPilotAI)**

```mermaid
flowchart LR
    A["CV + job advert"] --> B["Embed CV"]
    B --> C[("ChromaDB")]
    C --> D["Match each skill to the CV line that proves it"]
    D --> E{"LLM available?"}
    E -- yes --> F["Gemini / Claude / Ollama"]
    E -- "no, or retries fail" --> G["Deterministic rules"]
    F --> H["Match score, gaps, CV rewrite, interview prep"]
    G --> H
```
<sub>A simplified view. The real pipeline is an 8-node LangGraph graph served by FastAPI.</sub>

**Decisions I'm happy to defend in an interview**
- **Every matched skill is traced to a line in the CV** (RAG over ChromaDB). If the CV doesn't prove a skill, the tool doesn't claim it.
- **The pipeline always finishes.** If the LLM is down, it falls back to deterministic rules, after retrying with exponential backoff.
- **26 REST APIs and 2,517 pytest tests**, with PBKDF2-hashed passwords and hashed session tokens.

`Python` `FastAPI` `LangGraph` `ChromaDB` `Next.js` `TypeScript` `SQLite`

### Cloud-Based Attendance System
A MERN college ERP with separate roles for admins, faculty and students. Faculty mark attendance, create tests and upload marks, and the system calculates each student's attendance percentage by subject. JWT auth, bcrypt hashing.
**[View the repo →](https://github.com/RahulMedi07/Cloud-Based-Attendence-System)**

### Early Detection of Parkinson's Disease
A Streamlit app that takes a voice recording (live mic or WAV) and predicts risk from jitter, shimmer and HNR features extracted with Praat. It's a small-data project (195 samples), so I spent my effort on a sound evaluation setup (stratified 5-fold cross-validation, class-imbalance handling) rather than chasing a headline accuracy number.
**[View the repo →](https://github.com/RahulMedi07/Early-Detection-Of-Parkinsons-Disease-Using-Voice-Data)**

---

## What I actually did at Diligent

| The problem | What I did |
|---|---|
| An important reporting page was on an older SPA | Led the migration of "My Reports" to Reports Builder, from requirements analysis to AWS CI/CD deployment |
| The MCP gateway kept failing with 401/404 errors | Added JWT validation and retry-with-exponential-backoff logic |
| Nobody knew how the APIs behaved under load | Ran k6 load tests at up to 200 virtual users and read P50/P95/P99 latency in AWS CloudWatch |
| Python and Node.js services could drift apart | Built Pact consumer-driven contract tests so breaking changes fail before release |
| Production bugs: duplicate API calls, wrong report counts | Root-cause analysis and regression testing |

*Earlier, at SuprMentr Technologies (Dec 2025 – Feb 2026): a full-stack finance app in React, Node.js, Express and MongoDB, with JWT auth and an aggregation-pipeline dashboard.*

---

## Ask me about

- Why retry logic needs **backoff**, and what happens without it
- Why **P95 and P99 latency** tell you more than the average
- What **contract testing** catches that integration tests miss
- How to make a **RAG system cite its evidence**
- What an AI app should do **when the model is down**

---

## Toolbox

| | |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, C++, SQL |
| **Web** | React, Next.js, Node.js, Express, FastAPI, REST APIs, JWT |
| **AI** | LangGraph, LangChain, RAG, ChromaDB, embeddings, LLM APIs (Gemini, Claude, Ollama), prompt engineering, MCP |
| **Data & ML** | MongoDB, SQLite, scikit-learn, Pandas, NumPy |
| **Quality** | Pact, k6, pytest, API testing |
| **Cloud** | AWS (CI/CD, CloudWatch), Git, GitHub |
| **Foundations** | DSA, OOP, operating systems, computer networks, DBMS, SDLC |

*Certifications: Google Cloud Career Launchpad (Cloud Engineer Track) · Cloud Computing (NPTEL) · AI & Machine Learning (Coursera)*

---

<p align="center">
  <b>If your team needs someone who tests before shipping, let's talk.</b><br>
  <a href="mailto:rahulmedi33@gmail.com">rahulmedi33@gmail.com</a> ·
  <a href="https://www.linkedin.com/in/rahul-medi7/">LinkedIn</a>
</p>
