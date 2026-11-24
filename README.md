<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=620&lines=Hi+there+%F0%9F%91%8B+I'm+Dong79;Backend+%26+Full-Stack+Engineer;LLM+Inference+%C2%B7+C%2B%2B20+%C2%B7+CUDA;Async+Python+%C2%B7+Multi-Agent+Systems" alt="Typing SVG" />

<p>
  <a href="https://github.com/Dong79?tab=repositories"><img src="https://img.shields.io/badge/Open%20to-Backend%20%2F%20Full--Stack%20roles-2ea44f?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Ex--Google-4285F4?style=flat-square&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/MSCS-Santa%20Clara%20University-9e1b32?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=Dong79&style=flat-square&color=blue&label=Profile+views" />
</p>

</div>

### 🧑‍💻 About me

- 🔭 Building **LLM serving infrastructure** from scratch — paged KV cache, continuous batching, custom CUDA kernels
- 🤖 Designing **async, multi-agent pipelines** that are measurable: DAG scheduling, retries, LLM-as-a-Judge grounding checks
- 🏢 Previously at **Google** · 🎓 M.S. Computer Science, **Santa Clara University**
- 🌱 Interested in systems performance, distributed backends, and making LLM apps reliable in production

### 🛠️ Tech stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=cpp,python,java,js,ts&theme=dark" />
  <br/>
  <img src="https://skillicons.dev/icons?i=pytorch,fastapi,spring,nodejs,express,react,graphql&theme=dark" />
  <br/>
  <img src="https://skillicons.dev/icons?i=mongodb,aws,cmake,linux,git&theme=dark" />
</p>

<img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" /> <img src="https://img.shields.io/badge/LibTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white" /> <img src="https://img.shields.io/badge/SSE%20Streaming-555?style=flat-square" /> <img src="https://img.shields.io/badge/OpenAI--compatible%20API-412991?style=flat-square&logo=openai&logoColor=white" />

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### ⚡ [llm-inference-engine](https://github.com/Dong79/llm-inference-engine)
OpenAI-compatible LLM inference server in **C++20 + LibTorch**, built around the ideas behind vLLM.

- Continuous batching with chunked prefill
- Paged KV cache + prefix caching (LRU)
- Copy-on-write block sharing for `n > 1`
- Async SSE streaming, single engine thread
- Optional custom **CUDA paged-attention** kernel
- Runs Llama 2/3, Mistral, Qwen2/2.5/3

`C++20` `CUDA` `LibTorch` `CMake`

</td>
<td width="50%" valign="top">

#### 🔎 [async-research-pipeline](https://github.com/Dong79/async-research-pipeline)
Multi-agent "deep research" service: plans sub-questions, searches & summarizes them **in parallel** as an async DAG.

- Readiness-driven DAG scheduler, bounded concurrency
- Backoff w/ jitter, checkpoint & resume
- BM25 context budgeting, citation remapping
- SSE progress streaming with replay
- **LLM-as-a-Judge** claim-grounding audit

`Python` `asyncio` `FastAPI` `httpx` `Pydantic`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧪 [test_plan_agent](https://github.com/Dong79/test_plan_agent)
PRD → test-case **multi-agent** system: parallel extractor agents, local RAG, critic/refine loop, Pydantic-validated output with traceability.

`Python` `Multi-Agent` `RAG` `Structured Output`

</td>
<td width="50%" valign="top">

#### 💬 [vchat](https://github.com/Dong79/vchat) · 🎰 [lottery](https://github.com/Dong79/lottery)
Web apps — a group chat and a lottery app — with Node.js/Express REST backends, JWT auth and MongoDB.

`Node.js` `Express` `MongoDB` `Mongoose`

</td>
</tr>
</table>

### 📊 GitHub stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Dong79&show_icons=true&include_all_commits=true&count_private=true&theme=github_dark&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Dong79&layout=compact&langs_count=8&theme=github_dark&hide_border=true" />
  <br/>
  <img src="https://streak-stats.demolab.com?user=Dong79&theme=github-dark-blue&hide_border=true" />
  <br/>
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Dong79&theme=github-compact&hide_border=true&area=true" />
</div>

### 🐍 Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dong79/Dong79/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Dong79/Dong79/output/github-contribution-grid-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Dong79/Dong79/output/github-contribution-grid-snake.svg" />
</picture>

<!--
### 📫 Connect
Uncomment and fill in your links:
<a href="https://www.linkedin.com/in/YOUR-ID/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
-->
