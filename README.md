<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0D0D12,50:4C1D95,100:A855F7&text=Meriem%20Ibn%20Ibrahym&fontColor=FFFFFF&fontSize=46&fontAlignY=38&desc=AI%20Engineering%20%E2%80%A2%20Data%20Engineering%20%E2%80%A2%20Machine%20Learning&descSize=16&descAlignY=58&animation=fadeIn" width="100%" alt="Meriem Ibn Ibrahym"/>

<a href="https://meriem-ibnibrahym.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=A855F7&center=true&vCenter=true&width=620&lines=Je+con%C3%A7ois+des+assistants+RAG+et+des+LLM+appliqu%C3%A9s;Je+construis+des+pipelines+de+donn%C3%A9es+temps+r%C3%A9el;J'int%C3%A8gre+des+mod%C3%A8les+ML+dans+de+vraies+applications;En+recherche+d'un+PFE+de+6+mois+%E2%80%94+f%C3%A9vrier+2027" alt="Typing SVG"/>
</a>

<br/><br/>

<a href="https://meriem-ibnibrahym.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D0D12?style=for-the-badge&logo=vercel&logoColor=A855F7" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/meriem-ibn-ibrahym-30910b345/"><img src="https://img.shields.io/badge/LinkedIn-0D0D12?style=for-the-badge&logo=linkedin&logoColor=A855F7" alt="LinkedIn"/></a>
<img src="https://img.shields.io/badge/ibnibrahym.meriem%40gmail.com-0D0D12?style=for-the-badge&logo=gmail&logoColor=A855F7" alt="ibnibrahym.meriem@gmail.com"/>

<br/>

<img src="https://img.shields.io/badge/📍%20Tanger,%20Maroc-1E1B2E?style=flat-square" alt="Tanger"/>
<img src="https://img.shields.io/badge/🚀%20Mobilité-Casablanca%20%26%20Rabat-1E1B2E?style=flat-square" alt="Mobilité"/>
<img src="https://img.shields.io/badge/🎯%20PFE%206%20mois-Dès%20février%202027-7C3AED?style=flat-square" alt="PFE"/>

</div>

<br/>

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> À propos

Étudiante en dernière année du **Master Intelligence Artificielle & Data Science** à la FST de Tanger, je construis des solutions qui relient **l'IA générative**, **l'ingénierie des données** et **le développement logiciel**. J'aime partir d'un vrai besoin métier, expérimenter plusieurs approches, mesurer rigoureusement les résultats, puis transformer le modèle en une application réellement utilisable — qu'il s'agisse d'un assistant RAG, d'un pipeline de données en temps réel ou d'un modèle de Deep Learning exposé via une API. Je recherche aujourd'hui un **PFE de six mois à partir de février 2027** en **AI Engineering**, **Data Engineering** ou **Data Science**, au sein d'une équipe où je pourrai contribuer à des projets concrets, apprendre et partager mes idées.

<br/>

<!-- ═══════════════════════════ PROJECTS ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> Projets phares

### 🧠 GuardianYARA — Génération de règles YARA par RAG
<sub>IA générative · RAG · Cybersécurité · <i>Projet d'équipe</i></sub>

Écrire des règles de détection YARA exige une expertise pointue et beaucoup de temps, alors que les analystes partent souvent d'une simple description de menace en langage naturel. Pour réduire cet effort, nous avons conçu un système RAG qui combine une **recherche hybride FAISS + BM25**, chargée de retrouver les règles et documents les plus pertinents, avec un **LLM** qui génère la règle à partir de ce contexte. Le résultat est un assistant capable de proposer des règles YARA à partir de texte libre, accompagné d'un **benchmark comparatif** de plusieurs architectures RAG et des modèles Qwen2.5, Mistral et Flan-T5 afin d'identifier la configuration la plus adaptée.

`Python` `NLP` `RAG` `FAISS` `BM25` `Qwen2.5` `Mistral` `Flan-T5` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/ElMansouriAya/yara-rag-generator)

<br/>

### 📡 Real-Time Amazon Reviews Sentiment Analysis
<sub>Big Data · NLP · MLOps</sub>

Les avis clients arrivent en continu et en très grand volume, ce qui rend impossible leur analyse manuelle ou par simple traitement par lots lorsqu'on veut suivre l'opinion en temps réel. J'ai donc construit un pipeline **streaming de bout en bout** : les avis sont ingérés par **Kafka**, classifiés par un modèle NLP dans **Spark Streaming**, stockés dans **MongoDB** puis visualisés dans un dashboard **Flask**, le tout conteneurisé avec **Docker**, orchestré par **Airflow** et suivi avec **MLflow**. Le pipeline est opérationnel sur **568 454 avis clients**, avec des sentiments visualisés en temps réel et des expériences de modèles tracées et reproductibles.

`Python` `Kafka` `PySpark` `NLP` `MongoDB` `Flask` `Docker` `Airflow` `MLflow` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/Ibnibrahym-meriem/Amazon-Reviews-Sentiment-Analysis-BigData)

<br/>

### 💧 AquaLeak — Détection de fuites dans les réseaux d'eau
<sub>Deep Learning · Séries temporelles</sub>

Les fuites dans les réseaux de distribution d'eau entraînent d'importantes pertes et sont souvent repérées trop tard, faute d'exploiter rapidement les données des capteurs. À partir du jeu de données **BattLeDIM 2018**, j'ai préparé et fusionné environ **1,47 million de lignes**, puis entraîné un modèle **LSTM** intégrant un embedding de l'identifiant des conduites pour **détecter et localiser** les fuites, avec une restitution via une **API FastAPI** et un dashboard exportable en PDF. Sur le jeu d'évaluation du projet, le modèle atteint une **accuracy de 96,3 %**, un **F1 de 0,95** et un **rappel de 96 %** sur la classe fuite, ainsi qu'une **AUC de 0,998**.

`Python` `TensorFlow` `Keras` `LSTM` `Pandas` `NumPy` `FastAPI` &nbsp;·&nbsp; [**Voir le dépôt →**](https://github.com/Ibnibrahym-meriem/water-leak-detection)

<br/>

### ⚙️ Data Analytics & Machine Learning Platform
<sub>Plateforme No-Code ML · <i>Projet d'équipe</i></sub>

Mener un projet de données oblige à jongler entre plusieurs outils et à écrire du code à chaque étape, ce qui freine fortement les utilisateurs non techniques. Nous avons développé une plateforme web qui centralise tout le cycle : **collecte automatisée** avec Playwright, **nettoyage** avec Pandas et NumPy, **visualisation**, **entraînement de modèles** scikit-learn et **génération de rapports PDF**, le tout via une API **FastAPI** et une interface **React**. Il devient ainsi possible de passer de la donnée brute à un modèle évalué et à un rapport complet **sans écrire une seule ligne de code**, depuis une interface unique.

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

<br/>

<!-- ═══════════════════════════ ACTIVITY ═══════════════════════════ -->
## <img src="https://img.shields.io/badge/-%20-A855F7?style=flat-square" height="22"/> Activité

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ibnibrahym-meriem/Ibnibrahym-meriem/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ibnibrahym-meriem/Ibnibrahym-meriem/output/github-snake.svg"/>
  <img src="https://raw.githubusercontent.com/Ibnibrahym-meriem/Ibnibrahym-meriem/output/github-snake-dark.svg" width="100%" alt="Contributions GitHub"/>
</picture>

<br/><br/>

Je partage régulièrement mes projets, mes apprentissages et mes réflexions sur l'IA et la data sur LinkedIn.

<a href="https://www.linkedin.com/in/meriem-ibn-ibrahym-30910b345/"><img src="https://img.shields.io/badge/Suivre_mon_activité_sur_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Activité LinkedIn"/></a>

</div>

<br/>

<!-- ═══════════════════════════ FOOTER ═══════════════════════════ -->
<div align="center">

### Une opportunité en Data & IA ?

**AI Engineering · Data Engineering · Data Science**<br/>
Disponible pour un **PFE de six mois dès février 2027**

📧 **ibnibrahym.meriem@gmail.com**

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&section=footer&color=0:A855F7,50:4C1D95,100:0D0D12" width="100%" alt=""/>

</div>
