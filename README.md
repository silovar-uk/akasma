# アカスマ スマホLP

## フォルダ構成

```txt
akasuma_mobile_lp/
├── index.html
├── assets/
│   ├── 01-hero.png
│   ├── 02-program.png
│   ├── 03-league-order.png
│   ├── 04-players.png
│   ├── 05-match-points.png
│   ├── 06-record.png
│   └── 07-awards.png
└── screenshots/
    ├── mobile-390.png
    ├── mobile-430.png
    └── desktop-centered.png
```

## 実装メモ

- 生成済み画像を `assets/` に保存し、縦に隙間なく接続。
- LP幅は最大430px。スマホは画面幅いっぱい、PCは中央表示。
- 透明ボタンを画像上に重ね、未確定リンクは仮モーダル表示。
- モーダルは閉じるボタン、背景クリック、Escキーで閉じる。
- 重要情報は `sr-only` テキストとしてHTML内にも保持。
