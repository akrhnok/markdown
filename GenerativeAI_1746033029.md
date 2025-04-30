## 3Dで思い通りの画像を生成！NVIDIAが「3D-Guided Generative AI」のAI Blueprintを公開

### 主要ポイント

* 3Dシーンを基に、思い通りの画像を生成できるAI Blueprintが登場
* Blenderで3Dシーンを作成し、それを元に画像生成AIが画像を生成
* NVIDIA NIMマイクロサービスにより、GeForce RTX GPUで高速動作
* ComfyUIとBlenderプラグインにより、柔軟なワークフローを実現

### 詳細解説

NVIDIAは、3Dシーンを基に画像生成を行うためのAI Blueprintを公開しました。このBlueprintは、クリエイターがより詳細な構図やカメラアングルを制御し、思い通りの画像を生成することを可能にします。従来のテキストプロンプトだけでは難しかった、細かな調整やオブジェクトの配置を、3D空間で直感的に行うことができるようになります。

このBlueprintの核となるのは、Black Forest LabsのFLUX.1-devという画像生成モデルです。Blenderで作成した3Dシーンから生成された深度マップをFLUX.1-devに渡し、ユーザーのプロンプトと組み合わせて画像を生成します。深度マップは、オブジェクトの配置や遠近感をAIに指示する役割を果たします。これにより、複雑なテキストプロンプトを使わずに、よりクリエイティブな表現が可能になります。

さらに、このBlueprintは、ComfyUIという強力なツールを基盤としています。ComfyUIは、複数の生成AIモデルを連携させるための柔軟なワークフローを提供します。Blenderプラグインを使用することで、BlenderとComfyUIを直接接続し、3Dシーンの変更をリアルタイムに画像生成に反映させることができます。また、NVIDIA NIMマイクロサービスにより、FLUX.1-devモデルをGeForce RTX GPU上で最適化されたパフォーマンスで実行できます。TensorRT SDKやFP4/FP8といった最適化技術を活用し、高速な画像生成を実現します。

| 特徴 | 詳細 

**元記事:** [AI Blueprint for 3D-Guided Generative AI is Out Now NVIDIA Blog](https://blogs.nvidia.com/blog/rtx-ai-garage-3d-guided-generative-ai-blueprint/)