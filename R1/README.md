### R1：Introduction to LLM & RAG
[課程回放連結](https://youtu.be/kS1EbcfDlVE?si=Uyt3iXSDPY22nT6l)


## **參考資料**
- GenAI & LLM 介紹（40 min）
  - [什麼是生成式人工智慧 by 李鴻毅老師 2024 生成式 AI 導論](https://www.youtube.com/watch?v=JGtqpQXfJis)
  - [Introduction to Large Language Models by Google Cloud](https://youtu.be/RBzXsQHjptQ?si=fgLAPoen3revkFoI)
- RAG 介紹（20 min）
   - [What is Retrieval-Augmented Generation by IBM](https://www.youtube.com/watch?v=T-D1OfcDW1M)
   - [為什麼要用 RAG？不用微調模型就能低成本讓 LLM 理解專業知識的 AI 技術](https://tw.alphacamp.co/blog/what-is-rag-ai-technology-and-how-does-retrieval-augmented-generation-work)
- Hugging Face 介紹
  - [🤗 Hugging Face NLP Course（chapter 0 & chapter 1）](https://huggingface.co/learn/nlp-course/chapter0/1?fw=pt)
    - **chapter 0. SETUP**｜如何在 Colab 與自己的裝置上，使用 python 安裝 transformers
    - **chapter 1. TRANSFORMER MODELS**｜了解如何使用 transformers `pipeline` 以及 NLP 常見任務
    - **chapter 2. USING 🤗TRANSFORMERS**｜（Optinoal）作業需要，了解如何使用 transformers
    
- RAG 在保險領域的應用
  - [Retrieval-Augmented Generation in Insurance: Enhancing Accuracy, Efficiency, and Customer Experience](https://ingestai.io/blog/rag-in-insurance#title2)


## **作業：QA 檢索聊天機器人實作**
參考 `R1-Lab-HF-Tutorial.ipynb`</p>
利用 Hugging Face 的 text-generation model 與 Sentence Transformers embedding model 實作 QA 檢索聊天機器人。</p>
基於提供的資料集，使用 Embedding Cosine Similarity 檢索參考資料，再透過 LLM 生成答案。</p>

1. Baseline
   - 將 demo 中的資料，替換成我們提供 or 自己的資料集
   - 能夠檢索相似資料
   - 基於檢索的資料進行回答
2. Advanced（Optional）
   - Embedding 怎麼儲存？每次都要重新計算嗎？
   - 該如何處理太久以前的歷史資料？
   - 利用 Gradio or Hugging Face Spaces 部署、分享 Chatbot


繳交方式：上傳至 Github `./R1/R1-HW.ipynb`