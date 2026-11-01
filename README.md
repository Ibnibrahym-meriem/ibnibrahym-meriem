<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0D0D12,50:4C1D95,100:A855F7&text=Meriem%20Ibn%20Ibrahym&fontColor=FFFFFF&fontSize=46&fontAlignY=38&desc=AI%20Engineering%20%E2%80%A2%20Data%20Engineering%20%E2%80%A2%20Machine%20Learning&descSize=16&descAlignY=58&animation=fadeIn" width="100%" alt="Meriem Ibn Ibrahym"/>

<a href="https://meriem-ibnibrahym.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=A855F7&center=true&vCenter=true&width=620&lines=Je+con%C3%A7ois+des+assistants+RAG+et+des+LLM+appliqu%C3%A9s;Je+construis+des+pipelines+de+donn%C3%A9es+temps+r%C3%A9el;J'int%C3%A8gre+des+mod%C3%A8les+ML+dans+de+vraies+applications;En+recherche+d'un+PFE+de+6+mois+%E2%80%94+f%C3%A9vrier+2027" alt="Typing SVG"/>
</a>

<br/><br/>

<a href="https://meriem-ibnibrahym.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D0D12?style=for-the-badge&logo=vercel&logoColor=A855F7" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/meriem-ibn-ibrahym-30910b345/"><img src="https://img.shields.io/badge/LinkedIn-0D0D12?style=for-the-badge&logo=linkedin&logoColor=A855F7" alt="LinkedIn"/></a>
<a href="mailto:ibnibrahym.meriem@gmail.com"><img src="https://img.shields.io/badge/Email-0D0D12?style=for-the-badge&logo=gmail&logoColor=A855F7" alt="Email"/></a>

<br/>

<img src="https://img.shields.io/badge/📍%20Tanger,%20Maroc-1E1B2E?style=flat-square" alt="Tanger"/>
<img src="https://img.shields.io/badge/🚀%20Mobilité-Casablanca%20%26%20Rabat-1E1B2E?style=flat-square" alt="Mobilité"/>
<img src="https://img.shields.io/badge/🎯%20PFE%206%20mois-Dès%20février%202027-7C3AED?style=flat-square" alt="PFE"/>

</div>

<br/>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> À propos

```python
class MeriemIbnIbrahym:
    formation   = "Master IA & Data Science — FST de Tanger (diplôme 2027)"
    focus       = ["AI Engineering", "IA générative & RAG", "Data Engineering", "MLOps"]
    approche    = "Comprendre le besoin métier → expérimenter → mesurer → déployer"
    recherche   = "PFE de 6 mois · dès février 2027"
    langues     = ["Français", "Arabe", "Anglais"]
```

Mon parcours se situe à la croisée de **l'intelligence artificielle**, de **l'ingénierie des données** et du **développement logiciel**.
J'aime partir d'un vrai besoin, tester plusieurs approches, évaluer rigoureusement les résultats — puis livrer une solution utilisable.

<br/>

<!-- ═══════════════════════════ PROJECTS ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> Projets phares

### 🧠 GuardianYARA — Génération de règles YARA par RAG
<sub>IA générative · RAG · Cybersécurité · <i>Projet d'équipe</i></sub>

> **🔍 Problème**
> Écrire des règles de détection YARA demande une expertise pointue et beaucoup de temps. Les analystes partent souvent d'une simple description de menace en langage naturel, qu'ils doivent traduire manuellement en règle exploitable.

> **💡 Solution**
> Un système RAG qui transforme une description de menace en règle YARA : une **recherche hybride FAISS + BM25** retrouve les règles et documents les plus pertinents, puis un **LLM** génère la règle à partir de ce contexte. Plusieurs architectures RAG et modèles open source ont été comparés.

> **📈 Résultats**
> Un assistant capable de proposer des règles YARA à partir de texte libre, avec un **benchmark comparatif** de Qwen2.5, Mistral et Flan-T5 pour identifier la configuration la plus adaptée.

`Python` `NLP` `RAG` `FAISS` `BM25` `Qwen2.5` `Mistral` `Flan-T5` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/ElMansouriAya/yara-rag-generator)

<br/>

### 📡 Real-Time Amazon Reviews Sentiment Analysis
<sub>Big Data · NLP · MLOps</sub>

> **🔍 Problème**
> Les avis clients arrivent en continu et en très grand volume : impossible de les analyser manuellement ou en traitement par lots classique pour suivre l'opinion des clients en temps réel.

> **💡 Solution**
> Un pipeline **streaming de bout en bout** : ingestion des avis avec **Kafka**, traitement et classification NLP avec **Spark Streaming**, stockage dans **MongoDB** et visualisation dans un dashboard **Flask**. Le tout conteneurisé avec **Docker**, orchestré par **Airflow** et suivi avec **MLflow**.

> **📈 Résultats**
> Pipeline opérationnel sur **568 454 avis clients**, avec des sentiments visualisés en temps réel et des expériences de modèles tracées et reproductibles.

`Python` `Kafka` `PySpark` `NLP` `MongoDB` `Flask` `Docker` `Airflow` `MLflow` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/Ibnibrahym-meriem/Amazon-Reviews-Sentiment-Analysis-BigData)

<br/>

### 💧 AquaLeak — Détection de fuites dans les réseaux d'eau
<sub>Deep Learning · Séries temporelles</sub>

> **🔍 Problème**
> Les fuites dans les réseaux de distribution d'eau provoquent d'importantes pertes et sont souvent détectées trop tard, faute de pouvoir exploiter rapidement les données des capteurs.

> **💡 Solution**
> Préparation et fusion d'environ **1,47 million de lignes** issues du jeu de données **BattLeDIM 2018**, puis entraînement d'un modèle **LSTM** intégrant un embedding de l'identifiant des conduites pour détecter **et localiser** les fuites. Résultats restitués via une **API FastAPI** et un dashboard avec export PDF.

> **📈 Résultats** — sur le jeu d'évaluation du projet
>
> | Accuracy | F1 — fuite | Rappel — fuite | AUC |
> |:-:|:-:|:-:|:-:|
> | **96,3 %** | **0,95** | **96 %** | **0,998** |

`Python` `TensorFlow` `Keras` `LSTM` `Pandas` `NumPy` `FastAPI` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/Ibnibrahym-meriem/water-leak-detection)

<br/>

### ⚙️ Data Analytics & Machine Learning Platform
<sub>Plateforme No-Code ML · <i>Projet d'équipe</i></sub>

> **🔍 Problème**
> Mener un projet de données implique de jongler entre plusieurs outils et d'écrire du code à chaque étape — un frein pour les utilisateurs non techniques.

> **💡 Solution**
> Une plateforme web qui centralise tout le cycle : **collecte automatisée** avec Playwright, **nettoyage** avec Pandas et NumPy, **visualisation**, **entraînement de modèles** scikit-learn et **génération de rapports PDF** — via une API **FastAPI** et une interface **React**.

> **📈 Résultats**
> Un parcours complet, de la donnée brute au modèle évalué et au rapport, réalisable **sans écrire une ligne de code** depuis une seule interface.

`Python` `FastAPI` `React` `Pandas` `NumPy` `scikit-learn` `Playwright` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/Ibnibrahym-meriem/PlatformNo-Code-ML)

<br/>

<!-- ═══════════════════════════ STACK ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> Stack technique

<div align="center">

<img src="https://skillicons.dev/icons?i=py,tensorflow,sklearn,fastapi,django,flask,react,ts,tailwind,vite&theme=dark" alt="Stack 1"/>
<br/>
<img src="https://skillicons.dev/icons?i=kafka,docker,postgres,mysql,mongodb,redis,sqlite,linux,git,postman&theme=dark" alt="Stack 2"/>

</div>

<br/>

| Domaine | Outils |
|:--|:--|
| 🤖 **IA & Machine Learning** | Python · scikit-learn · TensorFlow · Keras · LSTM · Classification · Régression · Évaluation de modèles |
| ✨ **IA générative & NLP** | LLM · RAG · LangChain · Groq · Gemini · Embeddings · FAISS · Pinecone · BM25 · Prompt Engineering · TF-IDF |
| 🔄 **Data Engineering & MLOps** | SQL · Pandas · NumPy · PySpark · Kafka · Hadoop · Airflow · MLflow · ETL · Talend · Pentaho · Apache NiFi |
| 🗄️ **Bases de données** | PostgreSQL · MySQL · MongoDB · SQLite |
| 🧩 **Back-end & API** | FastAPI · Django · DRF · Flask · Streamlit · REST · JWT · Celery · Redis |
| 🎨 **Front-end** | React · TypeScript · JavaScript · Tailwind CSS · Vite · TanStack Query |
| 📊 **BI, tests & outils** | Power BI · Matplotlib · Docker Compose · pytest · Playwright · Git · Linux |

### 🌱 En cours d'apprentissage

<img src="https://img.shields.io/badge/IA_agentique-1E1B2E?style=for-the-badge&logo=robotframework&logoColor=A855F7" alt="IA agentique"/>
<img src="https://img.shields.io/badge/Google_Cloud-1E1B2E?style=for-the-badge&logo=googlecloud&logoColor=A855F7" alt="Google Cloud"/>
<img src="https://img.shields.io/badge/Virtualisation-1E1B2E?style=for-the-badge&logo=virtualbox&logoColor=A855F7" alt="Virtualisation"/>

<br/>

<!-- ═══════════════════════════ EDUCATION ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> Formation

| | Diplôme | Établissement | Année |
|:-:|:--|:--|:-:|
| 🎓 | **Master Intelligence Artificielle & Data Science** | FST de Tanger — Université Abdelmalek Essaâdi | 2027 |
| 📘 | **Licence Sciences et Techniques — Analytique de Données** | FST de Tanger | 2025 |

<br/>

<!-- ═══════════════════════════ STATS ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> Activité GitHub

<div align="center">

<img src="https://streak-stats.demolab.com?user=Ibnibrahym-meriem&theme=dark&hide_border=true&background=0D0D12&ring=A855F7&fire=A855F7&currStreakLabel=A855F7&sideLabels=C9C9D9&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=8B8BA0&stroke=2A2540&locale=fr" alt="GitHub Streak"/>

</div>

<br/>

<!-- ═══════════════════════════ FOOTER ═══════════════════════════ -->
<div align="center">

### Une opportunité en Data & IA ?

**AI Engineering · Data Engineering · Data Science**<br/>
Disponible pour un **PFE de six mois dès février 2027**

<a href="mailto:ibnibrahym.meriem@gmail.com"><img src="https://img.shields.io/badge/Me_contacter-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Contact"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:A855F7,50:4C1D95,100:0D0D12" width="100%" alt=""/>

</div>
