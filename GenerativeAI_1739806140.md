# USBスティックに隠された大規模言語モデル

## 概要

本レポートでは、USBスティックに大規模言語モデル（LLM）を搭載したプロジェクトについて、技術的背景とその実現方法を解説します。LLMは、自然言語処理で重要な役割を果たしており、通常は大量の計算リソースを必要とします。しかし、このプロジェクトでは、Raspberry Pi Zero Wを利用して、非常に小型で持ち運び可能なLLMを実現しました。

## 大規模言語モデルの背景

### LLMの特徴

- **大規模言語モデル（LLM）**: GPTやLLaMAなどのモデルは、数十億から数百億のパラメータを使用し、優れたテキスト生成能力を発揮します。これらのモデルは通常、多大な計算リソースを必要とします。
- **小型化の挑戦**: これらのモデルを小型のデバイスで動作させることは、計算リソースの制約から困難です。

### 小型デバイスでのLLM実現

- **Raspberry Pi Zero W**: このプロジェクトでは、Raspberry Pi Zero Wを利用してLLMを実現しました。Zero Wは非常に小型で、Wi-Fi接続も可能なため、持ち運びに便利です。
- **llama.cpp**: LLaMAの軽量版である`llama.cpp`を使用し、ARMv6命令セットに対応させるためにソースコードを修正しました。これにより、ARMv6で動作するPi Zero WでもLLMを動作させることができました。

## 実現方法

### ハードウェア構成

- **3Dプリンタ製ケース**: USBスティックの形状に合わせたカスタムケースを3Dプリンタで作成しました。
- **Raspberry Pi Zero W**: カスタムケース内にRaspberry Pi Zero Wを搭載し、`llama.cpp`を実行します。

### ソフトウェア構成

- **ファイルシステムとしての接続**: USBデバイスを複合デバイスとして設定し、ホストコンピュータにファイルシステムとして接続します。ユーザーは空のテキストファイルを作成するだけで、LLMが自動的にテキストを生成します。

## 意義と将来展望

- **小型化と持ち運び性**: このプロジェクトは、LLMを非常に小型で持ち運び可能な形態で実現しました。これにより、さまざまな場所でAI技術を活用できる可能性が広がります。
- **将来の応用**: 小型デバイスでのLLMの実現は、スマート家電や車載システムなど、インタラクティブなデバイスの開発に寄与する可能性があります。

## 結論

このプロジェクトは、技術的課題を克服し、LLMを小型で持ち運び可能な形態で実現しました。将来的には、より多様なデバイスやアプリケーションでAI技術が活用されることが期待されます。

#### 参照記事
- [1:https://hackaday.com/2025/02/17/usb-stick-hides-large-language-model/](https://hackaday.com/2025/02/17/usb-stick-hides-large-language-model/)
- [2:https://wiert.me/archives/](https://wiert.me/archives/)
- [3:https://aclanthology.org/2024.acl-long.678/](https://aclanthology.org/2024.acl-long.678/)
- [4:https://hackaday.io/project/46-hackadayio-project](https://hackaday.io/project/46-hackadayio-project)
- [5:https://machinelearning.apple.com/research/efficient-large-language](https://machinelearning.apple.com/research/efficient-large-language)


**元記事:** [USB Stick Hides Large Language Model Hackaday](https://hackaday.com/2025/02/17/usb-stick-hides-large-language-model/)