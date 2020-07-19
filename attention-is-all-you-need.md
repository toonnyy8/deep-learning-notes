# [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

## 簡介
在 2017 年，由 self attention 構成的新模型 Transformer 被提出。

#### 優點：
* **快速**：跟 RNN 類的模型相比，可將輸入序列做平行運算。
* **長距離關注**：跟 CNN 類的模型相比，可依據輸入序列長度動態改變感受野。

#### 缺點：
* **記憶體使用量過大**，受硬體設備限制了其關注距離。

## 架構
