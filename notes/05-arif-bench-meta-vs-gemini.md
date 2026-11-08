# 05. 夕日のベンチ（Meta vs Gemini 比較）

- 投稿者: ARIF N STUDIOS @arifnuryono87
- 投稿: https://www.threads.com/@arifnuryono87/post/DfbX1JcEcS0 （2026-11-06、インドネシア語、カルーセル2枚）
- 共有リンク: https://www.threads.com/share/BAaH91IEuJ
- プロンプトの所在: 本人の返信 https://www.threads.com/@arifnuryono87/post/DfbX1FmkTVk （JSON 形式）

## 要約

夕日（golden hour）のベンチに座る赤茶髪の女性のポートレート2枚。Meta と Gemini の生成比較がテーマ。

## 注意点（確認済みの訂正）

- どちらのスライドが Meta／Gemini か、投稿内のどこにもラベルがなく判別できない。顔の系統の違いとモデル名は結びつかない。
- JSON 先頭のキー `"meta"` は「メタデータ」の意味で、Meta 社とは無関係。
- プロンプト指定は黒ショーツだが、実際の画像は茶ショーツ + ベルトになっている。

## プロンプト（JSON、返信からの再掲）

```json
{
  "meta": {
    "aspect_ratio": "9:16",
    "style": "photorealistic",
    "lighting": "golden hour"
  },
  "subject": "22-year-old East Asian woman, long auburn wavy hair, fair glowing skin, black sleeveless tank top, black shorts, seated on a wooden bench outdoors, black quilted handbag beside her",
  "scene": "Outdoor bench at sunset, warm golden-hour light, shallow depth of field, cinematic composition, small 'Arif N Studios' watermark, SFW, professional fashion terminology",
  "negative_prompt": "no UI elements, no blur, no distortion"
}
```
