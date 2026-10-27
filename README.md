<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=140&section=header&text=Mohammed%20Thaher%20S&fontSize=36&fontColor=ffffff&fontAlignY=38"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&pause=1200&color=6366F1&center=true&vCenter=true&width=700&lines=I+build+LLM+agents+with+rules+in+code;GenAI+%26+Python+backend+engineer;CS+grad+from+Chennai,India" alt="Typing SVG"/>
</p>

I build LLM agents and the backends behind them. Every project below is deployed with a live demo. They're all solo work, and none of them has real users yet, so I'd rather say that up front than hide it.

I use AI coding tools every day, and I read, test and debug whatever they write before it ships. Open to AI / SDE roles in India / Remote.

### Projects

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Trendly** | Support agent where the LLM reasons but a rules engine makes the final call on returns, blocked categories and escalation. 8 guardrails, 5 Pytest cases. | Python, FastAPI, Groq, Pytest | [Live](https://trendly-agent-1.onrender.com/ui) · [Code](https://github.com/MohammedThaher01/trendly-agent) |
| **DocuMind** | Turns a plain request into a Word document. A 5 node LangGraph pipeline plans, drafts, critiques its own draft, revises and exports. 7 document types. | LangGraph, FastAPI, React, Groq | [Live](https://docu-mind.up.railway.app) · [Code](https://github.com/MohammedThaher01/DocuMind) |
| **Multimodal Visual Q&A** | YOLOv8m detects objects, and the structured output goes to Gemini to answer questions about counts and positions. A two stage pipeline, not an agent. | YOLOv8, Gemini, LangChain, FastAPI, Gradio | [Live](https://huggingface.co/spaces/7haher/multimodal-vision-qa) · [Code](https://github.com/MohammedThaher01/doc-rag-chat-bot) |
| **Document RAG Chatbot** | Upload PDFs, ask questions, get cited answers. | LangChain, FAISS, Groq, Streamlit | [Live](https://doc-rag-chat-bot.streamlit.app) · [Code](https://github.com/MohammedThaher01/doc-rag-chat-bot) |

### Things I've learned the hard way

- Rules that must always hold belong in code, not in the prompt. When I changed the model under Trendly, the prompt-based rules stopped being followed.
- A test that passes on one model proves very little.
- DocuMind's first critique prompt missed invented prices and conflicting timelines on a messy request, so I rewrote it to check for them.
- When a deploy fails, read the actual config values before trusting a confident theory. Mine was my API key sitting in the model name field.

### Toolbox

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white"/> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge"/> <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge"/> <img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge"/> <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

### Background

- B.E. Computer Science, Sathyabama Institute of Science and Technology (2026, First Class with Distinction)
- Intern at Campervan Factory, IIT Madras Research Park: integrated frontend pages with a Django backend for a live travel platform and managed two other interns
- Winner, AgriTech Hackathon: EfficientNetB4 on 38 crop disease classes, 95% accuracy
- Finalist, Zelestra x AWS ML Hackathon: stacking ensemble, 94.14% score


### Find me

<p>
  <a href="mailto:thahercareer@gmail.com"><img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/mohammed-thaher-s/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://thahersprofile.vercel.app"><img src="https://img.shields.io/badge/Portfolio-6366f1?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://x.com/Thaher01"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white"/></a>
</p>

<img src="https://github-readme-stats.vercel.app/api?username=MohammedThaher01&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=100&section=footer"/>
