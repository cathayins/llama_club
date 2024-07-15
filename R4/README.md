# Round 4：模型的高效服務和量化

[讀書會回放連結](https://youtu.be/Ia239rEoU1o?si=aP41fDc_dQiAZs35)

## 目標
- 掌握讓模型高效服務的技巧

## 知識點
- Vector database 介紹與基本操作
- 介紹量化壓縮的概念與優缺點
- 模型量化壓縮實作

## 參考資料
- [开源免费的向量数据库 Vector Database - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/667534584)
- [LLM Note Day 14 - 量化 Quantization - iT 邦幫忙](https://ithelp.ithome.com.tw/articles/10330372)
- [量化感知训练（Quantization-aware-training）探索-从原理到实践 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/548174416)
- [闲话模型压缩之量化（Quantization）篇_sigmoid量化 对精度影响大吗-CSDN博客](https://blog.csdn.net/jinzhuojun/article/details/106955059)
- [BERT 瘦身之路：Distillation，Quantization，Pruning - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/86900556)
- [QLoRA: 4bit量化+LoRA训练=瞬间起飞 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/634256206)

## 程式碼範例
- R4-Langchain_Tutorial.ipynb

## 作業
- 目標
    1. 請嘗試將下方語料庫中的文本透過量化技術轉為 embedding，並放入資料庫
    2. 檢索與 "怎麼提升模型效度" 最相關的10個文本以及相似度的分數(距離)
- 繳交方式：上傳至 Github `./R4/R4-HW.ipynb`