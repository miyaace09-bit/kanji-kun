# 幹事くんシリーズ

現在は「ボウリング幹事くん」をトップページと `/bowling/` で公開する静的HTML版です。

## 今回の修正

- ハンデ方式を追加
  - ハンデなし
  - 固定ハンデ
  - アベレージから自動計算
- 自動計算式を追加
  - ハンデ/G = floor((基準スコア - アベレージ) × 係数)
- 基準スコア、係数、最大ハンデを設定可能
- 適用ハンデ/G、ハンデ合計、総合点を表示

## 公開方法

このフォルダの中身をGitHubリポジトリ直下にアップロードしてください。

```text
index.html
bowling/
golf/
darts/
mahjong/
party/
shared/
assets/
legal/
README.md
```

Vercelでは Framework Preset を `Other` にしてDeployしてください。
