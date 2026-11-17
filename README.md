```text
┌──────────────────────────────────────────────────┐
│ RAHUL MEDI                        > OPEN TO WORK │
├──────────────────────────────────────────────────┤
│ role     Software Engineer · Full-Stack · GenAI  │
│ based    Bangalore, India                        │
│ shipped  at a global SaaS company                │
│ proof    2,517 tests · 200 users · 26 APIs       │
│ degree   B.E. ISE · 2026 · CGPA 8.8              │
│ looking  entry-level SWE · Full-Stack · AI       │
│ reach    rahulmedi33@gmail.com                   │
└──────────────────────────────────────────────────┘
```

**I build software that still works on a bad day.**

🌐 [Portfolio](https://myportfolio-rahulmedi.vercel.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/rahul-medi7/) · ✉️ [Email](mailto:rahulmedi33@gmail.com)

---

## ✅ My definition of done

- [x] It has tests
- [x] It has been load tested (k6, P50 / P95 / P99)
- [x] It fails gracefully: fallbacks, not crashes
- [x] Its AI answers point to their source
- [x] I can explain how every part works

---

## 🧩 Services I've built

| Service | What it does | Stack | Proof |
|---|---|---|---|
| [**CareerPilot AI**](https://github.com/RahulMedi07/CareerPilotAI) | Compares a CV with a job advert and returns a match score, skill gaps, a CV rewrite and interview prep | Python · FastAPI · LangGraph · ChromaDB · Next.js · TypeScript | 2,517 tests · 26 REST APIs |
| [**Attendance System**](https://github.com/RahulMedi07/Cloud-Based-Attendence-System) | MERN college ERP with separate roles for admins, faculty and students | React · Node.js · Express · MongoDB | JWT + bcrypt · per-subject attendance % |
| [**Parkinson's Detection**](https://github.com/RahulMedi07/Early-Detection-Of-Parkinsons-Disease-Using-Voice-Data) | Predicts risk from a voice recording (live mic or WAV) | Python · scikit-learn · Streamlit · Praat | Stratified 5-fold CV on 195 samples |

### How CareerPilot behaves when the LLM is down

```text
LLM call ............... timeout
retry with backoff ..... timeout
fallback rules ......... OK
analysis ............... completed
```
<sub>Illustrative. The real pipeline retries with exponential backoff across Gemini, Claude and Ollama, then falls back to deterministic rules, so an outage never stops the analysis.</sub>

**Evidence first:** every matched skill is traced to a line in the CV through RAG over ChromaDB. If the CV doesn't prove a skill, the tool doesn't claim it.

---

## 📦 Release notes

### v2026.09 · Diligent Corporation · Mar 2026 – Sep 2026
**Changed:** led the migration of the "My Reports" SPA to Reports Builder, from requirements analysis to AWS CI/CD deployment
**Fixed:** recurring MCP gateway 401/404 failures with JWT validation and retry-with-backoff logic
**Tested:** k6 load tests on BoardRisk, SP500 and Risk Manager REST APIs at up to 200 virtual users, tracking P50/P95/P99 latency in AWS CloudWatch
**Guarded:** Pact consumer-driven contract tests across Python and Node.js clients, so breaking changes fail before release

### v2025.12 · SuprMentr Technologies · Dec 2025 – Feb 2026
**Added:** Expense Tracker, a React, Node.js, Express and MongoDB finance app with JWT authentication and an aggregation-pipeline dashboard

---

## 🚧 Next release (in progress)

- [ ] Dockerize CareerPilot AI and run its pytest suite in GitHub Actions
- [ ] Deploy CareerPilot AI with a live demo
- [ ] Build a PostgreSQL-backed project
- [ ] Daily DSA and system-design practice

---

<details>
<summary><b>🧠 Ask me about</b></summary>

- Why retry logic needs **backoff**, and what happens without it
- Why **P95 and P99 latency** tell you more than the average
- What **contract testing** catches that integration tests miss
- How to make a **RAG system cite its evidence**
- What an AI app should do **when the model is down**

</details>

<details>
<summary><b>🛠️ Toolbox</b></summary>

| | |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, C++, SQL |
| **Web & APIs** | React, Next.js, Node.js, Express, FastAPI, REST APIs, JWT |
| **AI / GenAI** | LangGraph, LangChain, RAG, ChromaDB, embeddings, Gemini, Claude, Ollama, MCP, prompt engineering |
| **Data & ML** | MongoDB, SQLite, scikit-learn, Pandas, NumPy |
| **Quality** | Pact, k6, pytest, API testing |
| **Cloud** | AWS (CI/CD, CloudWatch), Git, GitHub, GitHub Actions |
| **Foundations** | DSA, OOP, operating systems, computer networks, DBMS, SDLC |

*Certifications: Google Cloud Career Launchpad (Cloud Engineer Track) · Cloud Computing (NPTEL) · AI & Machine Learning (Coursera)*

</details>

---

<p align="center">
  <b>If your team needs someone who tests before shipping, let's talk.</b><br>
  <a href="mailto:rahulmedi33@gmail.com">rahulmedi33@gmail.com</a> ·
  <a href="https://myportfolio-rahulmedi.vercel.app/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/rahul-medi7/">LinkedIn</a>
</p>
