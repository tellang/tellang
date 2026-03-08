<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?lines=Backend+Developer+→+AI%2FML+Engineer;LLM+Fine-tuning+%7C+RAG+%7C+vLLM+Serving;Building+Domain-Specific+AI+Products&font=JetBrains+Mono&center=true&width=550&height=50&color=A78BFA&vCenter=true&pause=1000&size=22&duration=2500" alt="Typing SVG" />
</a>

<br>

<a href="https://github.com/tellang?tab=followers">
  <img src="https://img.shields.io/github/followers/tellang?style=flat-square&logo=github&color=1F222E&labelColor=1F222E" alt="Followers" />
</a>
<a href="https://huggingface.co/tellang">
  <img src="https://img.shields.io/badge/HuggingFace-tellang-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="HuggingFace" />
</a>
<img src="https://komarev.com/ghpvc/?username=tellang&style=flat-square&color=A78BFA&label=VIEWS" alt="Views" />

</div>

---

### About Me

- **Backend → AI/ML Engineer** | SSAFY 14기 서울 Java 전공
- 도메인 특화 LLM 파인튜닝부터 프로덕션 서빙까지 **End-to-End** 경험
- **Interests**: `LLM Fine-tuning` · `RAG` · `vLLM` · `Prompt Engineering` · `Data Pipeline`

---

### 🤗 Hugging Face Activity

<details open>
<summary><b>YEJI — 한국어 운세 특화 LLM</b></summary>
<br>

**50 Repositories** · End-to-End ML Pipeline

Qwen3 기반 도메인 특화 모델을 v1~v9까지 반복 파인튜닝.
QDoRA→QLoRA→LoRA→DoRA→rsLoRA **5가지 PEFT 기법** 진화.
SFT 데이터 직접 구축 (사주 · 점성술 · 타로 · 화투 · 주역 · 자미두수) + AWQ/GGUF/MLX 양자화.

```
Data Collection → Preprocessing → SFT (v1~v9, 5 PEFT) → Quantization → vLLM Serving
```

| Category | Count | Highlights |
|----------|-------|-----------|
| **Models** | 20 | Qwen3 4B/8B, rsLoRA, AWQ/GGUF/MLX |
| **Datasets** | 28 | SFT + DPO/SimPO + 100K+ 중한 번역 코퍼스 |
| **Spaces** | 2 | Gateway, Captcha |

[![HuggingFace](https://img.shields.io/badge/🤗_All_Models_&_Datasets-tellang-FFD21E?style=flat-square)](https://huggingface.co/tellang)

</details>

---

### Featured Projects

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/tellang/yeji-core"><b>🔮 YEJI</b></a><br>
<sub>동양+서양 융합 AI 운세 서비스 · 7개 리포</sub><br><br>
Qwen3 파인튜닝 (5 PEFT 기법, v1~v9)<br>
vLLM 서빙 · AWQ 양자화 (16→5.5GB, -65%)<br>
검증 실패율 30%→5% · 추론 성공률 18/18<br>
Jenkins CI/CD · 4대 GPU 통합 인프라<br>
<sub><code>Spring Boot</code> <code>FastAPI</code> <code>vLLM</code> <code>Qwen3</code> <code>AWS</code></sub>
</td>
<td align="center" width="50%">
<a href="https://github.com/tellang/speaky"><b>🎭 Speaky</b></a><br>
<sub>AI 캐릭터 운세 챗봇 · M2 MacBook 배포</sub><br><br>
SFT + DPO + SimPO 3단계 정렬 학습<br>
6캐릭터 페르소나 · D1-D8 8차원 평가 (4.12/5.00)<br>
EXAONE 1.2B + E5 인텐트 분류 (13개)<br>
SSE 스트리밍 · Cloudflare Tunnel<br>
<sub><code>FastAPI</code> <code>vllm-mlx</code> <code>EXAONE</code> <code>Redis</code> <code>Jenkins</code></sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<b>🍽 MyEat (YYCH)</b> <img src="https://img.shields.io/badge/🏆_우수상-FF6B35?style=flat-square" /><br>
<sub>MBTI 기반 AI 영양 코칭 · SSAFY 관통프로젝트</sub><br><br>
Redis Vector Search 2단계 RAG (45K+ 음식 DB)<br>
GPT-5 Mini Intent Filter + Embedding Cache<br>
16개 MBTI 페르소나 · CoT 응답 생성<br>
API 비용 50% 절감 · SSE 스트리밍<br>
<sub><code>Java</code> <code>Spring Boot</code> <code>Redis Stack</code> <code>OpenAI</code></sub>
</td>
<td align="center" width="50%">
<a href="https://github.com/tellang/triflux"><b>🔀 triflux</b></a><br>
<sub>AI CLI Orchestrator · Claude × Codex × Gemini</sub><br><br>
멀티 모델 통합 라우팅<br>
DAG 기반 병렬 실행 엔진<br>
토큰 비용 추적 · 자동 fallback<br>
<br>
<sub><code>TypeScript</code> <code>Node.js</code></sub><br>
<img src="https://img.shields.io/github/stars/tellang/triflux?style=flat-square&color=A78BFA&labelColor=1F222E" />
<img src="https://img.shields.io/github/forks/tellang/triflux?style=flat-square&color=1F222E&labelColor=1F222E" />
</td>
</tr>
</table>

---

### Tech Stack

**AI / ML**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" /> <img src="https://img.shields.io/badge/vLLM-FF6F00?style=flat-square&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />

**Backend**

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />

**Infra / DevOps**

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" /> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" /> <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" /> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />

<details>
<summary><b>Backend (Previous)</b></summary>
<br>

<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" /> <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />

</details>

---

### Career Journey

| Period | Role | Focus |
|--------|------|-------|
| **2024** | Backend Developer | Spring Boot, MSA, Kafka, Redis |
| **2025.07 ~** | **AI/ML Engineer** | SSAFY 14기 서울 Java 전공 · LLM, RAG, vLLM |

---

<details>
<summary><h3>GitHub Stats</h3></summary>
<br>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tellang&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1F222E&title_color=A78BFA&icon_color=A78BFA" height="170" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tellang&layout=compact&theme=tokyonight&hide_border=true&bg_color=1F222E&title_color=A78BFA&hide=html,css" height="170" alt="Top Langs" />
</div>

<br>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=tellang&theme=tokyonight&background=1F222E&hide_border=true&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" alt="Streak Stats" />
</div>

</details>

---

<div align="center">

<a href="mailto:pte1024@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://huggingface.co/tellang"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black" /></a>

</div>
