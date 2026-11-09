<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2496ED,100:6C5CE7&height=180&section=header&text=Aadvik%20Chaturvedi&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=40" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=6C5CE7&center=true&vCenter=true&width=640&lines=CSE+%40+DTU%2C+Delhi;Agentic+systems+%2B+computer+vision;ML+Intern+%40+CRIS%2C+Ministry+of+Railways;LeetCode+Knight+%7C+Codeforces+Specialist" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/aadvik-chaturvedi"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://leetcode.com/u/Aadvik_1234/"><img src="https://img.shields.io/badge/-LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
  <a href="mailto:aadvikchaturvedi06@gmail.com"><img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

### About me

I'm a B.Tech CSE student at **Delhi Technological University** (2024–28, CGPA 9.19). I build AI systems that have to work outside a notebook: agents that call tools and recover from failures, vision models that sit behind an API, and the plumbing in between (queues, rate limiters, caches, streaming).

- **CRIS, Ministry of Railways (ML Intern, Jun–Aug 2026).** Built and deployed a delay-prediction service on live data for 1,000+ trains a day. Caught a target-leakage bug hidden in undocumented columns, rebuilt the pipeline, and took a GATv2 + BiGRU model to R² 0.951 (about 39% lower error than the historical baseline).
- **Vision + agents.** Remote-sensing VLM assistant with an auditable task router (SIH), satellite/radar nowcasting with SimVP, and a DeiT chest X-ray classifier with explainability checks.
- **Competitive programming.** LeetCode Knight (peak 2,067), Codeforces Specialist (peak 1,584), Meta Hacker Cup 2025 Round 2.

### Tech stack

<p align="center">
  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <br/>
  <img src="https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/-Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
</p>

### Featured work

#### Agents and LLM systems

| Project | What it is | Stack |
|---|---|---|
| [**SatQuery AI**](https://github.com/aadvikchaturvedi/SatQuery) | Ask questions about Sentinel-2 optical and SAR imagery. A rule-based controller decides from the inputs and the query whether to run VQA, captioning, grounding (Qwen2.5-VL-3B + LoRA), optical–SAR fusion or bi-temporal change detection, and logs an auditable execution report. Team project for SIH; I built the FastAPI backend, the agent/tool layer and the model integration. | FastAPI, Qwen2.5-VL, LoRA, Gemini, React |
| [**Multi-Agent Job Extractor**](https://github.com/aadvikchaturvedi/Agentic-Profile-to-Job-Matcher) | Scraper → Parser → Enrichment → Matching agents. Playwright scraping with per-domain token buckets, LLM fallback parsing, embedding pre-filter plus LLM scoring, retries with backoff, pause/resume/stop, live progress over WebSockets. | FastAPI, Playwright, Redis, Next.js |
| [**CodeHelp**](https://github.com/aadvikchaturvedi/CodeHelp) | Browser IDE that edits real local folders (File System Access API), with streaming LLM chat over SSE (local Ollama or Claude), code suggestions from a local model, and a Redis response cache. | Next.js 16, TypeScript, Redis, Docker |
| [**Project Prithvi**](https://github.com/aadvikchaturvedi/Project-Prithvi-New) | Recycling-pickup app with a tool-calling support agent grounded in a knowledge base. | FastAPI, Supabase, React |

#### Computer vision and spatio-temporal ML

| Project | What it is | Stack |
|---|---|---|
| [**Thunderstorm nowcasting (SIH 2026)**](https://github.com/aadvikchaturvedi/sih26072) | SimVP model that forecasts radar reflectivity 10–120 min ahead and lightning probability, with radar-dropout training for a satellite-only fallback, isotonic calibration and a diffusion refiner for ensembles. Backend issues district warnings in CAP format. Validated end to end on synthetic data so far. | PyTorch, FastAPI, React |
| [**Explainable COVID-19 X-ray ViT**](https://github.com/aadvikchaturvedi/Explainable-COVID-19-Chest-X-Ray-Classification-Using-Fine-Tuned-Vision-Transformers) | Fine-tuned DeiT-base (last 4 blocks), 96.8% test accuracy on 3 classes, with Grad-CAM and gradient-saliency maps plus a deletion/insertion evaluation harness. | PyTorch, timm |
| [**Splash**](https://github.com/aadvikchaturvedi/Splash) | Product layer for AI diving judging: upload a dive video, get entry, splash and position scores from an action-quality model. | Next.js, Supabase |

#### ML on real-world data

| Project | What it is |
|---|---|
| [**VajraAI**](https://github.com/aadvikchaturvedi/VajraAI) | Hack4Delhi team project. Tabular Transformer for transaction fraud on IEEE-CIS with focal loss, hard-negative mining and leakage-safe expanding-window CV (best fold ROC-AUC 0.807). |
| [**MapLY**](https://github.com/aadvikchaturvedi/MapLY) | Team project. Route risk overlay: each stretch of an OSRM route is scored by a district-level XGBoost model on NCRB crime data. Plus a Gemini + Pinecone RAG safety chatbot, DistilBERT sentiment and WebSocket SOS. I built the ML backend. |
| [**Flipkart Gridlock**](https://github.com/aadvikchaturvedi/flipkart_gridlock) | Geohash-level demand forecasting. Feature engineering took XGBoost from R² 0.750 to 0.945. |

### GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aadvikchaturvedi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aadvikchaturvedi&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=aadvikchaturvedi&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C5CE7,100:2496ED&height=100&section=footer" width="100%"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=aadvikchaturvedi&style=flat-square&color=blue" alt="Profile views" />
</p>
