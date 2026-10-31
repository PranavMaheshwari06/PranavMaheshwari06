# Pranav Maheshwari

M.Sc. Artificial Intelligence Engineering student at Universität Passau, working student at Mercedes-Benz AG. Based in Böblingen, Germany.

## About

I work on machine learning for engineering and simulation data, retrieval-augmented generation (RAG), and video anomaly detection. At Mercedes-Benz I build surrogate models and data pipelines for car-body simulation, and I contributed RAG components to an internal assistant. My master's thesis is on weakly supervised anomaly detection in surveillance video.

I am looking for junior AI / ML engineering roles in Germany, available full-time from 01/2027 while I finish the thesis.

Languages: English (C1), German (B1).

## Currently

- Master's thesis (in progress): weakly supervised video anomaly detection with emergency-response routing
- Study-in-Germany Admissions Assistant (in progress): hybrid RAG system with a rules engine
- Working student at Mercedes-Benz AG, Sindelfingen

## Experience

| Period | Role | Work |
|---|---|---|
| 08/2025 - present | Working Student, Mercedes-Benz AG | PhysicsNeMo MeshGraphNet surrogate for car-body paint thickness; Python pipeline from Nastran/OpenFOAM data to training data; mesh-element classifier; RAG components and FastAPI services for an internal AI assistant |
| 12/2022 - 03/2023 | Market Research and Forecasting Intern, EventCart | Predictive models on sales data (50K+ records), SQL workflows, Tableau dashboards |
| 01/2022 - 04/2022 | Product Engineer Intern, Highradius | ML model extracting invoice fields, React.js dashboard; reduced manual invoice-processing time by 40% |

## Selected work

**[Weakly Supervised Video Anomaly Detection](https://github.com/PranavMaheshwari06/Weakly-supervised-Video-Anomaly-Detection)** (master's thesis, in progress, offline)
VideoMAE with LoRA, attention-based multi-instance learning trained on video-level labels only. Video-level AUROC 0.940 on 290 held-out videos (3 seeds). Ablations and failure modes are reported, including a negative result.
Python, PyTorch, Hugging Face Transformers, PEFT

**[Study-in-Germany Admissions Assistant](https://github.com/PranavMaheshwari06/Project_Rag)** (in progress)
Hybrid retrieval (BM25 + dense, RRF, cross-encoder reranking) producing cited eligibility reports. A rules engine makes the decision; the LLM only extracts and explains. Retrieval is evaluated on a gold set enforced in CI.
Python, FastAPI, React, Docker, Gemini API

**Paint-thickness surrogate and mesh classifier** (Mercedes-Benz AG)
MeshGraphNet surrogate for KTL e-coat paint thickness, R² 0.896 on the multi-case model. A PyTorch classifier for CFD property IDs reached macro-F1 0.85 on 9 unseen models, against 0.68 for a kNN baseline. Internal work, no code published.
PyTorch, PyTorch Geometric, NVIDIA PhysicsNeMo, OpenFOAM, Nastran, OpenUSD

**[Real-time vehicle collision detection](https://github.com/PranavMaheshwari06)** (bachelor's thesis)
Multi-vehicle tracking and collision detection with YOLOv3 and OpenCV; alert latency under 200 ms. Resulted in a research paper.

## Skills

| Area | Tools and methods |
|---|---|
| Languages | Python, SQL, JavaScript (React) |
| Machine learning | PyTorch, PyTorch Geometric, scikit-learn, graph neural networks, transformers, LoRA / PEFT, multi-instance learning, computer vision, anomaly detection |
| LLM and retrieval | RAG, BM25, dense retrieval, cross-encoder reranking, guardrails, retrieval evaluation, Gemini API |
| Simulation | NVIDIA PhysicsNeMo, OpenFOAM, Nastran, OpenUSD |
| Engineering | FastAPI, Docker, CI, Git, Linux, NumPy, pandas, OpenCV |

## Education

- M.Sc. Artificial Intelligence Engineering, Universität Passau (10/2023 - expected 02/2027)
- B.Tech. Computer Science, SRM Institute of Science and Technology, India (07/2019 - 05/2023)

## Contact

- Email: pranavmaheshwari0601@gmail.com
- LinkedIn: [pranavmaheshwari0617](https://www.linkedin.com/in/pranavmaheshwari0617)
- Portfolio: [PranavMaheshwari06.github.io](https://pranavmaheshwari06.github.io/PranavMaheshwari_AI.github.io)
## Hi there 👋

<!--
**PranavMaheshwari06/PranavMaheshwari06** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
