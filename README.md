# 👋 Hi, I'm Nikos Litharis

**AI Engineer** — building LLM pipelines and RAG systems at [Netcompany](https://netcompany.com)  
📍 Thessaloniki, Greece

[![CV](https://img.shields.io/badge/CV-PDF-2ea44f?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](Nikos_Litharis_CV.pdf)
[![LinkedIn](https://img.shields.io/badge/Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/nicklitharis)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail)](mailto:nicklitharis@gmail.com)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle)](https://kaggle.com/nikoslitharis)

---

## 🔨 Currently Building

- **TAXIS** — a production legal-research assistant for Greece's Independent Authority for Public Revenue (AADE), built on the Microsoft Agent Framework
- **MedLeaf RAG** — bilingual (Greek/English) retrieval-augmented QA over official EU medicine information, with cited answers and an evaluation gate in CI *(in progress)*
- **Evaluation pipelines** for LLM systems: versioned scenario datasets, gold sources and automated answer/citation scoring

---

## 💼 Professional Experience

**AI Engineer**  
[![Netcompany](https://img.shields.io/badge/Netcompany-0055A5?style=flat&logoColor=white)](https://netcompany.com)  
`Nov 2025 - Present` | Thessaloniki, Greece

- Own the evaluation and UAT pipeline for **TAXIS**, AADE's production legal-research assistant: versioned scenario datasets covering adversarial, citation, temporal and incomplete-context challenge sets, with gold sources, a CLI runner that scores answers and citations, and evidence-promotion tooling with runtime provenance
- Architected a durable, resumable batch-ingestion pipeline for large legal corpora (OpenAI Batch API, Azure AI Search v3) with recovery for expired leases and a live throughput dashboard
- Design evaluation suites for RAG retrieval quality — bilingual (Greek/English) cases over IEC standards documentation — and iterate on prompts, chunking and embeddings
- Added voice interaction to a RAG assistant by integrating Azure Speech SDK STT/TTS with managed-identity authentication

**Military Service**  
`Sep 2024 - Jun 2025` | Hellenic Army

**AI Development Intern**  
[![Prosperty](https://img.shields.io/badge/Prosperty-AI_Real_Estate-FF6B6B?style=flat&logo=homeadvisor&logoColor=white)](https://theprosperty.com)  
`Feb 2024 - Mar 2024` | Remote

- Built a GPT-3 generation tool in Python that cut listing-description production time from ~2 hours to under 30 seconds
- Fine-tuned language models on property data against tone and accuracy requirements
- Shipped the tool into the live listing platform as a REST API with the product and engineering teams

---

## 🚀 Featured Projects

### [Haystack & Elasticsearch Q&A Search](https://github.com/NickLitharis/haystack-elastic)
> Two retrieval pipelines over the same corpus — keyword (BM25) against semantic search with Haystack's EmbeddingRetriever — returning the top-5 answers by embedding similarity  
> ![Python](https://img.shields.io/badge/-Python-blue) ![Haystack](https://img.shields.io/badge/-Haystack-00A1E0) ![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571)

### [Medical Image Captioning](https://github.com/NickLitharis/medica)
> BSc thesis: a CNN encoder with an attention-based RNN decoder, in TensorFlow, generating captions for medical images  
> ![Python](https://img.shields.io/badge/-Python-blue) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00) ![Computer%20Vision](https://img.shields.io/badge/-Computer%20Vision-green)

### [Earthquake Prediction Analysis](https://github.com/NickLitharis/earthquake-prediction)
> Predicted earthquake magnitude from 251,000 historical seismic records, comparing three regression models — Gradient Boosting reached R² 0.86  
> ![Python](https://img.shields.io/badge/-Python-blue) ![ML](https://img.shields.io/badge/-Machine%20Learning-orange)

### [Network Analysis Toolkit](https://github.com/NickLitharis/networkxplorer)
> Modeled complex systems with NetworkX and Matplotlib  
> ![Graphs](https://img.shields.io/badge/-Graph%20Theory-green) ![DataViz](https://img.shields.io/badge/-Visualization-yellow)

### [Streamlit ML App](https://github.com/NickLitharis/streamlit-ml)
> Interactive ML demos built with Streamlit  
> ![Streamlit](https://img.shields.io/badge/-Streamlit-red) ![Python](https://img.shields.io/badge/-Python-blue)

---

## 🛠️ Technical Toolkit

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white)

**LLM & RAG**  
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?logo=microsoftazure&logoColor=white)
![Microsoft Agent Framework](https://img.shields.io/badge/Microsoft_Agent_Framework-5E5E5E?logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Haystack](https://img.shields.io/badge/Haystack-00A1E0?logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white)

**AI/ML**  
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit_learn-F7931E?logo=scikit-learn&logoColor=white)

**Data & Visualization**  
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

**Infrastructure**  
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?logo=gitlab&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)

---

## 🎓 Education

**Bachelor of Computer Science**  
[![Ionian University](https://img.shields.io/badge/Ionian_University-005FAB?style=flat&logoColor=white)](https://ionio.gr)  
`2019 - 2024` | Corfu, Greece

- **Thesis**: *Text Generation from Medical Images* — a CNN encoder with an attention-based RNN decoder in TensorFlow, generating captions for medical images

---

*"Διά των δύο οδών συντομοτέρα η ευθεία" —  "By way of the two roads, the straight one is shorter."*
