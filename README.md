# 若林 誓也 (Wakabayashi Seiya)

- Role: Cloud Infrastructure / Backend Engineer
- Links: [Facebook](https://facebook.com/wakabaseisei) | [Twitter](https://twitter.com/wakabaseisei)

## 得意業務
- クラウドインフラの設計・構築
- アプリケーションのアーキテクチャ設計
- API設計
- アプリケーション基盤構築
- CI/CDパイプラインの設計構築
- テスト戦略策定と実行基盤の構築

## スキル

### 言語
Go, Python, TypeScript, C#, Node.js, Rego

### クラウド
#### AWS
EKS, ECS (Fargate), Amazon Aurora MySQL, IAM, SQS, SNS, SES, S3, ElastiCache for Redis, Lambda, CloudWatch

#### Google Cloud
GKE, Cloud Run, AlloyDB for PostgreSQL, Cloud Spanner, Cloud SQL, Cloud Datastore, BigQuery, VPC, Cloud Load Balancing, Cloud NAT, Cloud Armor, IAP, Secret Manager, Cloud KMS, Cloud DNS, Cloud Monitoring, Cloud Logging, Cloud Pub/Sub, Cloud Storage, Cloud Functions, Cloud Scheduler, Firebase (Authentication, Firestore, Hosting, Cloud Messaging)

### コンテナ
Docker, Kubernetes, Helm

### API/スキーマ定義
gRPC, Connect, Protobuf (Buf), OpenAPI (Swagger), CUE

### CI/CD
GitHub Actions, ArgoCD, GitLab CI, Jenkins

### データ基盤
Databricks, Apache Spark

### その他
- **IaC:** Terraform
- **監視 / オブザーバビリティ:** Datadog, OpenTelemetry
- **セキュリティ / 品質管理:** OPA (Conftest), Trivy, SOPS, OIDC/JWT
- **ミドルウェア / データストア:** Apache Kafka, MySQL, Redis
- **フレームワーク / ライブラリ:** React, React Native, Echo, FastAPI, ASP.NET Core
- **テスト / 負荷試験:** Playwright, Jest, JMeter, NUnit
- **その他環境:** Unity

---

## 主要な経歴

直近の経歴をいくつかピックアップします。

### 医療コンテンツの配信プラットフォームの開発・運用 (2026年2月 - 2026年10月)
- 役割: DRE (Data Reliability Engineer) / データ基盤
- 実績: Databricks・PySparkを用いたデータパイプラインの構築・運用

### 配送プラットフォームのインフラ設計構築 (2025年10月 - 2026年1月)
- 役割: クラウド・DevOps
- 実績:
  - Google Cloudを使用したインフラ設計・構築
  - GitHub Actions + Workload Identity連携によるセキュアなCI/CDパイプラインの構築
  - Conftest (OPA) / Trivy を活用したPolicy as Codeによるインフラの品質・セキュリティ担保

### 暗号資産取引サービスの開発 (2024年9月 - 2025年9月)
- 役割: バックエンド
- 実績:Go, gRPC, Kubernetes (GKE), Cloud Spannerを用いたマイクロサービスの新規機能開発

### 大規模toB向けECサービスのモダナイゼーション (2023年10月 - 2024年8月)
- 役割: バックエンド
- 実績: 基幹システムの一部ドメインのマイクロサービス化を推進（Go, Connect, AWS EKS）

## 個人開発
AWS上にマイクロサービスを構築。[ms-infra](https://github.com/wakabaseisei/ms-infra) / [ms-tech-docs](https://github.com/wakabaseisei/ms-tech-docs)
- **構成:** AWS (EKS, CloudFront, Aurora Serverless v2), Terraform, ArgoCD (GitOps), Go, Connect
