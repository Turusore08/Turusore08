<div align="center">

# Arya Pratama Rhama Putra
**AI Engineering Undergraduate @ Institut Teknologi Sepuluh Nopember (ITS)**  
*Applied Machine Learning · NLP & RAG Systems · Document & Computer Vision · Reinforcement Learning*

[![Portfolio](https://img.shields.io/badge/Portfolio-rhama--portfolio.vercel.app-0F172A?style=flat-square&logo=vercel&logoColor=white)](https://rhama-portfolio.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-aryapratamarhamaputra-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aryapratamarhamaputra/)
[![Email](https://img.shields.io/badge/Email-rhamaputra.business%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:rhamaputra.business@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Turusore08-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Turusore08)

</div>

---

### 👨‍💻 Overview

```yaml
education : B.Sc. in AI Engineering, Sepuluh Nopember Institute of Technology (2024 – 2028)
location  : Surabaya / Jakarta, Indonesia
focus     : [RAG & LLM Backends, Document OCR & Vision, Speech/Audio ML, Constrained RL & World Models]
currently : Building MengAsli RAG Backend, Aicareer Platform, and researching 3D Latent World Models & Safe-RLHF
```

---

### 🔬 Ongoing Research & Production Systems

| Project | Domain & Stack | Technical Summary |
| :--- | :--- | :--- |
| **PHI-LAB (`LeWM-NOVA3R`)** | `3D World Models` `PyTorch` `ManiSkill3` `AdaLN-Zero` | Researching 3D latent world models for robotic manipulation (`PushT-v1`, `PickCube-v1`) using a frozen NOVA-3R 3D encoder, Deterministic Information Bottleneck (DIB) spatial compression, and an AdaLN-Zero Transformer dynamics predictor. |
| **POME Safe-RLHF** | `Constrained RL` `Lagrangian-SAC` `Cal-QL` `ConvNeXt` | Developing an offline-to-online constrained reinforcement learning framework combining 16 IoT water-quality variables and microalgae imagery to automate bioprocess dosing under PerMenLHK No. 5/2014 effluent standards. |
| **MengAsli Backend** | `TypeScript` `Express` `pgvector` `BullMQ` `Gemini 2.5` | Production RAG backend for a maternal lactation counseling assistant using PostgreSQL (`pgvector` HNSW indexing), asynchronous medical PDF ingestion via Redis/BullMQ & `pymupdf4llm`, SSE token streaming, and PII scrubbing. |
| **Aicareer** | `DeepSeek V3` `PostgreSQL` `Prompt Engineering` | AI-assisted career platform (funded by HETI ITS) implementing LLM-based resume evaluation (*Aimprove*), semantic candidate-to-job matching logic, and structured job listing management. |

---

### 📦 Featured Repositories

| Repository | Category | Tech Stack | Implementation Details |
| :--- | :--- | :--- | :--- |
| **[VITS-Mamba](https://github.com/Turusore08/VITS-MAMBA)** | Speech Synthesis (TTS) | `PyTorch` `BiMamba SSM` `cVAE` `HiFi-GAN` `DDP` | End-to-end TTS pipeline replacing the quadratic Transformer text encoder in VITS with a linear-time `O(L)` Bidirectional Mamba module. Includes multi-GPU DDP (`fp16`) training, ARPAbet-to-IPA G2P, and MCD / F0 RMSE / RTF evaluation. |
| **[SAT Math OCR Pipeline](https://github.com/Turusore08/OCR-for-pdf-in-case-MATH-and-RnW-SAT)** | Document AI & ETL | `GOT-OCR 2.0` `PyMuPDF` `CUDA` `LLM` | Extraction pipeline for multi-column SAT math PDFs lacking text layers. Implements 100 DPI ink-density column probing, 300 DPI vector-geometry diagram cropping, and automated LaTeX conversion & College Board taxonomy tagging. |
| **[Action 2026](https://github.com/Turusore08/Action-2026)** | NLP & Data Mining | `IndoBERT-large` `XLM-R` `DeBERTa-v3` `IndoBERTweet` | Competition pipeline for heavily obfuscated Indonesian social media text, combining 5-layer lexical normalization (KBBI v6.1.0 & colloquial lexicon) with a 10-model Transformer ensemble and Stage-2 post-level probability calibration. |
| **[GEMASTIK 2026](https://github.com/Turusore08/GEMASTIK-2026)** | Audio Anti-Spoofing | `PyTorch` `torchaudio` `AASIST` `CQT-LFCC` `RawNet2` | Audio deepfake detection experiments on the ASVspoof 5 dataset (attacks A01–A18). Evaluates 5 architectures from LCNN and RawNet2 baselines to a hybrid CQT-LFCC spectral fusion with an AASIST graph attention backbone under stratified quota sampling. |
| **[Jawani AI](https://github.com/Turusore08/Jawani-SeaLion-9B)** | Regional NLP & LLM | `Javanese-BERT` `Sea-Lion 9B` `Hugging Face` `Streamlit` | Hybrid Javanese language assistant pairing a 4-tier speech level (*unggah-ungguh*: Ngoko Lugu, Ngoko Alus, Krama Lugu, Krama Inggil) BERT classifier with Sea-Lion 9B for grammar correction and multi-persona dialogue. |
| **[JavanE-BIRD](https://github.com/Turusore08/JavaneBIRD)** | Bioacoustics & CV | `PyTorch` `ResNet50` `Transformer` `Librosa` | Classification of 6 endemic Javanese bird species in noisy tropical environments using a learnable Sigmoid Gated Fusion network that balances spatial Log-Mel Spectrogram features (ResNet50) and sequential acoustic features (MFCC, Chroma, Tonnetz). |
| **[Renits](https://github.com/Turusore08/backend_Renits)** · **[Web](https://github.com/Turusore08/Website-Renits)** | HealthTech & IoT API | `Flask` `SQLAlchemy` `JWT` `Scikit-learn` `TypeScript` | REST API and web dashboard (PKM 2025 grant project) for logging non-invasive biomarker patch telemetry (glucose, potassium, comorbidities) and serving kidney disease risk predictions. |
| **[AuraRiset](https://github.com/Turusore08/FP-PWEB-AuraRiset)** | Full-Stack Web & LLM | `PHP 8.2` `PostgreSQL` `GPT-4o-mini` `Docker` | Web platform for extracting research gaps from uploaded academic PDFs, featuring RBAC authentication, 3D topic graph mapping, and automated PDF report generation. |
| **[SIPERAK](https://github.com/Turusore08/FP_KPPL)** | Software Eng & ML | `Python` `Flask` `Scikit-learn` `SQLite` `Pytest` | Public complaint system built with Boundary-Controller-Entity (BCE) architecture, utilizing dual TF-IDF (1–2 gram) + Logistic Regression pipelines for binary spam detection and multi-class agency routing. |

---

### 🛠️ Technical Stack

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

**Machine Learning, Vision & Audio**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend, Databases & Infrastructure**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis%20%2F%20BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare%20Tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

### 📊 GitHub Activity

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Turusore08&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Turusore08&layout=compact&langs_count=8&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

