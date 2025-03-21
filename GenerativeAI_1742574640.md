## 生成AIにおけるプライバシーリスク：プロンプトインジェクションの脅威

### 1. はじめに

本レポートは、ScanNetSecurityに掲載された記事「生成 AI の見えないプライバシーリスク」を基に、生成AI（Generative AI）が抱えるプライバシーリスク、特に「プロンプトインジェクション」と呼ばれる攻撃手法に焦点を当て、その脅威と対策について解説する。生成AIの急速な普及に伴い、個人情報保護の観点から注意すべき点について考察する。

### 2. 生成AIとプライバシーリスク

生成AIは、テキスト、画像、音声など様々なコンテンツを生成できる強力な技術である。しかし、その利用にはプライバシーリスクが伴う。記事では、個人情報（PII：Personally Identifiable Information）の漏洩リスクが特に重要視されている。

### 3. プロンプトインジェクションとは

プロンプトインジェクションとは、生成AIに対して意図的に不正な指示（プロンプト）を与えることで、本来アクセスできない情報や機能を不正に利用する攻撃手法である。

#### 3.1. プロンプトインジェクションの仕組み

生成AIは、ユーザーからの指示（プロンプト）に基づいて応答を生成する。プロンプトインジェクションでは、このプロンプトに悪意のある命令を埋め込むことで、AIの振る舞いを制御し、機密情報の取得や不正な操作を試みる。

#### 3.2. プロンプトインジェクションの具体例

記事で紹介されている「おばあちゃんエクスプロイト」は、プロンプトインジェクションの典型的な例である。

| プロンプト 

**元記事:** [生成 AI の見えないプライバシーリスク ScanNetSecurity](https://s.netsecurity.ne.jp/article/2025/03/21/52535.html)