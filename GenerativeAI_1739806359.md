# RAG AI: 自分で作るべき理由とその利点

## はじめに

近年、AI技術は急速に進化しており、特に**Retrieval-Augmented Generation (RAG)**という手法が注目されています。RAGは、大規模言語モデル（LLM）に外部の信頼性の高い情報源を活用することで、より正確で最新の情報を提供することを目的としています。本レポートでは、RAGの基本概念、利点、そしてニューヨーク市議会のデータサイエンティストによる「自分で作るべき理由」を分析します。

## RAGの基本概念

RAGは、LLMに外部のデータベースや文書から情報を取得し、それを基に回答を生成する手法です。これにより、LLMが単に学習データに頼るのではなく、最新の情報を活用してより正確な回答を提供できます[1][3]。

### RAGのプロセス

1. **外部データの作成**: 外部のデータソースから情報を取得し、ベクトル形式に変換します。
2. **関連情報の取得**: ユーザーのクエリをベクトル化し、関連する情報を検索します。
3. **LLMのプロンプトの強化**: 取得した情報をプロンプトに追加し、LLMがより正確な回答を生成できるようにします[1][3]。

## RAGの利点

- **正確性の向上**: RAGは、外部の信頼性の高い情報源を活用することで、LLMの回答の正確性を向上させます。
- **最新情報の提供**: 外部データを活用することで、最新の情報を提供できます。
- **コスト効率**: モデルの再訓練を必要とせず、既存のLLMを効率的に活用できます[1][3]。

## ニューヨーク市議会の取り組み

ニューヨーク市議会のデータサイエンティスト、Alaa Moussawi氏は、組織が自分でAIを開発することの重要性を強調しています。彼は、オープンソースのモデルを活用し、RAGを用いてより効率的なAIアプリケーションを構築することを推奨しています[4]。

### 自分で作るべき理由

- **セキュリティ**: クラウドベースのサービスではなく、自社で管理することでセキュリティリスクを軽減できます。
- **コスト削減**: オープンソースモデルを利用することで、開発コストを抑えることができます。
- **柔軟性**: 自社で開発することで、特定のニーズに応じたカスタマイズが可能です[4]。

## 結論

RAGは、LLMの限界を補うことで、より正確で最新の情報を提供する強力な手法です。ニューヨーク市議会の取り組みは、組織が自分でAIを開発することの利点を示しています。RAGを活用することで、組織はより効率的かつ信頼性の高いAIソリューションを構築できるでしょう。

#### 参照記事
- [1:https://aws.amazon.com/what-is/retrieval-augmented-generation/](https://aws.amazon.com/what-is/retrieval-augmented-generation/)
- [2:https://www.datasciencecentral.com](https://www.datasciencecentral.com)
- [3:https://www.superannotate.com/blog/rag-explained](https://www.superannotate.com/blog/rag-explained)
- [4:https://www.computerweekly.com](https://www.computerweekly.com)
- [5:https://cloud.google.com/use-cases/retrieval-augmented-generation](https://cloud.google.com/use-cases/retrieval-augmented-generation)


**元記事:** [RAG AI ‘Do it yourself,’ says NYC data scientist Computer Weekly](https://www.computerweekly.com/feature/RAG-AI-Do-it-yourself-says-NYC-data-scientist)