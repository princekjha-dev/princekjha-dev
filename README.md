<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:16213e,100:0f3460&height=160&section=header&text=Prince%20Kumar%20Jha&fontSize=42&fontColor=e0e0e0&fontAlignY=55&desc=Backend%20%C2%B7%20AI%20Tooling%20%C2%B7%20Open%20Source&descSize=16&descAlignY=78&descColor=a0a0b0" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prince-kumar-jha-72659435b/)
[![Portfolio](https://img.shields.io/badge/Portfolio-1A56DB?style=flat-square&logo=About.me&logoColor=white)](https://princebuilds.netlify.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pkjha2028@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=princekjha-dev&style=flat-square&color=0f3460&label=Profile+Views)](https://github.com/princekjha-dev)

</div>

---

### About

B.Tech CSE student at ITS Engineering College, Greater Noida (2025–Present).

I build backend tools and AI pipelines — things that actually run, not just demo. Before starting college I worked as a Data Annotation Specialist at Cogito Tech, labeling 10,000+ images for CV pipelines. Since then I've shipped open-source tools, built full-stack RAG apps, and learned how async systems, vector retrieval, and multi-provider LLM backends work in practice.

Currently learning: **Java · Spring Boot · Spring Security · system design fundamentals**

Open to **backend, AI/ML, and Python internships** in Delhi NCR or remote.

---

### Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)

**Backend & Systems**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-3670A0?style=flat-square&logo=python&logoColor=ffdd54)

**AI & Data**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Whisper](https://img.shields.io/badge/Whisper-000000?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square&logo=databricks&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

**Tooling**

![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[Clipify](https://github.com/princekjha-dev/Clipify)** &nbsp; [![Live](https://img.shields.io/badge/Live-clipifyy.netlify.app-0f3460?style=flat-square)](https://clipifyy.netlify.app)

AI-powered CLI tool that takes a YouTube URL or local video and outputs ranked short-form clips ready for TikTok, Reels, and Shorts.

- Word-level transcription via **faster-whisper**
- 5-signal clip ranking: hook, energy, sentiment, keywords, silence
- FFmpeg stream-copy export — no re-encoding overhead
- **13-provider AI backend** (Groq, OpenAI, Claude, Gemini, Mistral, Cohere +) with automatic failover
- Published as **v1.0.1** on PyPI · 20 GitHub stars

`Python` `FFmpeg` `faster-whisper` `yt-dlp` `OpenAI` `Groq`

</td>
<td width="50%" valign="top">

**[IntelliDoc](https://github.com/princekjha-dev/Al-Powered-Office-Document-Automation-System)** &nbsp; [![Live](https://img.shields.io/badge/Live-intellidoc.netlify.app-0f3460?style=flat-square)](https://intellidoc.netlify.app)

Document Q&A and analysis tool. Upload a PDF, DOCX, or XLSX — ask questions, get source-grounded answers in 2–5s, compare docs side-by-side.

- RAG pipeline using **OpenRouter + Groq**
- 5-dimension quality scoring per document
- Available as web dashboard, Telegram bot, and CLI
- Telegram bot: circuit-breaker, retry, rate limiting, `asyncio.gather()`

`Python` `Flask` `asyncio` `OpenRouter` `Groq` `Hugging Face` `Telegram`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[RepoChat](https://github.com/princekjha-dev/RepoChat)**

Full-stack RAG app for natural language querying over public GitHub repositories — no local clone needed.

- AST-based chunking for code-aware document splitting
- **ChromaDB** vector store with Sentence Transformers semantic embeddings
- Flask REST API backend + React/Tailwind frontend
- Enables dev teams to ask questions directly over any public codebase

`Python` `Flask` `ChromaDB` `Sentence Transformers` `React` `Tailwind`

</td>
<td width="50%" valign="top">

**[Placement Analysis](https://github.com/princekjha-dev/placement-analysis)**

ML analysis of engineering student placement patterns using a 5,000-record synthetic dataset.

- Logistic regression to predict placement probability
- Key finding: internships = strongest predictor; CGPA < 7.0 = barrier
- 3-script pipeline → auto PDF report via **FPDF**
- Also packaged as a Jupyter notebook

`Python` `Pandas` `Scikit-learn` `Matplotlib` `Seaborn` `FPDF`

</td>
</tr>
</table>

---

### GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=princekjha-dev&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false&show_icons=true)

![Streak](https://nirzak-streak-stats.vercel.app/?user=princekjha-dev&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=princekjha-dev&theme=tokyonight&hide_border=true&layout=compact)

</div>

---

### Experience & Achievements

- 🏢 **Cogito Tech** — Data Annotation Specialist *(May–Aug 2025, pre-enrollment)* · Labeled 10,000+ images for CV pipelines, 95%+ QA accuracy
- 🏆 **Smart India Hackathon** — Round 2 Shortlisted · EdTech government problem statement
- ⚡ **Hack the Beginning** — Sole developer on team · Built and demoed a working prototype in 24 hours
- 🚀 **Clipify v1.0.1** — Published on PyPI and GitHub · 20 stars, zero marketing

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f3460,50:16213e,100:1a1a2e&height=100&section=footer" />

*"Build tools that people actually use."*

</div>
