# busho-index
## 1. TextChunking_RegisterIndex.ipynb
### 日本語データセットをチャンク分割し Azure Cognitive Search のインデックスに登録するサンプル

Azure Cognitive Search のキーワード検索をするために以下を行うサンプルです。

- 戦国武将の Wikipedia ページをチャンクに分割
- Azure Cognitive Search のインデックスに登録

## 2. TextChunking_Embeddings_RegisterIndex.ipynb
### 日本語データセットをチャンク分割し、Embeddings に変換して Azure Cognitive Search のベクトルインデックスに登録するサンプル

Azure Cognitive Search のベクトル検索を行うために、以下を行うサンプルです。

- 戦国武将の Wikipedia ページをチャンクに分割
- チャンクごとに Embeddings を生成
- Azure Cognitive Search のベクトルインデックスに登録
