# findhydrant_hikonecity

滋賀県彦根市のオープンデータを活用し、消火栓やその他の水源を検索するウェブアプリケーションです。インタラクティブな地図上に位置情報を可視化し、消火活動のための最寄りの水源を簡単に見つけることができます。

## デモ

**ライブアプリケーション:** **[https://code4fukui.github.io/findhydrant_hikonecity/](https://code4fukui.github.io/findhydrant_hikonecity/)**

![findhydrant_hikonecityアプリケーションのスクリーンショット](https://code4fukui.github.io/findhydrant_hikonecity/ss.jpg)

## 機能

- **インタラクティブな地図:** 彦根市の消火栓やその他の水源（水槽など）の位置を地図上に表示します。
- **ジオロケーション:** 読み込み時に自動的に現在地を中心に表示し、周辺の消火栓を表示します。
- **最寄り検索:** 「最寄り」ボタンを使用すると、現在位置から最も近い水源に瞬時にズームします。
- **詳細情報:** 任意のアイコンをクリックすると、種別、管径、住所などの詳細情報がポップアップで表示されます。
- **直感的なアイコン:** 消火栓、水槽、その他の水源を区別するために、それぞれ異なるアイコンを使用しています。
- **簡単なナビゲーション:** 「前へ」「次へ」ボタンを使用して、リスト内の近い消火栓を順番に確認できます。

## ローカルでの実行方法

1.  このリポジトリをクローンします:
    ```bash
    git clone https://github.com/code4fukui/findhydrant_hikonecity.git
    ```
2.  プロジェクトディレクトリに移動します:
    ```bash
    cd findhydrant_hikonecity
    ```
3.  Webブラウザで `index.html` ファイルを開きます。

## データソース

本プロジェクトでは、彦根市の消火栓オープンデータを加工したCSVファイルを使用しています。

-   **ソース:** 彦根市 消火栓水利データ (Hikone City Fire Hydrant and Water Source Data)
-   **提供元:** 滋賀県彦根市
-   **データURL:** [https://data.bodik.jp/dataset/252026_shoukasen_20200401/resource/88ae56c2-504e-41f9-92d3-ff1175e8d94e](https://data.bodik.jp/dataset/252026_shoukasen_20200401/resource/88ae56c2-504e-41f9-92d3-ff1175e8d94e)

データは `syoukasen_20200401.csv` としてリポジトリ内にローカル保存されています。

## 依存関係

This
