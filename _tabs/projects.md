---
# the default layout is 'page'
icon: fas fa-laptop-code
order: 3
---

# 🚀 Featured Projects

---

### 🏦 Finance RAG Chatbot
> **Description:** A Retrieval-Augmented Generation (RAG) chatbot designed to retrieve and summarize information from complex financial terms and conditions (PDF).

* **Key Features:**
    * **Semantic Chunking:** Implemented custom text splitting based on financial clauses (Articles/Chapters) to maintain document structure using regex.
    * **Advanced Reranking:** Applied **MMR (Maximal Marginal Relevance)** and LLM-based scoring (Upstage Solar Pro 2) to enhance retrieval accuracy and reduce redundancy.
    * **User Interface:** Developed an interactive web interface using **Streamlit** for seamless PDF uploads and real-time Q&A.
* **Tech Stack:** Python 3.12, LangChain, Upstage Solar API, ChromaDB, Streamlit
* **Link:** [View on GitHub](https://github.com/jinhee-ai-kim/finance-rag-chatbot)


---
### 📊 Explainable Credit Default Prediction (XAI)
> **Description:** A comparative study on credit card default prediction using SHAP and DiCE to achieve both model interpretability and actionable counterfactual insights.

* **Key Features:**
    * **Dual XAI Approach:** Leveraged **SHAP** for feature attribution (Logistic Regression) and **DiCE** for counterfactual explanations (XGBoost).
    * **Model Comparison:** Analyzed linear vs. non-linear decision boundaries to evaluate how different models interpret financial risk.
    * **Counterfactual Analysis:** Generated "what-if" scenarios to identify minimal feature changes required to flip a prediction from 'Default' to 'Non-default'.
* **Tech Stack:** Python, Scikit-learn, XGBoost, SHAP, DiCE, Pandas
* **Link:** [View on GitHub](https://github.com/jinhee-ai-kim/credit-default-xai)


<!-- --- -->


<!-- ### 🏥 Indoor Amenity Detection
> **Description:** Object detection project using Faster R-CNN to identify indoor amenities.
* **Tech Stack:** Python, PyTorch, Faster R-CNN
* **Link:** [View on GitHub](https://github.com/your-id/project-repo) -->
