# ClipCaptioner

ブラウザ上で動画のキャプション作成・クリップ編集を行う、GitHub Pages向けの静的アプリです。

## GitHub Pagesで公開する

1. このフォルダをGitHubリポジトリにpushする。
2. リポジトリの **Settings → Pages** を開く。
3. **Build and deployment** で **Deploy from a branch** を選ぶ。
4. Branchに `main`、フォルダに `/ (root)` を指定して保存する。
5. 表示されたURLを開く。

`index.html` がリポジトリのルートにあるため、追加のビルド設定は不要です。

## ローカル確認

ブラウザのセキュリティ制限を避けるため、簡易HTTPサーバー経由で開いてください。

```powershell
python -m http.server 8000
```

その後、`http://localhost:8000` を開きます。

## 注意

- UIライブラリとONNX RuntimeをCDNから読み込みます。公開時はインターネット接続が必要です。
- 動画処理は利用ブラウザの対応状況やGPU性能に依存します。
