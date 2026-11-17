<div align="center">

# Rahul Medi

### Software Engineer · Full-Stack · GenAI

*I build software that still works on a bad day.*

<p>
<img src="https://img.shields.io/badge/OPEN_TO_WORK-entry--level_roles-2ea44f?style=for-the-badge" alt="Open to work, entry-level roles"/>
<img src="https://img.shields.io/badge/Bangalore-India-203a43?style=for-the-badge" alt="Bangalore, India"/>
<img src="https://img.shields.io/badge/B.E._ISE-CGPA_8.8-203a43?style=for-the-badge" alt="B.E. ISE, CGPA 8.8"/>
</p>

<p>
<a href="https://myportfolio-rahulmedi.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-00c2ff?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/rahul-medi7/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rahulmedi33@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

</div>

---

<div align="center">

| <h2>200</h2> | <h2>2,517</h2> | <h2>26</h2> | <h2>2</h2> |
|:---:|:---:|:---:|:---:|
| concurrent users<br>in k6 load tests | pytest tests<br>in CareerPilot AI | REST APIs<br>in CareerPilot AI | internships<br>SaaS + startup |

</div>

---

## 👋 About

I'm a 2026 B.E. graduate (Information Science & Engineering). At **Diligent Corporation**, a global SaaS company, my work was less about new features and more about making sure existing ones didn't fall over: migrating a production SPA, fixing authentication failures, load testing APIs and writing contract tests.

Outside work, I build AI tools that have to show their evidence.

## ✅ My definition of done

- [x] It has tests
- [x] It has been load tested (k6, P50 / P95 / P99)
- [x] It fails gracefully: fallbacks, not crashes
- [x] Its AI answers point to their source
- [x] I can explain how every part works

## 🧩 Featured work

### 🧭 [CareerPilot AI](https://github.com/RahulMedi07/CareerPilotAI): multi-agent job match & interview prep
> Paste a CV and a job advert. Get a match score, skill gaps, a tailored CV rewrite and interview prep.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

- 🔎 **Evidence first:** RAG over ChromaDB traces every matched skill to the CV line that proves it. If the CV doesn't prove it, the tool doesn't claim it.
- 🛟 **Always finishes:** Gemini, Claude and Ollama calls retry with exponential backoff, then fall back to deterministic rules, so an outage never stops the analysis.
- 🔐 **26 REST APIs**, an 8-node LangGraph pipeline, PBKDF2 password hashing and **2,517 pytest tests**.

### ☁️ [Cloud-Based Attendance System](https://github.com/RahulMedi07/Cloud-Based-Attendence-System)
> A MERN college ERP with separate roles for admins, faculty and students.

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens&logoColor=white)

- Faculty mark attendance, create tests and upload marks; attendance percentage is calculated per subject
- JWT authentication with bcrypt password hashing

### 🎙️ [Early Detection of Parkinson's Disease](https://github.com/RahulMedi07/Early-Detection-Of-Parkinsons-Disease-Using-Voice-Data)
> A Streamlit app that predicts risk from a voice recording (live mic or WAV).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Praat](https://img.shields.io/badge/Praat-6e40c9?style=flat-square)

- Praat jitter, shimmer and HNR features, with a Logistic Regression pipeline
- Small dataset (195 samples), so I focused on honest evaluation: stratified 5-fold cross-validation and class-imbalance handling

## 💼 Experience

**🏢 Software Development Intern · Diligent Corporation** `Mar 2026 – Sep 2026`
- Led the migration of the "My Reports" SPA to Reports Builder, from requirements analysis to AWS CI/CD deployment
- Fixed recurring MCP gateway 401/404 failures with JWT validation and retry-with-backoff logic
- Ran k6 load tests on BoardRisk, SP500 and Risk Manager REST APIs at up to 200 virtual users, tracking P50/P95/P99 latency in AWS CloudWatch
- Built Pact consumer-driven contract tests across Python and Node.js clients so breaking changes fail before release

**💻 Full Stack Web Development Intern · SuprMentr Technologies** `Dec 2025 – Feb 2026`
- Built Expense Tracker, a React, Node.js, Express and MongoDB finance app with JWT authentication and an aggregation-pipeline dashboard

## 🛠️ Toolbox

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square) |
| **Web & APIs** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![REST](https://img.shields.io/badge/REST_APIs-0A66C2?style=flat-square) ![JWT](https://img.shields.io/badge/JWT-black?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **AI / GenAI** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-6e40c9?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square) ![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square) ![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square) ![Ollama](https://img.shields.io/badge/Ollama-333333?style=flat-square) ![MCP](https://img.shields.io/badge/MCP-0d1117?style=flat-square) |
| **Data & ML** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Quality** | ![Pact](https://img.shields.io/badge/Pact-F05032?style=flat-square) ![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![API testing](https://img.shields.io/badge/API_testing-2ea44f?style=flat-square) |
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square) ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

*Certifications: Google Cloud Career Launchpad (Cloud Engineer Track) · Cloud Computing (NPTEL) · AI & Machine Learning (Coursera)*

## 🚧 Next release (in progress)

- [ ] Dockerize CareerPilot AI and run its pytest suite in GitHub Actions
- [ ] Deploy CareerPilot AI with a live demo
- [ ] Build a PostgreSQL-backed project
- [ ] Daily DSA and system-design practice

<details>
<summary><b>🧠 Ask me about</b></summary>

- Why retry logic needs **backoff**, and what happens without it
- Why **P95 and P99 latency** tell you more than the average
- What **contract testing** catches that integration tests miss
- How to make a **RAG system cite its evidence**
- What an AI app should do **when the model is down**

</details>

---

<div align="center">

### If your team needs someone who tests before shipping, let's talk.

<a href="mailto:rahulmedi33@gmail.com"><img src="https://img.shields.io/badge/Email_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"/></a>
<a href="https://www.linkedin.com/in/rahul-medi7/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/></a>
<a href="https://myportfolio-rahulmedi.vercel.app/"><img src="https://img.shields.io/badge/View_portfolio-00c2ff?style=for-the-badge&logo=vercel&logoColor=black" alt="View portfolio"/></a>

</div>
