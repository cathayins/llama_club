# Round 2：Prompt Engineering
[讀書會回放連結](https://youtu.be/JrjufPdeQuM)


## **目標**
- 介紹 Prompt Engineering 以及優化方式

## **參考資料**
- **李宏毅老師介紹**
  - [【生成式AI導論 2024】第3講：訓練不了人工智慧？你可以訓練你自己 (上) — 神奇咒語與提供更多資訊](https://www.youtube.com/watch?v=A3Yx35KrSN0)
  - [【生成式AI導論 2024】第4講：訓練不了人工智慧？你可以訓練你自己 (中) — 拆解問題與使用工具](https://www.youtube.com/watch?v=lwe3_x50_uw)
  - [【生成式AI導論 2024】第5講：訓練不了人工智慧？你可以訓練你自己 (下) — 讓語言彼此合作，把一個人活成一個團隊 (開頭有芙莉蓮雷，慎入)](https://www.youtube.com/watch?v=inebiWdQW-4)
- **提示詞技巧總覽**
  - [Prompt Engineering Guide](https://www.promptingguide.ai/zh/introduction)
- **ChatGPT 提示詞技巧**
  - [ChatGPT Prompt Engineering for Developers](https://learn.deeplearning.ai/courses/chatgpt-prompt-eng/lesson/1/introduction)

## **作業：資訊擷取實作**
參考 `R2-Langchain-Tutorial.ipynb`</p>
利用 Langchain 的 LLMs, Prompt 透過 LCEL 實作資訊擷取機器人。</p>

1. Baseline
   - 從新聞描述中擷取出相關資訊
   - 以 JSON 格式回傳，並轉為 Python Dict
2. Advanced（Optional）
   - 如何將多個 LLMChain 進行串接，將多個 LLM 透過流程化的方式結合

繳交方式：上傳至 Github `./R2/R2-HW.ipynb`