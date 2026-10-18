# 盆踊り、民謡流し情報（地図）

公開用の地図ページだけを置くリポジトリ。GitHub Pages で https://dobon.jp/map/ に出る（地図は map/index.html。トップの index.html は /map/ へ送るだけ。ドメインはムームードメイン、DNS はムームーDNS。旧アドレス https://mamecoro-droid.github.io/bon-odori-map-site/ からは自動で飛ぶ）。

- 地図の中身は、スプレッドシート（Apps Script の `?format=json`）を開くたびに読む。ここにデータは置かない
- Google マップのキーは、Google Cloud でこのサイトだけに使えるよう制限してある
- 投稿の受付・確認・スプレッドシートのコードは、別のフォルダ（bon-odori-map）
