# python-web-scraping-sample

某物件情報サイトから物件情報をスクレイピングできるアウトプットサンプル。

各種ライブラリの使用方法を理解。

urlはこちら
https://github.com/massu-159/python-web-scraping-sample

## 環境変数
ソースコード内の変数設定してください。
```
<URL>  スクレイピングをかけるurl

<FILE>  書き出すファイルパス
```

## アプリケーションの仕様

### 1. 仕様
- 物件情報
  - 物件情報の条件設定（家賃、最寄駅、部屋数、・・・）
- スクレイピング
  - 進捗表示
  - 時間計測
  - 取得件数表示
  - 負荷分散
- CSV書き出し

### 2. 構成技術
- python : 3.9.15
- csv
- numpy
- requests
- bs4
- retry

