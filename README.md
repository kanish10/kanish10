<p align="center">
  <img src="https://raw.githubusercontent.com/kanish10/kanish10/main/header.svg" width="100%" alt="Kanish Khanna" />
</p>

<div align="center">

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3000&pause=1500&color=764BA2&center=true&vCenter=true&random=false&width=700&lines=Applied+AI+Engineer+%40+Rakuten+Inc;CS+%40+University+of+British+Columbia;Building+LLM+Serving+Systems+%26+GPU+Tooling;From+CUDA+Kernels+to+Production+Infrastructure" alt="Typing SVG" /></a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-kanishkhanna-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kanishkhanna/)

</div>

<br/>

I build at the intersection of **AI and systems** — making inference faster, catching GPU regressions before they ship, and building the tooling that keeps AI infrastructure honest. Currently an **Applied AI Engineer Intern** at **Rakuten Inc**, finishing my CS degree at **UBC** in Vancouver.

<br/>

## What I Build

<table>
<tr>
<td width="50%" valign="top">

### [LLM Inference Server](https://github.com/kanish10/LLM-Inference-Server)

<sub>

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

</sub>

From-scratch **continuous batching** scheduler — the algorithm behind vLLM and TGI. Lock-free hot path with a Go gRPC gateway providing admission control, backpressure, and Prometheus metrics.

`→ 2.13x throughput at matched p99 latency vs static batching`

</td>
<td width="50%" valign="top">

### [PerfLens](https://github.com/kanish10/PerfLens)

<sub>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

</sub>

Nightly CI that **catches and explains CUDA kernel regressions**. Nsight Compute profiling → noise-aware statistical detection → AI triage agent that correlates performance changes with source diffs.

`→ 83 tests · automated PR gates · FastAPI + React dashboard`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Ray Tracer](https://github.com/kanish10/Ray-Tracer)

<sub>

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)

</sub>

From-scratch **ray tracing renderer** — vector math, camera systems, materials, lighting, and scene file support.

</td>
<td width="50%" valign="top">

### [NLP Piazza Chatbot](https://github.com/kanish10/nlp-piazza-analysis-chatbot)

<sub>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-191919?style=flat&logo=anthropic&logoColor=white)

</sub>

Piazza discussion analyzer with an **AI chatbot powered by Claude v2.1** on AWS Bedrock. Uses Comprehend NLP to surface learning insights from student discussions.

</td>
</tr>
</table>

<br/>

## Tech Stack

<table>
<tr><td>

**Languages** &nbsp;&nbsp;
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frameworks** &nbsp;&nbsp;
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)

**Infrastructure** &nbsp;&nbsp;
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Data & Observability** &nbsp;&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

</td></tr>
</table>

<br/>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=kanish10&theme=transparent&hide_border=true&ring=764BA2&fire=667eea&currStreakLabel=764BA2&sideLabels=764BA2&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681" />
  <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=kanish10&theme=default&hide_border=true&ring=667eea&fire=764BA2&currStreakLabel=667eea" />
  <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=kanish10&theme=transparent&hide_border=true&ring=764BA2&fire=667eea&currStreakLabel=764BA2&sideLabels=764BA2&currStreakNum=c9d1d9&sideNums=c9d1d9&dates=6e7681" />
</picture>
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kanish10/kanish10/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kanish10/kanish10/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/kanish10/kanish10/output/github-snake-dark.svg" />
  </picture>
</div>
