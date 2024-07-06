# Round 5：RAG的優化策略

## 目標
- 串接整個 RAG 的流程
- 掌握 RAG 的優化方式

## 知識點
- 實作整個 RAG 的流程
- 哪些因素會影響到 RAG 的效度
- RAG 效果不好的幾個原因及優化策略

## 參考資料
- [RAG (Retrieval Augmented Generation) | 甚麼是 RAG | RAG 教學 | Medium](https://medium.com/@cch.chichieh/rag-retrieval-augmented-generation-%E7%82%BA%E8%87%AA%E7%84%B6%E8%AA%9E%E8%A8%80%E8%99%95%E7%90%86%E6%8F%AD%E9%96%8B%E6%96%B0%E7%AF%87%E7%AB%A0-fced76fdb8b9)
- [读懂RAG这一篇就够了，万字详述RAG的5步流程和12个优化策略](https://zhuanlan.zhihu.com/p/680574405)
- [大模型检索增强生成（RAG）有哪些好用的技巧？](https://www.zhihu.com/question/625481187/answer/3309968693)
- [RAG系统的“七宗罪”--一周出demo，半年用不好](https://zhuanlan.zhihu.com/p/677691070)
- [在大模型应用中，如何提升RAG（检索增强生成）的能力？](https://www.zhihu.com/question/643138720/answer/3495870046)

## 程式碼範例
- R5-Langchain_Tutorial.ipynb

## 作業
- 任務
    1. 載入文本模型，直接跟 LLM 進行QA
    2. 參考 Tutorial 的內容，讓 LLM 根據 小組語料庫 的內容進行回答
    2. 分別嘗試 chunk, prompt, 召回數量, 召回方式, rerank 等RAG 的優化策略，嘗試提升 RAG 的效度
- 繳交方式：上傳至 Github `./R5/R5-HW.ipynb`