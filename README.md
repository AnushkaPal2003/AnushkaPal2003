# Hi, I'm Anushka Pal 👋

**Data Scientist & AI Engineer** — building RAG pipelines, agentic systems, knowledge graphs, and end-to-end ML systems.

Open to full-time **Data Science / ML / AI Engineer** roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anushka-pal-a677731ba/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/AnushkaPal2003)

---

## 🚀 Projects

| | Project | Description | Stack |
|---|---|---|---|
| 🤖 | [Multi-Agent AI Research Platform](https://github.com/AnushkaPal2003/Investment_Research_crew) | 4-agent CrewAI pipeline — industry researcher and financial analyst run in parallel, a risk-reviewer agent cross-checks both for contradictions and unverified claims, and a report writer finalizes the brief; converts a single company name into a structured due-diligence report; FastAPI backend deployed on Render + Streamlit frontend, Docker Compose, GitHub Actions CI/CD | CrewAI · FastAPI · Streamlit · Groq · Tavily · Docker |
| 🏥 | [Healthcare Customer Support — Intelligent Router Agent](https://github.com/AnushkaPal2003/Healthcare_Customer_Support_Agent) | LangGraph-based agentic RAG system that categorizes queries by department (billing/appointments/records/insurance), detects sentiment, and routes via conditional edges — negative/distress sentiment escalates to human or on-call teams, positive/neutral triggers department-filtered RAG response; Pydantic structured output prevents hallucinated categories, MemorySaver persists per-session history | LangGraph · GPT-4o · ChromaDB · LangSmith · Streamlit |
| 📋 | [HR Policy Assistant — Corrective RAG (CRAG)](https://github.com/AnushkaPal2003/crag_hr_assistant) | LangGraph-based corrective RAG with LLM document grading — filters irrelevant retrievals before generation, automatically rewrites query and falls back to Tavily web search when no relevant docs are found, reducing hallucination risk from irrelevant context; FastAPI backend + Streamlit frontend, per-response source attribution (knowledge base vs. web fallback), end-to-end LangSmith observability | LangGraph · OpenAI (GPT-4o-mini) · ChromaDB · Tavily · FastAPI · Streamlit |
| 🔍 | [Hybrid RAG — Confidence-Aware Retrieval](https://github.com/AnushkaPal2003/Hybrid_Rag) | Solved RAG's silent failure mode — hybrid BM25 + ChromaDB retrieval with min-max normalized weighted score fusion generates a confidence threshold, routing low-confidence queries to Tavily web search fallback instead of unsupported generation; on-demand DeepEval layer tracks Answer Relevancy, Faithfulness, Contextual Precision/Recall & Hallucination per query | BM25 · ChromaDB · Tavily · GPT-4o-mini · DeepEval · Python |
| 🌐 | [MCP Research Agent](https://github.com/AnushkaPal2003) | 3-node LangGraph workflow (Planner, Researcher, Synthesizer) where nodes communicate exclusively through an MCP client layer, enforcing clean protocol boundaries between agent logic and tool execution; 4 MCP tools (web search, page fetch, note save/retrieve) exposed via a FastMCP server | FastMCP · LangGraph · Groq · Tavily · Streamlit |
| 🕸️ | [Graph RAG — Amazon Reviews](https://github.com/AnushkaPal2003/graph-rag-amazon-reviews) | Knowledge Graph-powered RAG over Amazon phone reviews — LLM router classifies intent, hybrid search (keyword + semantic), 1,701 nodes across Brand → Phone → Review relationships | Neo4j AuraDB · Azure OpenAI · Streamlit |
| 🖼️ | [Multimodal RAG — PDF](https://github.com/AnushkaPal2003/multimodal-rag-pdf) | RAG pipeline that parses text, tables, and images from PDFs using Unstructured (hi-res mode) — GPT-4o vision summarizes each modality, MultiVectorRetriever embeds summaries in ChromaDB but returns full context from Redis docstore | GPT-4o · ChromaDB · Redis · LangChain · Unstructured |
| 📄 | [Chat with PDF](https://github.com/AnushkaPal2003/Chat-with-your-PDF) | RAG pipeline enabling semantic Q&A across PDF documents — 4 stages: ingestion, chunking, embedding, retrieval | LangChain · ChromaDB · SentenceTransformer · Groq |
| ✅ | [Fact-Check Agent](https://github.com/AnushkaPal2003) | Extracts claims from a PDF, verifies each against live web search (Tavily), and uses GPT-4o-mini as a verdict engine; built and deployed for a real product assessment | Python · Tavily · OpenAI · Streamlit |
| 🧪 | [PromptForge](https://github.com/AnushkaPal2003/promptforge) | Multi-provider prompt evaluation tool comparing LLM reasoning across models | Python · Streamlit · Groq · OpenAI |
| 📰 | [Fake News Detection](https://github.com/AnushkaPal2003) | Trained and compared RNN, LSTM, GRU, and TF-IDF + Logistic Regression on the ISOT dataset (44K+ articles) using Word2Vec embeddings — GRU achieved 99.84% accuracy / 0.9999 ROC-AUC; deployed as a live Streamlit demo with GitHub Actions CI | TensorFlow/Keras · Word2Vec · MLflow · Streamlit · GitHub Actions |
| 🔴 | [Credit Card Fraud Detection](https://github.com/AnushkaPal2003/Credit-Card-Fraud-Detection) | Unsupervised fraud detection on severely imbalanced data using Isolation Forest — ROC-AUC 0.9539, Average Precision 0.1717, logged with MLflow, containerized with Docker | Isolation Forest · MLflow · Docker |
| 🏠 | [Boston Real Estate Price Prediction](https://github.com/AnushkaPal2003/Boston-Estate-Price-Predictor) | 10 regression models compared — XGBoost best (Test R² 0.888, CV R² 0.838), deployed as Streamlit app | Python · XGBoost · Scikit-learn · Streamlit |
| 📉 | [Telecom Customer Churn](https://github.com/AnushkaPal2003/Telecom-Churn) | 8 classifiers compared — Logistic Regression best (~82% accuracy), Streamlit deployment for real-time prediction | Python · Scikit-learn · Logistic Regression |
| 🧠 | [Sentiment Analysis](https://github.com/AnushkaPal2003/sentiment-analysis) | End-to-end NLP pipeline — 3 models trained, ~87.9% accuracy, tracked with MLflow, deployed on Azure with GitHub Actions CI/CD | TF-IDF · Logistic Regression · SVM · MLflow · Docker |
| 🎬 | [Movie Recommendation System](https://github.com/AnushkaPal2003/Movie-Recommendation-system) | Content-based filtering on 10K+ movies — unified tags (genres, keywords, overview, cast, director), TF-IDF + cosine similarity, top-5 recommendations | Python · TfidfVectorizer · Cosine Similarity |
| 👥 | [Customer Segmentation](https://github.com/AnushkaPal2003/Customer-Segmentation) | KMeans clustering — 5 optimal segments, silhouette score ~0.55 for model validation | K-Means · Python · Seaborn |
| 🐱 | [Cat vs Dog – Deep Learning](https://github.com/AnushkaPal2003/Deep-Learning) | 4-layer CNN on 25K images — ~92% train, ~85% val accuracy, data augmentation applied | TensorFlow · Keras · CNN |
| 🦠 | [Covid Forecasting – Prophet](https://github.com/AnushkaPal2003/Facebook-Prophet-Model-Covid-Dataset) | Time series forecasting of Covid trends — 100-day predictions, MAPE 1.6%–2.7% | Python · Prophet · Pandas · Matplotlib |
| 🧪 | [A/B Testing – Landing Page](https://github.com/AnushkaPal2003/AB-Testing-) | Two-proportion Z-test on 35K+ conversions, visualised results | Python · Statsmodels · Matplotlib · Seaborn |
| 📊 | [Zomato Analytics Dashboard](https://github.com/AnushkaPal2003/ZomatoDashboard) | Multi-city restaurant analytics with DAX-driven KPIs, geographic maps, dynamic filters, drill-down by location/rating/revenue segment | Power BI · DAX · Power Query |
| 🏥 | [Diabetes Prediction](https://github.com/AnushkaPal2003/Diabetes-Prediction-Model) | Classification model with feature engineering and model evaluation | Python · Scikit-learn |
| ☕ | [Coffee Sales Dashboard](https://github.com/AnushkaPal2003/Coffee-PowerBI) | Sales performance dashboard with KPIs and trend analysis | Power BI · DAX |
| 👩‍💼 | [Employee Dashboard](https://github.com/AnushkaPal2003/Employee-Dashboard) | SQL-based HR analytics with salary and hiring trend insights | SQL · Power BI |

---

## 🛠️ Tech Stack

**Languages** &nbsp; ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**ML / DL** &nbsp; ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat) ![Random Forest](https://img.shields.io/badge/Random_Forest-228B22?style=flat)

**Agentic AI** &nbsp; ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat) ![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat) ![CrewAI](https://img.shields.io/badge/CrewAI-1C3C3C?style=flat) ![MCP](https://img.shields.io/badge/MCP-1C3C3C?style=flat)

**MLOps** &nbsp; ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**BI & Viz** &nbsp; ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

**Gen-AI & RAG** &nbsp; ![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat) ![ChromaDB](https://img.shields.io/badge/ChromaDB-7289DA?style=flat) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat) ![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat&logo=neo4j&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Tavily](https://img.shields.io/badge/Tavily-FF6B35?style=flat) ![Unstructured](https://img.shields.io/badge/Unstructured-6B7280?style=flat) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-8B5CF6?style=flat) ![RAG](https://img.shields.io/badge/RAG-FF6B6B?style=flat) ![Graph RAG](https://img.shields.io/badge/Graph_RAG-008CC1?style=flat) ![Multimodal RAG](https://img.shields.io/badge/Multimodal_RAG-7C3AED?style=flat) ![Agentic RAG](https://img.shields.io/badge/Agentic_RAG-1C3C3C?style=flat)

**Cloud** &nbsp; ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

---

## 📊 GitHub Stats

![Anushka's GitHub stats](https://github-readme-stats.vercel.app/api?username=AnushkaPal2003&show_icons=true&theme=default&hide_border=true&count_private=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=AnushkaPal2003&layout=compact&hide_border=true&theme=default)

---

*Open to full-time Data Science / ML / AI Engineer roles. Feel free to reach out!*
