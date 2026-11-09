# 07. Instant 8K — アップスケール用「Nano Banana Prompt」

- 投稿者: Rose @rosedoesai（Instagram リール）
- 投稿: https://www.instagram.com/reel/DerCO1NOUFd/ （2026-10-19）
- 共有リンク: https://www.instagram.com/reel/DerCO1NOUFd/?srtk=aXllNmM1ODdlMGs=

## 要約

AI ポートレートを 8K 級にアップスケールするプロンプトのデモ動画。左右スプリット（ワイプ）比較で、低精細版と 8K 版を見せながら、効く要素を画面テキストで提示する。

- 唇の質感（lip texture）
- 肌の質感（realistic skin）
- 髪の質感（hair texture）

キャプションの主張は「解像度ではなく細部が秘密」。プロンプト全5本は「8K」とコメントすると DM で送る形で、投稿内で読めるのは最終ショットに表示される1本のみ。

画面テキストの綴りは動画ママだと誤記がある（「8K DEFIND」「Realstick skin」など）。

## プロンプト（最終ショット「Nano Banana Prompt」の全文）

最終ショットのフレーム画像から直接読み取り（2回確認で一致）。末尾の「zoom level」の直後に小さな「v」のような文字が1つ見える（フレーム上は "levelv" 状）。本文はそこで終わっている。

```text
Render this subject as an 8K ultra-realistic photograph. Reconstruct pore-level skin detail across the entire face, natural colour variation between forehead cheeks and chin, peach fuzz catching light along the jaw and hairline, realistic subsurface scattering showing warm blood tone beneath the skin, individual eyebrow hairs with natural growth direction, natural asymmetry throughout. No smoothing, no retouching. Keep the exact same identity, expression, angle, zoom distance and lighting. Same framing, aspect ratio, crop level, zoom level
```

### 要点

「8K 化しろ」ではなく、毛穴レベルの肌・額／頬／顎の色の違い・産毛・血色の透け（subsurface scattering）・眉毛1本ずつの生え方向・自然な左右非対称を再構築しつつ、同一性・表情・角度・照明・構図は完全維持し、滑らかにしたりレタッチしたりしない、というアップスケール専用の指示。対象モデルは Nano Banana（Gemini の画像モデル）想定。
