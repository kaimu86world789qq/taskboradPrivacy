# プライバシーポリシーの公開用ファイル

「タスクボード — ロック画面とホーム画面で見えるToDo」の日本語・英語ポリシーと案内ページです。

- `privacy-ja.md`: 日本語
- `privacy-en.md`: English
- `index.md`: 案内ページ
- `_config.yml`: GitHub Pages（Jekyll）のサイト設定

このフォルダの内容を公開用リポジトリのルートに配置し、GitHub Pagesで公開します。公開後のページは `privacy-ja.html`、`privacy-en.html` です。更新時は、このフォルダと `C:/app_project/99Privacy/taskboradPrivacy/` の対応ファイルを同じ内容に保ってください。

## 公開前に確認すること

- 対象年齢は未決定のため、元アプリの「16歳以上」という記載は引き継いでいません。ストアの対象年齢・対象ユーザー設定と広告SDK設定を決めたら、必要な説明を整合させてください。
- 現行アプリにはUMP等の広告同意取得・撤回の画面がありません。EEA・英国・スイスなどへ配信する場合は、必要な同意対応とAdMob側の設定を行い、ポリシーの「広告に関する選択」を実装に合わせて更新してください。
- アプリの設定から日英のポリシーをオフラインで閲覧でき、Web版へのリンクもあります。壁紙の自動更新の停止設定についても本文に記載しています。
- Androidの自動バックアップは明示的に無効化されていないため、「バックアップ無効」とは記載していません。
- 運営者名とメールアドレスは、いただいた元ポリシーのものを引き継いでいます。

参照資料:

- [Google Mobile Ads SDKのデータ開示資料](https://developers.google.com/admob/android/privacy/play-data-disclosure?hl=ja)
- [Googleの欧州向け広告同意の案内](https://developers.google.com/admob/flutter/privacy/gdpr)
