<div align="center">

<img src="https://img.shields.io/badge/RAHUL_MEDI-0d1117?style=for-the-badge&labelColor=0d1117&color=00c2ff&logo=github&logoColor=white" height="42"/>

# Software Engineer · Full-Stack · GenAI

**I build software that still works on a bad day.**
Production experience at a global SaaS company. Multi-agent AI with receipts.

![Location](https://img.shields.io/badge/📍_Bangalore,_India-0f2027?style=for-the-badge)
![Degree](https://img.shields.io/badge/🎓_B.E._ISE_·_CGPA_8.8-203a43?style=for-the-badge)
![Open](https://img.shields.io/badge/🟢_Open_to_entry--level_roles-2ea44f?style=for-the-badge)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-medi7/)
[![Email](https://img.shields.io/badge/rahulmedi33@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulmedi33@gmail.com)

</div>

---

```text
$ pytest rahul_medi/ -v

test_shipped_at_global_saas_company ................ PASSED
test_load_tested_apis_at_200_users ................. PASSED
test_contract_tests_catch_breaking_changes ......... PASSED
test_ai_pipeline_survives_llm_outage ............... PASSED
test_can_explain_every_line_of_my_resume ........... PASSED

5 passed, 0 failed, 1 pending: your_team.py
```

<div align="center">

| ⚡ **200** | 🧪 **2,517** | 🔌 **26** | 🏢 **2** |
|:---:|:---:|:---:|:---:|
| concurrent users in k6 load tests | pytest tests in CareerPilot AI | REST APIs in CareerPilot AI | internships completed |

</div>

---

## 👋 The short version

I'm a 2026 B.E. graduate (Information Science & Engineering). At **Diligent Corporation**, a global SaaS company, my work was less about new features and more about making sure existing ones didn't fall over: migrating a production SPA, fixing authentication failures, load testing APIs and writing contract tests.

Outside work, I build AI tools that have to show their evidence. Three things matter to me:

> **Evidence**: an AI answer should point to its source.
> **Resilience**: a system should degrade, not crash.
> **Proof**: if I say it works, there's a test or a load run behind it.

---

## 🚀 Projects

<div align="center">

| 🧭 [**CareerPilot AI**](https://github.com/RahulMedi07/CareerPilotAI) | ☁️ [**Attendance System**](https://github.com/RahulMedi07/Cloud-Based-Attendence-System) | 🎙️ [**Parkinson's Detection**](https://github.com/RahulMedi07/Early-Detection-Of-Parkinsons-Disease-Using-Voice-Data) |
|:---:|:---:|:---:|
| Multi-agent job match and interview prep | MERN college ERP with role-based access | Voice-based risk prediction |
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) | ![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Node](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |

</div>

### 🧭 CareerPilot AI
*Paste a CV and a job advert. Get a match score, the skill gaps, a tailored CV rewrite and interview prep.*

```mermaid
flowchart LR
    A["CV + job advert"] --> B["Embed CV"]
    B --> C[("ChromaDB")]
    C --> D["Match each skill to the CV line that proves it"]
    D --> E{"LLM available?"}
    E -- yes --> F["Gemini / Claude / Ollama"]
    E -- "no, or retries fail" --> G["Deterministic rules"]
    F --> H["Score, gaps, CV rewrite, interview prep"]
    G --> H
```
<sub>Simplified view. The real pipeline is an 8-node LangGraph graph served by FastAPI.</sub>

- 🔎 **Evidence first:** every matched skill is traced to a line in the CV through RAG over ChromaDB. If the CV doesn't prove it, the tool doesn't claim it.
- 🛟 **Always finishes:** retry-with-exponential-backoff, then deterministic fallbacks, so an LLM outage doesn't stop the analysis.
- 🔐 **26 REST APIs**, PBKDF2 password hashing, hashed session tokens and **2,517 pytest tests**.
- 🖥️ Next.js and TypeScript frontend, SQLite storage.

### ☁️ Cloud-Based Attendance System
A MERN college ERP with separate roles for admins, faculty and students. Faculty mark attendance, create tests and upload marks, and the system calculates attendance percentage by subject. JWT authentication, bcrypt hashing.

### 🎙️ Early Detection of Parkinson's Disease
A Streamlit app that takes a voice recording (live mic or WAV) and predicts risk from jitter, shimmer and HNR features extracted with Praat. It's a small dataset (195 samples), so I focused on a sound evaluation setup (stratified 5-fold cross-validation, class-imbalance handling) rather than chasing a headline accuracy number.

---

## 💼 What I actually did at Diligent

| The problem | What I did |
|---|---|
| An important reporting page was on an older SPA | Led the migration of "My Reports" to Reports Builder, from requirements analysis to AWS CI/CD deployment |
| The MCP gateway kept failing with 401/404 errors | Added JWT validation and retry-with-exponential-backoff logic |
| Nobody knew how the APIs behaved under load | Ran k6 load tests at up to 200 virtual users and read P50/P95/P99 latency in AWS CloudWatch |
| Python and Node.js services could drift apart | Built Pact consumer-driven contract tests so breaking changes fail before release |

*Software Development Intern · Diligent Corporation · Mar 2026 – Sep 2026*
*Full Stack Web Development Intern · SuprMentr Technologies · Dec 2025 – Feb 2026: a React, Node.js, Express and MongoDB finance app with JWT auth and an aggregation-pipeline dashboard.*

---

## 🧠 Ask me about

- Why retry logic needs **backoff**, and what happens without it
- Why **P95 and P99 latency** tell you more than the average
- What **contract testing** catches that integration tests miss
- How to make a **RAG system cite its evidence**
- What an AI app should do **when the model is down**

---

## 🛠️ Toolbox

<div align="center">

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

| | |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, C++, SQL |
| **Web & APIs** | React, Next.js, Node.js, Express, FastAPI, REST APIs, JWT |
| **AI / GenAI** | LangGraph, LangChain, RAG, ChromaDB, embeddings, Gemini, Claude, Ollama, MCP, prompt engineering |
| **Data & ML** | MongoDB, SQLite, scikit-learn, Pandas, NumPy |
| **Quality** | Pact, k6, pytest, API testing |
| **Cloud** | AWS (CI/CD, CloudWatch), Git, GitHub, GitHub Actions |
| **Foundations** | DSA, OOP, operating systems, computer networks, DBMS, SDLC |

<details>
<summary>📜 Certifications</summary>

- Google Cloud Career Launchpad (Cloud Engineer Track), Google
- Cloud Computing, NPTEL
- Artificial Intelligence & Machine Learning, Coursera

</details>

---

<div align="center">

### 📫 If your team needs someone who tests before shipping, let's talk.

[![Email me](https://img.shields.io/badge/Email_me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rahulmedi33@gmail.com)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-medi7/)

</div>
