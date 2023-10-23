# ブルー/グリーンデプロイ - Blue/Green Deploy
## Aurora MySQL
[ブルー/グリーンデプロイの作成 - AWSドキュメント](https://docs.aws.amazon.com/ja_jp/AmazonRDS/latest/AuroraUserGuide/blue-green-deployments-creating.html)
- カスタムDBクラスターパラメータグループで `binlog_formata = ROW` を設定する。
- ライターインスタンスを再起動する。