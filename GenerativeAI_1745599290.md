# AIが生成するコードの脆弱性に関する調査レポート：Backslash Securityの発表

## 1. はじめに

本レポートは、AIセキュリティ企業であるBackslash Securityが発表した、大規模言語モデル（LLM）が生成するコードの脆弱性に関する調査結果をまとめたものです。近年、AIによるコード生成技術が普及する中で、生成されるコードのセキュリティリスクが課題となっています。本レポートでは、Backslash Securityの調査内容を詳細に分析し、その対策について考察します。

## 2. 調査概要

Backslash Securityは、OpenAIのGPT、AnthropicのClaude、GoogleのGeminiなど、7種類の最新LLMを対象に、生成されるコードのセキュリティを評価しました。評価は、プロンプト（指示）の与え方を変えることで行われました。具体的には、以下の3段階のプロンプトが使用されました。

* **単純な指示（Naive prompts）：** セキュリティに関する特別な指示を含まないプロンプト。
* **セキュリティを意識した指示：** セキュリティ要件を明示的に含めたプロンプト。
* **OWASPのベストプラクティスに基づいた指示：** OWASP（Open Web Application Security Project）のベストプラクティスに沿ったプロンプト。

調査では、生成されたコードに存在する脆弱性（CWE：Common Weakness Enumeration）の数を評価しました。

## 3. 調査結果

### 3.1. プロンプトと脆弱性の関係

調査の結果、プロンプトの与え方によって、生成されるコードのセキュリティレベルが大きく異なることが明らかになりました。

| プロンプトの種類 | 結果 

**元記事:** [AIセキュリティのBackslash Security、GPT-4.1など人気LLMが生成するコードの脆弱性を指摘](https://www.atpartners.co.jp/news/2025-04-25-ai-security-s-backslash-security-points-out-vulnerabilities-in-gpt-4-1-and-other-popular-llm-generated-code)