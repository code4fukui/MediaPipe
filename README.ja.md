# MediaPipe

MediaPipeは、Google製の機械学習ベースのマルチタスクのパイプラインフレームワークです。このリポジトリでは、MediaPipeのHands解析機能を使用したサンプルコードを提供しています。

## デモ
- [Aizume](https://code4fukui.github.io/Aizume/)

## 機能
- 手の検出と座標の取得
- 手のランドマークの描画
- 手の接続線の描画

## 使い方

```js
import { drawConnectors, drawLandmarks } from "https://code4fukui.github.io/MediaPipe/drawing_utils.js";
import { Hands } from "https://code4fukui.github.io/MediaPipe/Hands.js";
```

## ライセンス
Apache License 2.0