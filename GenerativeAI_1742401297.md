# OracleとNVIDIAの協業によるAgentic AI推論の加速：エンタープライズへの影響

## 1. はじめに

本レポートでは、OracleとNVIDIAが発表した協業内容について、その技術的背景、エンタープライズへの影響、および今後の展望を分析します。具体的には、Oracle Cloud Infrastructure (OCI)とNVIDIA AI Enterpriseソフトウェアプラットフォームの統合、AI Vector Searchの加速、およびNVIDIA Blackwellプラットフォームの導入について詳細に検討します。

## 2. 協業の概要

OracleとNVIDIAは、企業がagentic AIアプリケーション（自律的に行動し、学習するAIアプリケーション）を迅速に開発できるよう支援するため、包括的な協業を発表しました。この協業は、Oracle Cloud Infrastructure (OCI)とNVIDIA AI Enterpriseソフトウェアプラットフォームの統合、Oracle Database 23aiにおけるAI Vector Searchの加速、およびNVIDIA BlackwellプラットフォームのOCIへの導入を主な柱としています。

### 2.1. OCIとNVIDIA AI Enterpriseの統合

OCIとNVIDIA AI Enterpriseの統合により、160以上のAIツールと100以上のNVIDIA NIM™マイクロサービスがOCIコンソールを通じてネイティブに利用可能になります。

* **NVIDIA NIM™マイクロサービス**: NVIDIA NIMは、最適化されたクラウドネイティブな推論マイクロサービスの集合体です。これにより、企業は最新のAIモデル（NVIDIA Llama Nemotronモデルなど）を容易に利用し、agentic AIアプリケーションを構築できます。

### 2.2. AI Vector Searchの加速

OracleとNVIDIAは、Oracle Database 23aiにおけるAI Vector Searchの加速に向けて協業しています。具体的には、NVIDIA cuVSライブラリを活用して、ベクトル埋め込み（テキスト、画像、動画などのデータを数値ベクトルに変換すること）の生成とベクトルインデックスの作成を高速化します。

* **AI Vector Search**: 大量のデータから類似性の高い情報を効率的に検索するための技術です。

### 2.3. NVIDIA Blackwellプラットフォームの導入

OCIは、NVIDIA Blackwellプラットフォームを導入し、AI推論とトレーニングのパフォーマンスを向上させます。OCIは、NVIDIA GB200 NVL72システム（最大131,072個のNVIDIA GPUを搭載可能）の提供を予定しており、NVIDIA Blackwell Ultra GPUを搭載した大規模AIスーパーコンピュータの注文も受け付けています。

## 3. エンタープライズへの影響

この協業は、様々な形でエンタープライズに影響を与えます。

### 3.1. AIアプリケーション開発の加速

OCIとNVIDIA AI Enterpriseの統合により、企業はAIツールやマイクロサービスを容易に利用できるようになり、AIアプリケーションの開発期間を短縮できます。特に、NVIDIA AI Enterpriseは、OCIベアメタルインスタンスおよびKubernetesクラスター向けのデプロイイメージとして提供され、OCIコンソールから直接課金とカスタマーサポートを受けられます。

### 3.2. AI導入の簡素化

OCI AI Blueprintsは、AIワークロードを迅速に実行するためのノーコードデプロイレシピを提供します。これにより、企業はソフトウェアスタックの選択やインフラストラクチャのプロビジョニングに関する意思決定をすることなく、AIプロジェクトを迅速に開始できます。

### 3.3. リアルタイムAI推論の実現

OCI Data Scienceでは、データサイエンティストが事前に最適化されたNVIDIA NIMマイクロサービスに直接アクセスできます。これにより、インフラストラクチャ管理の複雑さを回避し、リアルタイムAI推論を実現できます。

### 3.4. データセキュリティとコンプライアンスの確保

NVIDIA NIMマイクロサービスは、顧客のOCIテナンシー内で実行されるため、データセキュリティとコンプライアンスを維持できます。

### 3.5. AI Vector Searchのパフォーマンス向上

NVIDIA GPUとcuVSライブラリを活用することで、Oracle Database 23aiにおけるAI Vector Searchのパフォーマンスが向上し、高ボリュームのAIベクトルワークロードをサポートできます。

## 4. 事例紹介

本協業を活用している企業の事例を以下に示します。

| 企業名 | 活用内容 

**元記事:** [Oracle and NVIDIA Collaborate to Help Enterprises Accelerate Agentic AI Inference](https://www.oracle.com/news/announcement/oracle-and-nvidia-collaborate-to-help-enterprises-accelerate-agentic-ai-inference-2025-03-18/)