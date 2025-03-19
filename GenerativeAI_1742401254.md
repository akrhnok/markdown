## Azure AI Foundry、NVIDIA NIM、NVIDIA AgentIQによるエージェントワークフローの加速：詳細レポート

### 1. はじめに

本レポートでは、Microsoft Azure Blogに掲載された記事「Accelerating agentic workflows with Azure AI Foundry, NVIDIA NIM, and NVIDIA AgentIQ」の内容を基に、Azure AI FoundryにおけるNVIDIA NIMマイクロサービスとNVIDIA AgentIQツールキットの統合がもたらす影響について分析します。本記事は、AIプロジェクトの効率化、性能向上、コスト最適化を目的としたものであり、特にエージェント型AIワークフローの加速に焦点を当てています。

### 2. Azure AI FoundryとNVIDIAの連携：概要

MicrosoftとNVIDIAの協業により、Azure AI FoundryにNVIDIA NIMマイクロサービスとNVIDIA AgentIQツールキットが統合されました。この統合は、AI開発ライフサイクルの各段階を簡素化し、迅速な市場投入と高性能なAIアプリケーションの実現を目指しています。

### 3. NVIDIA NIMマイクロサービスの詳細

NVIDIA NIM（NVIDIA AI Enterpriseソフトウェアスイートの一部）は、安全で信頼性の高い高性能なAI推論を実現するためのマイクロサービスの集合体です。

* **主な特徴:**
 * **ゼロコンフィギュレーションデプロイ:** 事前最適化された状態で、すぐに利用可能。
 * **Azureとのシームレスな統合:** Azure AI Agent ServiceやSemantic Kernelとの連携。
 * **エンタープライズグレードの信頼性:** NVIDIA AI Enterpriseによる継続的なパフォーマンスとセキュリティサポート。
 * **スケーラブルな推論:** AzureのNVIDIAアクセラレーテッドインフラストラクチャを活用。
 * **最適化されたワークフロー:** 大規模言語モデルから高度な分析まで、幅広いアプリケーションを加速。

* **デプロイ方法:** Azure AI FoundryのモデルカタログからLlama-3.3-70B-NIMなどのモデルを選択し、数クリックでAIワークフローに統合できます。

### 4. NVIDIA AgentIQツールキットによるパフォーマンス最適化

NVIDIA AgentIQは、AIエージェントの接続、プロファイリング、最適化を目的としたオープンソースツールキットです。

* **主な機能:**
 * **プロファイリングと最適化:** リアルタイムのテレメトリを活用し、AIエージェントの配置を調整して、レイテンシと計算オーバーヘッドを削減。
 * **動的な推論の強化:** 予測される出力トークン数、次の推論までの推定時間、および予想されるトークン長などのメタデータを継続的に収集・分析し、エージェントのパフォーマンスを動的に改善。
 * **Semantic Kernelとの統合:** Azure AI Foundry Agent Serviceとの直接統合により、エージェントのセマンティック推論とタスク実行能力を強化。

### 5. NVIDIA Llama Nemotron Reasonの統合

NVIDIAは、高度な推論能力を持つAIモデルファミリーであるNVIDIA Llama Nemotron Reasonの統合を予定しています。Nemotronは、コーディング、複雑な数学、科学的推論に優れており、ユーザーの意図を理解し、検索や翻訳などのツールをシームレスに呼び出すことができます。

### 6. 導入事例

* **Epic:** クラウドと分析担当副社長Drew McCombs氏は、NVIDIA NIMマイクロサービスの導入により、患者ケアの向上、臨床医と業務効率の向上、および医療イノベーションの促進に貢献できると述べています。
* **ServiceNow:** プラットフォームとAI担当EVP Jon Sigler氏は、ServiceNowのAIプラットフォームとNVIDIA NIM、Microsoft Azure AI Foundry、Azure AI Agent Serviceの組み合わせにより、業界固有のAIエージェントを市場に投入し、問題解決の迅速化、優れた顧客体験の提供、組織の生産性と効率の向上に貢献できると述べています。

### 7. まとめ：Azure AI Foundryの利点

Azure AI Foundryは、NVIDIA NIMとAgentIQの組み合わせにより、エンタープライズグレードのエージェントアプリケーションを構築、デプロイ、スケーリングするためのターンキーソリューションを提供します。

* **主な利点:**
 * AIデプロイメントの加速
 * エージェントワークフローの強化
 * インフラストラクチャコストの削減
 * イノベーションへの集中

### 8. 結論

Azure AI Foundry、NVIDIA NIM、およびNVIDIA AgentIQの統合は、AIエージェントワークフローの効率化と最適化を促進し、企業がAIを活用したイノベーションを加速するための強力な基盤を提供します。この統合により、AIプロジェクトの迅速な開発と展開、コスト削減、およびパフォーマンス向上が期待できます。



**元記事:** [Accelerating agentic workflows with Azure AI Foundry, NVIDIA NIM, and NVIDIA AgentIQ Microsoft Azure Blog](https://azure.microsoft.com/en-us/blog/accelerating-agentic-workflows-with-azure-ai-foundry-nvidia-nim-and-nvidia-agentiq/)