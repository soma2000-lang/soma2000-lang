# Somasree Majumder

**ML Engineer — Defense CV · Open Source · Systems from Paper to Production**

Building real-time computer vision systems for defense at [DeepEdge](https://deepedge.ai). Contributor to PyTorch Lightning, Hugging Face, and KerasCV/NLP. [LinkedIn LIFT Scholar 2022](https://www.linkedin.com) (Top 500 women technologists globally, 0.5% acceptance).

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/somasree-majumder-3533411aa/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=flat&logo=google-chrome&logoColor=white)](https://soma2000-lang.github.io/portfolio)
[![LeetCode](https://img.shields.io/badge/LeetCode_650+-FFA116?style=flat&logo=leetcode&logoColor=black)](https://leetcode.com/soma2000-lang/)

---

## What I'm Working On

**Anti-UAV Tracking @ DeepEdge** — End-to-end production system deployed at 3 defense installations, processing infrared video in real-time on NVIDIA Jetson edge devices.

- Sub-pixel tracking ensemble (Lucas-Kanade + TAPNet + CoTracker) extending detection range 1.5km → 5km — contributed to $2M+ contract renewal
- Hybrid CV pipeline (YOLOv8 + Kalman + MOG2/SVM): 95%+ accuracy, 80% false positive reduction
- 4.2x inference speedup (250ms → 60ms) via TensorRT quantization + CUDA kernel fusion for 30fps edge deployment
- 3D world-frame localization: monocular depth + camera calibration + IMU fusion → <0.5m error

---

## Open Source Contributions

| Project | Stars | What I Did |
|---|---|---|
| [**PyTorch Lightning**](https://github.com/Lightning-AI/pytorch-lightning) | 27K+ | [PRs →](https://github.com/Lightning-AI/pytorch-lightning/pulls?q=author%3Asoma2000-lang) |
| [**Hugging Face Transformers**](https://github.com/huggingface/transformers) | 135K+ | [PRs →](https://github.com/huggingface/transformers/pulls?q=author%3Asoma2000-lang) |
| [**KerasCV / KerasNLP**](https://github.com/keras-team/keras-cv) | — | Implemented augmentation layers used by 35K+ engineers |
| [**Unify.ai (Ivy)**](https://github.com/unifyai/ivy) | — | Built 15+ TensorRT OpConverters, 3x faster inference, 40% memory reduction |

---

## Selected Projects

### [`Paper-Implementations-in-Deep-Learning`](https://github.com/soma2000-lang/Paper-Implementations-in-Deep-Learning)
From-scratch implementations of key deep learning papers in PyTorch. Not wrappers — actual algorithm reimplementations to understand the math.

### [`vector-db`](https://github.com/soma2000-lang/vector-db) — Custom Vector Database
HNSW graph-based approximate nearest neighbor search, built from scratch in Python with minimal dependencies. No LangChain, no Pinecone — just NumPy and the algorithm.

### [`flight-scanner`](https://github.com/soma2000-lang/flight-scanner) — RAG Flight Analytics
Natural language queries over structured flight data using DeepSeek-R1 (70B) + LLaMA 3.2 (3B) with RAG architecture, ChromaDB, and FastAPI.

### [`amazon-classification`](https://github.com/soma2000-lang/amazon-classification) — Large-Scale Product Classification
Fine-tuned ALBERT on 500K Amazon listings across 27 categories with 1:150 class imbalance. 89% F1 — beat BERT by 12% and the production baseline by 10%. Deployed with TensorRT.

### [`childmind-prediction`](https://github.com/soma2000-lang/childmind-prediction) — ChildMind Anxiety Prediction
Gated RNNs analyzing children's physical activity patterns for early detection of problematic internet use. Healthcare ML with real clinical relevance.

### [`food-delivery`](https://github.com/soma2000-lang/food-delivery) — Full-Stack Delivery Platform
Django REST + JWT auth. Vendor management, proximity search, payment integration, real-time order tracking, push notifications. Shows I build complete products, not just models.

---

## Competition Results

| Event | Result |
|---|---|
| **Challang Global Hackathon** | Top 10 / 100 teams worldwide — disaster response CV (satellite imagery + EfficientNet, 91% IoU) |
| **HackerEarth ML Challenge** | Rank 18 / 2,500 |
| **Cipla Datathon** | Rank 12 / 1,000+ (Top 1.2%) |
| **Google Code Jam for Women** | Rank 1,600 / 50,000+ |

---

## Publications

- **"Privacy-Preserving Cloud Computing"** — Homomorphic encryption for secure computation. IEMATICS 2020
- **"ML in Medical Diagnosis"** — Applied ML for clinical diagnostics. SPECTRUM 2020

---

## Professional Background

**DeepEdge** (Defense AI Startup) — ML Engineer, Mar 2025 – Present
**Deloitte** (AI Center of Excellence) — ML Engineer, Jul 2023 – Mar 2025
**Unify.ai** — ML Engineer (Contract), Feb – May 2023

B.Tech ECE, Institute of Engineering & Management, Kolkata — 8.94/10 CGPA

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=soma2000-lang&count_private=true&show_icons=true&theme=default&hide_border=true&include_all_commits=true" alt="GitHub Stats" height="160"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=soma2000-lang&theme=default&hide_border=true" alt="GitHub Streak" height="160"/>
</p>
