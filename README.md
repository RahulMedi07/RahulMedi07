<div align="center">

<img src="assets/banner.svg" alt="Rahul Medi: Software Engineer, Full-Stack, GenAI. Open to entry-level roles in Bangalore" width="100%"/>

<p>
<a href="https://myportfolio-rahulmedi.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-00c2ff?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/rahul-medi7/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rahulmedi33@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<img src="assets/metrics.svg" alt="200 concurrent users in k6 load tests, 2,517 pytest tests, 26 REST APIs, 2 internships" width="100%"/>

</div>

## 👋 About

I'm a 2026 B.E. graduate (Information Science & Engineering, CGPA 8.8). At **Diligent Corporation**, a global SaaS company, my work was less about new features and more about making sure existing ones didn't fall over: migrating a production SPA, fixing authentication failures, load testing APIs and writing contract tests.

Outside work, I build AI tools that have to show their evidence.

## ✅ My definition of done

- [x] It has tests
- [x] It has been load tested (k6, P50 / P95 / P99)
- [x] It fails gracefully: fallbacks, not crashes
- [x] Its AI answers point to their source
- [x] I can explain how every part works

## 🧩 Featured work

<p align="center">
<a href="https://github.com/RahulMedi07/CareerPilotAI"><img src="assets/project-careerpilot.svg" alt="CareerPilot AI: multi-agent job match and interview prep" width="100%"/></a>
</p>
<p align="center">
<a href="https://github.com/RahulMedi07/Cloud-Based-Attendence-System"><img src="assets/project-attendance.svg" alt="Cloud-Based Attendance System: MERN college ERP" width="100%"/></a>
</p>
<p align="center">
<a href="https://github.com/RahulMedi07/Early-Detection-Of-Parkinsons-Disease-Using-Voice-Data"><img src="assets/project-parkinsons.svg" alt="Early Detection of Parkinson's Disease from voice data" width="100%"/></a>
</p>

**Inside CareerPilot AI:** an 8-node LangGraph pipeline behind FastAPI. RAG over ChromaDB traces every matched skill to the CV line that proves it, and if the CV doesn't prove a skill, the tool doesn't claim it. LLM calls (Gemini, Claude, Ollama) retry with exponential backoff, then fall back to deterministic rules, so an outage never stops the analysis.

## 💼 Experience

**🏢 Software Development Intern · Diligent Corporation** `Mar 2026 – Sep 2026`
- Led the migration of the "My Reports" SPA to Reports Builder, from requirements analysis to AWS CI/CD deployment
- Fixed recurring MCP gateway 401/404 failures with JWT validation and retry-with-backoff logic
- Ran k6 load tests on BoardRisk, SP500 and Risk Manager REST APIs at up to 200 virtual users, tracking P50/P95/P99 latency in AWS CloudWatch
- Built Pact consumer-driven contract tests across Python and Node.js clients so breaking changes fail before release

**💻 Full Stack Web Development Intern · SuprMentr Technologies** `Dec 2025 – Feb 2026`
- Built Expense Tracker, a React, Node.js, Express and MongoDB finance app with JWT authentication and an aggregation-pipeline dashboard

## 🛠️ Toolbox

<p align="center">
<img src="assets/stack.svg" alt="Toolbox: Python, JavaScript, TypeScript, C++, SQL, React, Next.js, Node.js, FastAPI, LangGraph, LangChain, RAG, ChromaDB, MongoDB, scikit-learn, Pact, k6, pytest, AWS" width="100%"/>
</p>

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

<p align="center">
<a href="mailto:rahulmedi33@gmail.com"><img src="assets/footer.svg" alt="If your team needs someone who tests before shipping, let's talk. rahulmedi33@gmail.com" width="100%"/></a>
</p>
