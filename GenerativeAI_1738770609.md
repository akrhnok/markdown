## SambaNova CloudにおけるTülu 3 405Bモデルの導入とその意義

### 1. はじめに

本レポートでは、SambaNova Systemsが提供するSambaNova Cloudに新たに導入された大規模言語モデル「Tülu 3 405B」について、その概要、性能、および意義を客観的に分析する。Tülu 3 405Bは、Allen Institute for AI (Ai2)によって開発されたオープンソースモデルであり、SambaNova Cloud上でDeepSeek V3を上回る性能を示すことが報告されている。

### 2. SambaNova CloudとRDUアーキテクチャ

SambaNova Cloudは、企業が最先端のAIおよび深層学習機能を迅速に展開するためのプラットフォームである。特に、SambaNovaが開発したRDU（Reconfigurable Dataflow Unit）アーキテクチャは、GPUの代替として、要求の厳しい生成AIおよびエージェントAIワークロードを処理するために設計されている。RDUは、AIに特化したプロセッサであり、高い計算能力と効率的なデータ処理を実現する。

### 3. Tülu 3 405Bモデルの概要

Tülu 3 405Bは、4050億のパラメータを持つ大規模言語モデルであり、Llama 3を基にファインチューニングされている。このモデルは、以下の点で優れた性能を示す。

*   **PopQA:** Wikipediaから収集された14,000の専門知識に関する質問において、DeepSeek V3やGPT-4oを上回る性能を発揮。
*   **MMLU:** 多様なタスクにおける言語理解能力を測るベンチマークで86.6のスコアを達成。
*   **GSM8K:** 数学の文章題において、同クラスの他のモデルを凌駕。

これらの結果は、Tülu 3 405Bが、知識の理解、言語の推論、および問題解決において高い能力を持つことを示唆している。

### 4. Tüluシリーズの進化と特徴

Tüluシリーズは、Ai2によって開発されたオープンソースのAIモデルであり、初期のバージョンからデータ収集と教師ありファインチューニングに重点を置いて開発されてきた。Direct Preference Optimization (DPO)やProximal Policy Optimization (PPO)などの革新的な技術を採用し、商用AIシステムに匹敵する性能を実現している。Tülu 3は、命令追従、コーディング、数学的推論、および多言語対応を含むコアスキルを強化するための洗練された5部構成のポストトレーニングレシピを備えた包括的なオープンソースフレームワークを提供する。

### 5. SambaNova CloudにおけるTülu 3 405Bの利用

SambaNova Cloudの利用者は、APIを通じてTülu 3 405Bにアクセスできる。また、Hugging Faceなどのパートナーを通じて、SambaNova Cloudの推論APIを利用することも可能である。SambaNova Cloudは、高速な推論速度を提供し、AIエージェントやチャットボットなどのリアルタイムアプリケーションの構築を支援する。

### 6. SambaNova Cloudの利点

SambaNova Cloudは、以下の利点を提供する。

*   **高速な推論速度:** SambaNovaのSN40L AIチップにより、GPUと比較して最大10倍高速な推論速度を実現。
*   **オープンソースモデルの統合:** Llama 3 405Bなどの最新かつ最高のオープンソースモデルを容易に統合可能。
*   **開発者向けのリソース:** 開発者コミュニティ、スターターキット、技術ドキュメントなどのリソースを提供し、AI開発を支援。

### 7. まとめ

SambaNova Cloudに導入されたTülu 3 405Bは、高性能なオープンソースモデルであり、AI研究者や開発者にとって強力なツールとなる。SambaNova Cloudの高速な推論速度と豊富なリソースを活用することで、AIアプリケーションの開発を加速し、新たなビジネス価値を創出することが期待される。

**元記事:** [On SambaNova Cloud, Tülu 3 405B, A New Model Better than DeepSeek V3](https://sambanova.ai/blog/sambanova-cloud-tulu-3-405b-a-new-model-better-than-deepseek-v3)