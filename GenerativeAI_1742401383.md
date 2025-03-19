# OracleとNVIDIAの協業による企業向けエージェントAI推論加速：レポート

## 1. はじめに

本レポートは、2025年3月18日に発表されたOracleとNVIDIAの協業に関するニュース記事を基に、その内容を客観的に分析し、企業におけるAI活用の加速に焦点を当ててまとめたものである。本協業は、Oracle Cloud Infrastructure (OCI)とNVIDIA AI Enterpriseソフトウェアプラットフォームの統合を通じて、エージェントAIアプリケーションの開発を支援することを目的としている。

## 2. 協業の概要

OracleとNVIDIAは、企業がエージェントAIアプリケーションを迅速かつ容易に構築できるよう、両社の技術を統合した。

* **統合内容**:
 * OCIとNVIDIA AI Enterpriseの統合
 * Oracle Database 23aiにおけるAIベクトル検索の加速
* **目的**: 企業におけるAI導入の加速、データからの価値創出の支援

## 3. 具体的な技術的連携

### 3.1. OCIとNVIDIA AI Enterpriseの統合

OCIコンソールを通じて、160以上のAIツールと100以上のNVIDIA NIM™マイクロサービスがネイティブに利用可能になる。

* **NVIDIA NIM (NVIDIA Inference Microservices)**: 最適化されたクラウドネイティブな推論マイクロサービス。
 * 最新のNVIDIA Llama Nemotronモデルを含む、主要なAIモデルに対応。
* **展開方法**: OCIベアメタルインスタンスおよびOCI Kubernetes Engineを利用したKubernetesクラスタ向けのデプロイメントイメージとして提供。
* **利点**: Oracleを通じた直接的な課金とカスタマーサポート。

### 3.2. AI Blueprintsの活用

OracleとNVIDIAは、AI Blueprintsと呼ばれる、コードを記述せずにAIワークロードを実行できるテンプレートの共同開発に取り組んでいる。

* **OCI AI Blueprints**:
 * ハードウェアの推奨事項（NVIDIA GPUなど）
 * NIMマイクロサービス
 * 事前設定された可観測性ツール
* **NVIDIA Blueprints**:
 * NVIDIAスタック全体で統一された開発体験を提供
 * 企業向けAIユースケースのリファレンスワークフローを提供
* **活用例**: カスタマーサービスAIアシスタントなど、カスタムAIアプリケーションの開発

### 3.3. Oracle Database 23aiにおけるAIベクトル検索の加速

NVIDIA GPUとNVIDIA cuVSライブラリを活用し、Oracle Database 23aiにおけるAIベクトル検索の性能を向上させる。

* **AIベクトル検索**: テキスト、画像、動画などの大量の入力データをベクトル化し、インデックスを作成する技術。
* **効果**: AIパイプラインの性能向上、高ボリュームのAIベクトルワークロードのサポート。

### 3.4. OCI Data ScienceにおけるNVIDIA NIMマイクロサービスの利用

データサイエンティストは、OCI Data Science内で事前最適化されたNVIDIA NIMマイクロサービスに直接アクセスできる。

* **利点**: インフラストラクチャ管理の複雑さを軽減し、リアルタイムAI推論ユースケースをサポート。
* **セキュリティ**: モデルは顧客のOCIテナンシ内で実行され、データセキュリティとコンプライアンスを維持。
* **料金体系**: 従量課金制またはOracle Universal Creditsの利用が可能。

## 4. 導入事例

* **Soley Therapeutics**: OCI AI Infrastructure、NVIDIA AI Enterprise、NVIDIA Blackwell GPUを活用し、AI創薬プラットフォームを構築。
* **Pipefy**: OCI AI Blueprintsを活用し、NVIDIA GPUノードを起動し、マルチモーダル大規模言語モデルを迅速にデプロイ。
* **DeweyVision**: Oracle Database 23aiとNVIDIA GPUを活用し、メディアをデータ化するAIツールを開発。
* **SoundHound AI**: OCI上で音声AIプラットフォームを運用し、NVIDIA GPUを活用して次世代音声AIのトレーニングを加速。

## 5. NVIDIA BlackwellとOCI

OCIは、NVIDIA Blackwellアーキテクチャに基づく最新のGPUを提供予定。

* **NVIDIA Blackwell Ultra GPU**: NVIDIA GB300 NVL72システムおよびNVIDIA HGX™ B300 NVL16システムを含む。
* **効果**: AI性能の向上、AIファクトリーにおける収益機会の拡大。

## 6. まとめ

OracleとNVIDIAの協業は、企業がAIを活用し、ビジネス成果を向上させるための包括的なソリューションを提供する。OCIとNVIDIA AI Enterpriseの統合、AI Blueprintsの活用、Oracle Database 23aiにおけるAIベクトル検索の加速、NVIDIA NIMマイクロサービスの提供、そして最新のNVIDIA Blackwell GPUの導入は、企業がAIを迅速かつ効率的に導入し、データから価値を引き出すことを支援する。

## 7. 今後の展望

本協業は、AI技術の進化と企業のニーズに合わせて、今後も継続的に発展していくことが期待される。特に、NVIDIA Blackwell GPUの導入は、AIワークロードの性能向上に大きく貢献し、より高度なAIアプリケーションの開発を促進するだろう。



**元記事:** [Oracle and NVIDIA Collaborate to Help Enterprises Accelerate Agentic AI Inference NVIDIA Newsroom](https://nvidianews.nvidia.com/news/oracle-and-nvidia-collaborate-to-help-enterprises-accelerate-agentic-ai-inference)