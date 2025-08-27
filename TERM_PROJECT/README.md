# 🚘 Tracking Research Focus on Autonomous Driving Over Time  

## 📌 Project Overview  
This project analyzes the **evolution of autonomous driving research** by leveraging **NLP techniques** on a large corpus of academic publications.  
We aim to uncover **dominant research themes, trends, and influential external factors** that have shaped the trajectory of autonomous vehicle (AV) research over the years.  

---

## 🎯 Objectives  
- Collect & preprocess academic publications on autonomous driving.  
- Analyze dominant research themes using **topic modeling (LDA, LSA, BERTopic)**.  
- Track how themes have shifted over time.  
- Provide actionable insights for researchers and industry stakeholders.  

---

## 🛠️ Methodology  

1. **Data Collection**  
   - Sources: **Scopus (2,696 papers), PubMed (10,840), arXiv (6,597)**  
   - Total: **20,133 papers → cleaned to 17,704 → annotated to 9,317 relevant papers**  

2. **Preprocessing**  
   - Duplicate & null-value removal  
   - Stopword removal, tokenization, lemmatization  
   - Annotation using **Llama 3** (>95% consistency)  

3. **Analysis**  
   - Topic Modeling: **LDA, LSA, BERTopic**  
   - Temporal Trend Analysis  
   - Visualization: **Word clouds, coherence scores, topic evolution graphs**  

---

## 📊 Results  

- **LDA**: Clear separation of major research areas (computer vision, safety, AI traffic systems).  
- **LSA**: Captured latent relationships but less interpretability.  
- **BERTopic**: Outperformed others with domain-specific terminology and nuanced topics (ethics, fleet management, hybrid models).  
- **Trends Over Time**:  
  - *1995–2010*: Foundational work (GNSS, trajectory prediction).  
  - *2010–2015*: Growth in testing, simulation, LiDAR.  
  - *2016–2019*: Surge in safety, crash analysis, ML integration.  
  - *2020–2024*: Sharp increase in advanced learning, ethics, fleet autonomy.  

---

## ⚠️ Challenges & Limitations  
- Annotation quality limited by reliance on Llama3; could improve with GPT-4.  
- Topic model sensitivity to hyperparameters.  
- Overlap in academic papers across different venues → data redundancy.  

---

## 🚀 Future Work  
- Incorporating **multimodal data** (patents, industry reports, news).  
- Using **advanced LLM-based NLP models** for deeper semantic analysis.  
- Improving relevance filtering with hybrid human + AI annotation.  

---
