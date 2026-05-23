<div align="center">

# Pranav Dubey

CS undergrad at VIT Bhopal. I build AI systems that work in production —  
not just in notebooks.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranavdubey17)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/)
[![Codeforces](https://img.shields.io/badge/Codeforces-%231F8ACB.svg?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/)
[![Gmail](https://img.shields.io/badge/Email-pranavdubeyy%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:pranavdubeyy@gmail.com)

</div>

---

Most of what I build sits at the intersection of deep learning and backend engineering —  
training models, wiring them into APIs, and making sure they hold up under real conditions.  
Currently interested in computer vision, LLM pipelines, and product analytics.

---

## Tech Stack

**Languages:** Python · Java · SQL

**AI / ML:** PyTorch · TensorFlow · Scikit-learn · Keras · YOLOv8 · ConvNeXt · NumPy · Pandas · Matplotlib

**Backend:** FastAPI · Spring Boot · Node.js · REST APIs · JWT + RBAC · AES-GCM · Redis

**Infra:** Docker · PostgreSQL · SQLite · MinIO · Render · Vercel · Hugging Face Spaces

---

## Projects

### AI Video Surveillance — Anomaly Detection
`PyTorch` `YOLOv8` `ResNet50` `LSTM` `Grad-CAM` `FastAPI` `Streamlit` `Docker`

Built an end-to-end CCTV anomaly detection system on the UCF-Crime dataset — 1.37M+ frames across 1,900 videos. The goal was to go beyond black-box scoring and make the model's reasoning interpretable.

- **0.803 AUC-ROC** — outperforms Sultani et al. 2018 baseline (75.41%) using ranking loss optimization and weighted minority sampling
- Grad-CAM saliency overlays produce frame-level visual explanations
- Async FastAPI backend with background job queues and streaming inference endpoints
- Streamlit dashboard for real-time anomaly visualization

[![Demo](https://img.shields.io/badge/Live%20Demo-00C7B7?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/spaces/Pranavdubey1725/ai-video-surveillance) [![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pranavdubey1725)

---

### Congenital Heart Defect Prediction
`ConvNeXt-Base` `PyTorch` `Spring Boot` `FastAPI` `PostgreSQL` `Redis` `Docker`

Chest X-ray classifier for detecting congenital heart defects (Normal / ASD / VSD). The medical domain meant imbalanced data and high stakes for false negatives — both shaped every design decision.

- **82.6% accuracy · 0.83 macro F1** on a 612-image dataset
- CLAHE augmentation + focal loss + SE recalibration for imbalanced classes
- **0.96 VSD precision · 0.94 Normal recall**
- 22+ REST APIs — AES-GCM encryption, JWT + RBAC auth, Redis caching, MinIO storage

[![Demo](https://img.shields.io/badge/Live%20Demo-00C7B7?style=flat-square&logo=netlify&logoColor=white)](#) [![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pranavdubey1725)

---

### Customer Support Automation Platform
`FastAPI` `Groq Llama 3.3-70b` `Streamlit` `SQLite` `Docker`

AI pipeline that handles the full support ticket lifecycle — from intake to drafted reply — without a human in the loop until review.

- Intent classification → 5-tier urgency scoring → routing across 8 queues → LLM-drafted reply, **<3s end-to-end**
- Decoupled NLP modules with Pydantic contracts, designed for plug-and-play model upgrades
- Multi-role dashboard for agent approve/edit/reject workflows and supervisor analytics

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pranavdubey1725)

---

### E-Commerce Product Metrics Analysis
`Python` `Pandas` `NumPy` `Matplotlib`

Behavioral analytics on large-scale e-commerce event data — the kind of analysis that tells you where users drop off and why.

- DAU / MAU / stickiness metrics
- View → cart → purchase funnel analysis
- Cohort-based retention and checkout friction identification

[![Repo](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/pranavdubey1725/E-Commerce-App-Usage-Analysis)

---

## GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=pranavdubey1725&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=pranavdubey1725&layout=compact&theme=tokyonight&hide_border=true)

</div>
