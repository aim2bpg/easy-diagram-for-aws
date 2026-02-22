# 簡易構成図ツール for AWS

画像・URLで簡単に共有できるテンプレート式のAWS簡易構成図ツール

## Demo

https://aim2bpg.github.io/easy-diagram-for-aws/

## 特徴

- AWSインフラのアーキテクチャをテンプレート上でビジュアルに構成
- リソースの表示／非表示をサイドバーのトグルで直感的に制御
- 構成をURLパラメーターにエンコードしてワンクリックで共有
- 構成図を画像（PNG）としてクリップボードにコピー可能
- HA（冗長化）モードで複数AZの構成をワンクリック切替
- FE層 + ALB（内部）の有無に合わせてルーティング矢印を動的に切替
- WAF・CloudFront・APIゲートウェイ・IGWへの経路を動的にルーティング
- サブネット種別（プライベート ↔ パブリック）の切替表示

## 収録リソース

| カテゴリ | リソース |
|---|---|
| システム管理 | Session Manager, CloudTrail, AWS Config, Management Console |
| ネットワーク | VPC, IGW, NGW, ALB (公開/内部), WAF, CloudFront, API Gateway, Route 53, ACM, ネットワークFW |
| コンピューティング | EC2, Fargate, EKS, Lambda, ENI |
| データストア | Aurora, RDS, DynamoDB, ElastiCache, EFS, S3 |
| CI/CD | CodePipeline, CodeCommit, CodeBuild, CodeDeploy, ECR, ECS |

## 使い方

1. ブラウザで `index.html` を開く（またはDemo URLへアクセス）
2. サイドバーのリソースボタンをクリックして表示／非表示を切替
3. **URL共有** ボタンで現在の構成をURLとしてコピー
4. **図をコピー** ボタンで構成図をPNG画像としてクリップボードへコピー

## License

MIT
