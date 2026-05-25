# 🐱 ねこみくじ

> スワイプして今日の運勢を引こう！ゆるかわ猫のおみくじゲーム

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://keji-dev-jp.github.io/nekomikuji/nekomikuji.html)

## 🎮 遊び方
1. 猫カードを**左右にスワイプ**
2. 運勢が出る（大吉・中吉・小吉・吉・末吉 の5種類）
3. 「もう一回」で何度でも遊べる
4. 結果を**Xでシェア**できる

## ✨ 機能
- 🐱 オリジナルSVG猫イラスト
- 📅 日替わりおみくじ（1日目は毎日固定の運勢）
- 📱 PWA対応（ホーム画面に追加可能）
- 📶 オフライン対応（Service Worker）
- 𝕏 Xシェアボタン付き
- 💫 運勢ごとのパーティクル演出

## 🚀 公開URL
https://keji-dev-jp.github.io/nekomikuji/nekomikuji.html

## 📁 ファイル構成
```
nekomikuji/
├── nekomikuji.html   # ゲーム本体
├── manifest.json     # PWA設定
├── sw.js             # Service Worker（オフライン対応）
└── README.md
```

## 📌 アイコン追加（任意）
- `icon-192.png`（192×192px）
- `icon-512.png`（512×512px）

## 🛠 技術構成
- HTML / CSS / JavaScript（フレームワークなし）
- PWA（manifest + Service Worker）
- GitHub Pages（無料ホスティング）
