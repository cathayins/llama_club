# Round 3：Semantic Search

[讀書會回放連結](https://youtu.be/ifIjFd0Pgz4)

## **目標**
- 如何把文本轉向量後(含文本切分方式)，存放至向量資料庫，並計算文本之間的相似度


## **參考資料**
- **Embedding 介紹**
  - [Embedding和向量資料庫系列（1）Embedding是什麼?](https://tako-analytics.com/2023-09-28-data-science-embedding-and-vector-database-series-1-what-is-embedding/)
  - [Embedding和向量資料庫系列（2）Embedding實作與相似度計算](https://tako-analytics.com/2023-09-28-data-science-embedding-and-vector-database-series-2-implementation-of-embedding-and-similarity-computation/)
  - [Chinese Embedding model Ranking](https://huggingface.co/spaces/mteb/leaderboard)
  
- **Chunking 技巧**
  - [LM 大语言模型应用的分段策略](https://xie.infoq.cn/article/215f8e34ffad1aa709d564802)
  - [最详细的文本分块(Chunking)方法，直接影响LLM应用效果](https://luxiangdong.com/2023/09/20/chunk/)
  
- **Retrieval**
  - [LangChain 怎麼玩？ Retrieval 篇，來做個聊天機器人(ChatBot)吧](https://myapollo.com.tw/blog/langchain-tutorial-retrieval/)
  - [Large Language Models with Semantic Search - Dense Retrieval](https://hackmd.io/@YungHuiHsu/Sk-hxS0-T)

## **程式碼範例**
- [LangChain Chat with Your Data (1~5章)](https://learn.deeplearning.ai/courses/langchain-chat-with-your-data/lesson/1/introduction)

## **作業：資訊擷取實作**
參考 `R3-Langchain-Tutorial.ipynb`</p>
利用 Langchain 的 document_loaders, embeddings, vectorstores 等實作簡單的 RAG。</p>

1. Baseline
   - 將第一次作業的 QA 檢索聊天機器人，重新透過 LangChain 進行實作
2. Advance
   - 測試不同的 Chunk 大小，對於答案生成的影響

繳交方式：上傳至 Github `./R3/R3-HW.ipynb`