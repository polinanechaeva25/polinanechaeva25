<h1 align="center">Polina Nechaeva</h1>

<p align="center">
  <b>Software Engineer — Backend &amp; AI Systems</b><br>
  I build AI products for business: assistants over company knowledge,<br>
  agent workflows, and the integrations that connect them to real channels<br>
  <sub>Quito, Ecuador — open to remote</sub>
</p>

<p align="center">
  <a href="https://linkedin.com/in/polina-nechaeva-dev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:polinanech09@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

Backend engineer with 3+ years in production, working on AI systems that companies actually run their operations on: assistants that answer from a business's own knowledge base, agent workflows that automate the steps around them, and the integration layer that plugs all of it into the messengers and CRMs people already use.

Mostly Python and TypeScript, and I stay involved through deployment — Docker, Kubernetes, CI/CD. I like the parts where correctness matters: retrieval quality, tenant isolation, and the performance work that only shows up once real traffic arrives.

### Tech stack

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/Django_REST-A30000?style=flat-square&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

**AI &amp; LLM**

![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![vLLM](https://img.shields.io/badge/vLLM-FDB515?style=flat-square&logoColor=black) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Data &amp; infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)

**Frontend &amp; mobile**

![React](https://img.shields.io/badge/React-087EA4?style=flat-square&logo=react&logoColor=white) ![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) ![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxt&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-087EA4?style=flat-square&logo=react&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)

### What I've been building

**AI assistant platform for business** — *Wikilect*<br>
Assistants that answer from a company's own knowledge base and live inside the channels its customers already use.

I built the retrieval layer on PostgreSQL/pgvector (semantic search combined with weighted full-text), LangChain tool-calling agents with context-window trimming, and a multi-provider LLM layer — OpenAI, Ollama, vLLM, LiteLLM — that lets models be swapped without touching product code. Responses stream token by token over Django Channels, and input is multimodal: images normalized for vision models, voice notes transcribed with Yandex SpeechKit.

I also owned 11 integration channels end to end — Telegram, VK, MAX, Bitrix24, JivoChat, HelpDeskEddy, PACT, Chat2Desk — from webhooks and async task pipelines to public OpenAPI docs, with Sentry and Langfuse tracing so it's possible to see what a model actually did on a real conversation. The platform serves many client organizations from one deployment, and I designed that isolation layer from scratch.

**Visual builder for AI agent workflows** — *Wikiflow*<br>
A node-based editor where a business assembles its own LLM pipelines instead of asking engineers for each change. I contributed components to the execution engine: a universal node for sending messages to any connected integration, configurable search and embedding nodes, image handling for vision models, and voice transcription — each covered with pytest and shipped to Kubernetes through Helm and CI.

**News &amp; media intelligence platform** — *Port by Elemento*<br>
Media-monitoring dashboards in React 18 + TypeScript with multi-tenant filtering and per-client branding, on a DRF/PostgreSQL backend with automated PDF reporting. Gemini API for summarization and localization. Shipped on Cloud Run via Docker and GitHub Actions.

**AI-powered mobile news app** — *IDEAL*<br>
Node.js/Express (TypeScript) backend with OpenAI SDK, proactive chat prompting and TTL session management, plus the React Native app: Google Sign-In, native deep linking, push notifications.

<sub>These are commercial projects, so the code is private. Happy to walk through the architecture and trade-offs in a conversation.</sub>

### Community

Mentor at **Django Girls Cuenca** (Ecuador) — teaching Python and Django fundamentals to people writing their first web app.

### Beyond code

Background in Mechatronics and Robotics Engineering (BSc, MPEI, with honors) — which is where the habit of debugging systems rather than guessing at them comes from. I work in Russian, Spanish and English.
