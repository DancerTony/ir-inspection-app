IR検査 PWA（配布用）

このフォルダ一式をそのままWebに公開すると、PWAとしてホーム画面に追加できます。

最短手順（GitHub Pages）
1) GitHubで新規リポジトリを作成
2) このフォルダ内のファイルをリポジトリ直下にアップロード
3) Settings -> Pages -> Deploy from a branch
   Branch: main, Folder: /(root)
4) 表示されたURLを相手に共有

相手側
- iPhone: Safariで開く -> 共有 -> ホーム画面に追加
- Android: Chromeで開く -> メニュー -> アプリをインストール

更新したら service-worker.js の CACHE_NAME の末尾 v1 を v2 に変更すると確実に反映されます。
