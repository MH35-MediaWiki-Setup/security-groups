# Security Groups

MediaWiki用のセキュリティグループを定義します

## 使い方

1. `aws cloudformation deploy --template-file formation.yml --stack-name [your stack name] --parameter-overrides Vpc=[your created vpc ID]`する
2. デプロイ完了まで待つ

## 作成されるもの

* ALB用セキュリティグループ
* バウンスハンドラLambda用セキュリティグループ
* EC2インスタンス用セキュリティグループ
* RDSインスタンス用セキュリティグループ
* Elasticacheインスタンス用セキュリティグループ
