# Random Quotes Generator

## プロジェクト概要

ランダムに、プログラミング関連の名言を出力するWebアプリです。
無料のAPIを利用しています。
無料なため、429エラー(Too Many Requests)が発生することがあります。

## 使用方法

1. **依存関係のインストール**:

```sh
npm install
```

2.  **開発サーバーの起動**:

```
npm run dev
```

## その他コマンド

lint チェック(もしまとめて確認したい際は実行)

```
npm run lint
```

コードの整形(vsCode の拡張機能で保存時に自動整形されるよう設定してありますが、一括整形したい際に利用してください。)

```
npm run format
```

ビルドコマンド(コミット前に、実行してビルドエラーがないことの確認をお願いします)

```
npm run build
```

## 制作時メモ

### デプロイ

PUSH 検知にて GitHub Pagesに自動デプロイされます.

### 環境変数について

現在利用していません。
(名言APIはAPIキーなしでリクエスト可能です)

## 制作の背景,作った感想

- connpassで参加したハンズオンの内容を試してみるために作りました。若干そのままではない作りとしています。
- React \* Vite \* GitHub Pagesでホスティングしたことがなかったため、ホスティングして公開するymlを最初から手書きしようとして少し時間をかけてしまいました。流石に環境別に無料で複数ドメイン取得はできなかったです。
- Gitの運用ルール(PUSH制限など)をコードベースで管理できるようにしたかったのですが、無料プランだとできないことに気づかず進んでいたため、素直にGitHubの設定画面で慣れるようと思いました(いくつかリポジトリに設定してテストできたのでよかったです。)

## 公開url

https://tominaga-tora.github.io/random-quote-generator/
