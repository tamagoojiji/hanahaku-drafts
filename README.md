# 花博 下書きBOX（hanahaku-drafts）

花博SNS下書き保管システムの閲覧用PWA。スプレッドシートに保管された下書き（X / ストーリーズ / オープンチャット）をスマホで見てコピーし、投稿済みチェックを付ける。

- ホスティング: GitHub Pages（静的・ビルド不要）
- 接続先: GAS Web App（URL・APIキーは初回アクセス時に入力→localStorage保存。コードには含まれない）
- 将来のUSJ対応: `index.html` 内の `TABS` 配列にタブ設定を追加するだけ
