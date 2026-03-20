<h1 align="center">Hi, I'm Lian Huang</h1>

<p align="center">
  <a href="https://github.com/lianhuang1221"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=500&lines=Software+Engineer+%7C+FinTech+Backend;MSc+Computer+Science+%40+Aston+University;AI%2FML+Researcher+%7C+LLM+%2B+TMLC+Pipeline;Open+to+Backend+%26+AI%2FML+Roles" alt="Typing SVG" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=lianhuang1221&style=flat-square&color=58A6FF&label=Profile+Views" alt="Profile Views" />
</p>

<p align="center">
  <a href="mailto:lian.huang1221@gmail.com"><img src="https://img.shields.io/badge/Email-lian.huang1221%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/lianhuang1221"><img src="https://img.shields.io/badge/LinkedIn-Lian%20Huang-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/lianhuang1221"><img src="https://img.shields.io/badge/GitHub-lianhuang1221-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

## About Me

I am a software engineer with 5+ years of experience spanning **large-scale financial backend systems** and **applied AI/ML research**. My work bridges the gap between production-grade software engineering and cutting-edge machine learning.

At **NCCC (National Credit Card Center of R.O.C.)**, I built mission-critical FinTech infrastructure — developing a FIDO authentication system that saved ~NT$10M in operational costs and optimizing transaction throughput for American Express & Discover Financial Services from **TPS 200 → TPS 1,000** (5× improvement).

I recently completed my **MSc in Computer Science at Aston University (UK)**, where my dissertation investigated whether Traditional ML Classifiers can augment LLM reasoning under single-GPU constraints. I designed a multi-pipeline experimental framework comparing Llama-3 8B and DeepSeek-V2 7B with LightGBM/XGBoost hybrid architectures.

Currently open to **Backend Engineer** and **AI/ML Engineer** opportunities.

---

## Research

### Comparative Analysis of Reasoning Capabilities in LLMs and Traditional ML Classifiers
**MSc Dissertation** · Aston University · 2024–2026

Investigated whether Traditional ML Classifiers (TMLC) can augment LLM reasoning under single-GPU constraints (RTX 5080, 16 GB VRAM). Designed and implemented a **4-pipeline experimental framework**:

| Pipeline | Description |
|----------|-------------|
| **A — Frozen LLM** | Zero-shot evaluation with Self-Consistency decoding (k=5) |
| **B — LoRA Fine-tuning** | INT8-quantized LoRA/QLoRA adaptation with sampling-based evaluation |
| **C — Reasoning-layer Feature Extraction** | Extract reasoning signals → downstream LightGBM/XGBoost classification |
| **D — Vector-layer Feature Extraction** | Extract hidden-state representations → PCA → TMLC classification |

**Models:** Llama-3 8B, DeepSeek-V2 7B
**Tech:** PyTorch · LoRA/QLoRA · INT8 Quantization · Self-Consistency Decoding · LightGBM · XGBoost · PCA · Calibration (Sigmoid/CV)

> Repository: [`LLM-vs-TMLC-Reasoning-Pipeline`](https://github.com/lianhuang1221/LLM-vs-TMLC-Reasoning-Pipeline) *(if public)*

---

## Featured Projects

### LLM + TMLC Hybrid Reasoning Pipeline
An end-to-end ML pipeline for comparing LLM reasoning with traditional ML classifiers. Covers zero-shot evaluation, LoRA fine-tuning, reasoning feature extraction, and vector-layer feature extraction with LightGBM/XGBoost downstream classification. Config-driven experiment management via JSON.

### Blockchain Identity Verification System
Designed and developed a blockchain-based identity verification architecture covering electronic devices, blockchain servers, admin backend, and window servers. Built with **Ethereum** and **Solidity** smart contracts. *(Jun 2020 – Sep 2022)*

### LINE Chatbot for Quotation Inquiries
Developed a LINE chatbot with fuzzy search capabilities, serving ~200 clients in the machinery manufacturing industry. Built with Django, PostgreSQL, and Tailwind CSS.

---

## Tech Stack

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

### AI / Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

### Infrastructure & Tools
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

### Blockchain
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

---

## Experience

| Period | Role | Organization |
|--------|------|--------------|
| 2024 – 2026 | **MSc Computer Science** | Aston University, Birmingham, UK |
| 2019 – 2022 | **Software Engineer** | NCCC (National Credit Card Center of R.O.C.), Taipei |
| 2018 – Present | **Freelance Software Developer** | Self-employed, Taoyuan |
| 2013 – 2018 | **BSc Information Engineering** | Chung Hua University, Hsinchu |

---

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=lianhuang1221&theme=github-compact&hide_border=true&area=true&custom_title=Contribution%20Activity" alt="Activity Graph" />
</p>

---

<p align="center">
  <em>"Bridging the gap between large language models and traditional machine learning — one pipeline at a time."</em>
</p>
