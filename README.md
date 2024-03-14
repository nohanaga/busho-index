# busho-index
## 1. [TextChunking_RegisterIndex.ipynb](TextChunking_RegisterIndex.ipynb)
日本語データセットをチャンク分割し Azure AI Search のインデックスに登録するサンプル

Azure AI Search のキーワード検索をするために以下を行うサンプルです。

- 戦国武将の Wikipedia ページをチャンクに分割
- Azure AI Search のインデックスに登録

## 2. [TextChunking_Embeddings_RegisterIndex.ipynb](TextChunking_Embeddings_RegisterIndex.ipynb)
日本語データセットをチャンク分割し、Embeddings に変換して Azure AI Search のベクトルインデックスに登録するサンプル

## 3. [KeywordVectorHybridSemanticSearch.ipynb](KeywordVectorHybridSemanticSearch.ipynb)
フルテキスト検索、ベクトル検索、ハイブリッド検索、セマンティックハイブリッド検索を行うサンプル

Azure AI Search の様々な検索を行うために、以下を行うサンプルです。

- 戦国武将の Wikipedia ページをチャンクに分割
- チャンクごとに Embeddings を生成
- Azure AI Search のベクトルインデックスに登録
- 検索クエリーを発行

## 4. [Semantic_Chunker.ipynb](Semantic_Chunker.ipynb)
Azure AI Document Intelligence と LangChain を使用してセマンティックチャンキングを行うサンプル

## 5. [Corrective RAG (CRAG)](crag_azure_ai_search_bing.ipynb)
Corrective RAG (CRAG) のサンプル