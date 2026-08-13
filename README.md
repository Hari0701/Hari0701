<div align="center">
  <img src="https://user-images.githubusercontent.com/68813522/199673160-50a160ef-2154-48a8-8a13-6e247c52f39d.png" alt="Header" width="100%"/>
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2E9EF7&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B%2C+I'm+Hariharan;Applied+AI+Engineer;Document+Intelligence+%26+RAG+on+Azure;Full-Stack+%7C+Web%2C+iOS+%26+Android" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=hari0701&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="profile views" />
  <img src="https://img.shields.io/github/followers/hari0701?label=Followers&style=for-the-badge&color=blue" alt="followers" />
  <img src="https://img.shields.io/github/stars/hari0701?label=Stars&style=for-the-badge&color=yellow" alt="stars" />
</p>

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=F75C7E&center=true&vCenter=true&width=500&lines=OCR+%E2%86%92+extraction+%E2%86%92+validation+%E2%86%92+structured+data;RAG+with+answers+traceable+to+the+source;Azure+Functions+%7C+Cosmos+DB+%7C+Service+Bus;Requirements+to+production%2C+end+to+end)](https://git.io/typing-svg)

</div>

---

## 👨‍💻 About Me

<img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/devSouvik/devSouvik/master/gif3.gif">

- 🔭 **Currently:** Applied AI Engineer at **Infiligence Technologies**

- 📄 **What I actually build:** document-intelligence pipelines — ingestion, OCR,
  classification, LLM extraction, validation, structured output — with confidence
  scoring and human review where the model isn't sure

- 🔎 **And:** RAG systems where every answer traces back to the source document

- ☁️ **On:** Azure Functions, App Service, Cosmos DB, Service Bus, Blob Storage,
  Application Insights — event-driven so long-running AI jobs survive restarts

- 🧱 **Full-stack too:** React / Next.js, Node / NestJS / FastAPI / .NET,
  React Native & Flutter — web, iOS and Android shipped end to end

- 🛠️ **I own delivery:** requirements → architecture → CI/CD → monitoring →
  production support. Primary engineer on multiple client deliveries.

- 🌍 **Fully remote** throughout my career, across time zones

- 💬 **Ask me about:** RAG that doesn't hallucinate, extracting fields from
  documents that were never designed to be parsed, keeping AI jobs idempotent

- 📫 **Reach me:** [hari07.at@gmail.com](mailto:hari07.at@gmail.com)

- ⚡ **Fun fact:** I wrote an operating system that explains itself while running

<br clear="both">

---

## 🚀 Featured Project

### [5AM-OS](https://github.com/Hari0701/5AM-OS) — an x86_64 kernel that explains itself

A teaching operating system in Rust, `#![no_std]`, one dependency. It narrates
its own boot and reads live CPU state to explain what's under you — `explain gdt`
walks the CPU's actual descriptor table and decodes the real bytes.

- **Two swappable slots.** The scheduler (5 policies) and page replacement
  (4 policies) sit behind narrow contracts. Change them from the shell *while the
  machine runs*, then measure the difference.
- **Arguments become measurements.** `bench sched` and `bench paging` reproduce
  Bélády's anomaly on real page tables — FIFO taking **more** page faults when
  given **more** memory, at the 1969 paper's own numbers.
- **108 self-tests that run inside the machine**, because that's the only honest
  place to check whether a page really got mapped.
- **A 15M-parameter Llama-2 transformer running in ring 0** — no BLAS, no libm,
  no allocator on the inference path.
- **Nine labs** that delete a working function and ask for it back.

`Rust` · `no_std` · `x86_64` · paging · COW · demand paging · swapping · ELF ·
FAT16 · ring 3 · syscalls · signals · SMP bring-up

---

## 🛠️ Tech Stack

<div align="center">

### AI / ML
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Document Intelligence](https://img.shields.io/badge/AI_Document_Intelligence-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Anthropic_Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

![RAG](https://img.shields.io/badge/RAG-2E9EF7?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Embeddings_&_Vector_Search-2E9EF7?style=for-the-badge)
![OCR](https://img.shields.io/badge/OCR_&_Document_Understanding-2E9EF7?style=for-the-badge)
![Agents](https://img.shields.io/badge/Agentic_&_Tool_Calling-2E9EF7?style=for-the-badge)
![Guardrails](https://img.shields.io/badge/Evaluation_&_Guardrails-2E9EF7?style=for-the-badge)

### Cloud — Azure
![Azure Functions](https://img.shields.io/badge/Azure_Functions-0062AD?style=for-the-badge&logo=azurefunctions&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos_DB-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Service Bus](https://img.shields.io/badge/Service_Bus-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Blob Storage](https://img.shields.io/badge/Blob_Storage-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![App Insights](https://img.shields.io/badge/Application_Insights-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Mobile
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### Data
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=hari0701&theme=tokyo-night&hide_border=true" alt="Contribution Graph"/>
</div>

---

## 🤝 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hari0701)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hari07.at@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/_harix__)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@hari07.at)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/c/poducodu)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/_.hari07)

</div>

---

<div align="center">

### 💭 Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>

---

<div align="center">

**⭐️ From [Hari0701](https://github.com/Hari0701) with 💙**

![Wave](https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg)

</div>
