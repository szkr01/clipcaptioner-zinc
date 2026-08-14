# ClipCaptioner

ブラウザ上で動画のキャプション作成・クリップ編集を行う、GitHub Pages向けの静的アプリです。

## 公開URL

https://szkr01.github.io/clipcaptioner-zinc/

## GitHub Pagesで公開する

1. GitHubリポジトリの **Settings → Pages** を開く。
2. **Build and deployment** で **Deploy from a branch** を選ぶ。
3. Branchに `main`、フォルダに `/ (root)` を指定して保存する。

`index.html` がリポジトリのルートにあるため、追加のビルド設定は不要です。

## 注意

- UIライブラリとONNX RuntimeをCDNから読み込みます。公開時はインターネット接続が必要です。
- 動画処理は利用ブラウザの対応状況やGPU性能に依存します。
