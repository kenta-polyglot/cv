# 業務経歴書

## 基本情報

|key|value|
|----|----|
|Name|勝又 健太|
|Location|東京都 渋谷区|
|Twitter|[@poly_soft](https://twitter.com/poly_soft) (フォロワー7,000)|
|Qiita|[@poly_soft](https://qiita.com/poly_soft) (Contribution数11,000)|
|Youtube|[雑食系エンジニアTV](https://www.youtube.com/channel/UC_HLK-ksslL-Z_2wiIZDlMg) (チャンネル登録者数8,700)|
|英語力|TOEIC820点|
|bokete力|[星13,000超](https://bokete.jp/user/polysoft)|

## 概要

クラウドアーキテクチャ設計、クラウドインフラ構築管理、基盤コード開発、DevOps/MLOpsが現在の専門です。

バックエンドの多種多様な言語・DB・フレームワークを用いた豊富な開発経験があり、AWSとGCPの様々なマネージドサービスに精通しています。

小規模〜中規模サービスの新規開発フェーズにおいて非常に有用なタイプのエンジニアだと思います。

## スキル

※基本的にすべて実業務で数ヶ月以上使用した技術だけを列挙しています。

### 言語

Rust | Kotlin | Scala | Java | Go | Elixir | Ruby | Python | PHP | Perl | JavaScript | TypeScript | VC++ | C# | VB.NET | Delphi | Objective-C | Action Script

### フレームワーク等

Iron | Vert.x | Finch | Cats | Shapeless | Scaldi | PlayFramework | Slick | ScalideJDBC | Spec2 | Struts | Revel | Phoenix | Ruby on Rails | Flask | Django | Zend Framework | CodeIgniter | CakePHP | Ethna | Symfony | jQuery | Vue.js | MFC | .NET Framerowk

### RDB/NoSQL

MySQL | PostgreSQL | Greenplum | Oracle | SQL Server | Greenplum | Redis | Memcached | Tokyo Tyrant | Kyoto Tycoon

### クラウド

#### AWS

VPC | S3 | Cloud Front | API Gateway | Lambda | ELB | EC2 | ECS | Beanstalk | Route53 | IAM | Cognito | Elasticsearch Service | RDS(MySQL|PostgreSQL) | Aurora | DynamoDB | ElastiCache(Redis) | Kinesis | Kinesis firehose | SQS | SNS | SES | Redshift | EMR(Spark) | Cloud Formation | Cloud Watch


#### GCP

VPC | GCS | Cloud Functions | GCE | GKE(Kubernetes) | GAE/SE(Standard Environment) | GAE/FE(Flexible Environment) | IAM | Cloud SQL | Cloud Memorystore(Redis) | Cloud Pub/Sub | Cloud NAT | Cloud Armor | BigQuery | Dataflow(Apache Beam) | Composer(Airflow) | ML Engine | Datalab | Deployment Manager | Cloud Build | Stackdriver Logging | Stackdriver Monitoring

### SaaS/PaaS

GitHub | BitBucket(Stash) | CircleCI | Wercker | DataDog | Sentry | NewRelic | TreasureData | DeployGate | TestFlight

### その他

Docker | Xen | Jenkins | Fluentd | Capistrano | Chef | nginx | unicorn | Apache | Tomcat | Gulp | Webpack | Pug | SASS | Mecab | Zabbix | munin | Elasticsearch | Kibana | RabbitMQ | LDAP | LVS | BIND | DHCP | IIS | Active Directory | DirectShow | Sharepoint Server | Exchage Server

## 業務経歴

### 【Go/Python/GCP/MLOps】機械学習系システムの開発ワークフロー整備/API開発/インフラ構築 (2018年〜)

#### プロジェクト概要
国内最大級の情報サイトを運営している企業様の機械学習チームにおいて、開発ワークフローの整備やクラウドインフラの構築管理等、いわゆる「DevOps」「MLOps」系の業務を担当。

#### 担当業務
複数のマイクロサービスにおける共通の開発ワークフロー整備やサービス全体のアーキテクチャ設計、WebAPIと機械学習APIの連携、GCP上のインフラ構築等多種多様なタスクを担当。具体的には下記。

- Knative+Istioを使用したサーバーレスプラットフォーム環境の調査。
- GKE + Go + gRPC + Pythonの組み合わせによるマイクロサービス構成の調査と開発。
- Go + OpenAPI3.0 + go-swaggerによるREST API定義とモデルの自動生成によるAPI開発。
- Gitリポジトリのブランチモデルの定義およびBitbucketを使用したレビュー＆デプロイフローの整備。
- Google Cloud Source RepositoryとGoogle Cloud Builderを使用したCI/CD環境の構築
- Google Cloud DatalabとGoogle ML EngineとGoogle Composer(Airflow)を使用した機械学習ワークフローの構築。
- Google Cloud Dataflow(Apache Beam)を使用したビッグデータ分散処理に関する調査と開発。
- Google Cloud Composer(Airflow)を使用したジョブフロー制御基盤の構築。
- Google Cloud Memorystore(Redis)の導入。
- Pipenvの導入によるPython開発環境の共通化と環境毎の差異の解消。
- flake8とblackの導入によるコードフォーマットの統一とコードレビューの効率化。
- GAE/FEとGKE(Kubernetes)を用いたBitbucket連携サーバの開発。
- GAE/FEとCloud SQLを用いた簡易推薦APIの開発。
- VPCとGAEのファイアウォール設定。
- GCEを用いたNAT Gatewayの構築とルーティング設定。
- GCEを用いた踏み台サーバの構築。
- Google Cloud Deployment Managerとgcloudを使用したインフラのコード化。
- Google Cloud Functionsを使用したDBのマイグレーション。
- Stackdriver Monitoringを使用した監視ダッシュボードの構築。

#### 発揮したバリュー

「Githubが使えない」「サードパーティのCIツールが使えない」「ローカル環境から外部ネットワークへのSSH接続が禁止されている」「インフラに対する外部からのアクセス元IPの制限が非常に厳しい」「GCPのプロジェクトを自由に作成出来ない」等、様々な制約条件のある中での業務であったが、幅広い知識とスキルと速習能力を活かし、「モダンな開発ワークフローのスムーズな導入」および「少人数で管理可能な省力化された機械学習インフラ構成」を実現してチームに大きく貢献。

### 【Kotlin/Vert.x/TypeScript/Vue.js】汎用レコメンダシステムの開発 (2017年〜2018年)

#### プロジェクト概要
機械学習系のプロダクト開発に強みをもつ企業様において、汎用レコメンダシステムの開発作業を担当。

#### 担当業務
主にインフラ設計やアプリケーションのアーキテクチャ設計作業を担当し、CloudFormationによるAWSのインフラ構築と管理、CircleCIによるCI/CD環境の構築、APIサーバのWebフレームワークの選定、各種実装作業等を担当。
言語はKotlin。WebフレームワークはVert.x。データベースはDynamoDBとAurora、認証基盤にはCognito、ログ収集にはFluentd、分析基盤にはBigQuery、監視系ダッシュボードにはDataDogを使用。
フロントエンド(管理系画面)の実装も担当。言語はTypeScript、フレームワークはVue.jsを使用。(HTMLはPug化、CSSはSASS化)

#### 発揮したバリュー
CloudFormationによるAWS構成管理は初体験であったが短期間で学習しキャッチアップ。インフラのコード化とデプロイの完全自動化を実現。またAWSサポート等を有効に活用して適切なAWSサービスを選択/提案しサービス全体のシンプル化に貢献。フロントエンドの担当も久々であったが最新のトレンド(Flux/Webpack/Babel/TypeScript等)を短期間で学習してモダンな構成を実現。

### 【Scala/Rust/GCP】大規模DMPの開発・運用業務 (2017年)



#### プロジェクト概要
大規模DMPの開発・運用業務を担当。

#### 担当業務
主にAPIの開発・改修・移植作業を担当。使用言語はScala/Rust。使用した主なライブラリはScalaがFinch/Cats/Shapeless、RustはIron。
サーバー環境はGCP(Kubernetes/GKE/GCS/Cloud Pubsub)。
分散処理基盤としてApache Spark、分析基盤としてTresure Dataを使用。

#### 発揮したバリュー
Scalaに関しては「Better Java」ではなく「関数型スタイルでの開発」が徹底されている環境だったため、CatsやShapeless等の関数型ライブラリの使用方法や概念に慣れるまで非常に苦労したが、「Scala関数型デザイン＆プログラミング」等で学習し短時間でキャッチアップ。GKE(Kubernetes)も同様に短期間でキャッチアップして早い段階で戦力として貢献。
Rustに関しては未経験(チーム内にも経験者ゼロの状態)であったが、こちらも短時間で「オーナーシップ」や「ライフタイム」等の概念を理解して2ヶ月ほどでAPIの移植作業を完了。

### 【Scala/Go/Spark】ネイティブ広告プラットフォームの開発 (2016年)

#### プロジェクト概要
SEOコンサルティングやトレーディングデスク事業等を行っておられる企業様において、ネイティブ広告プラットフォームの開発作業を担当。

#### 担当業務
Apache SparkとScalaを使用した大量データのバッチ処理システムの機能追加、Golangを使用した配信サーバーの機能追加、広告タグ(JavaScript)の改修、クローラー(Ruby)の改修作業等を担当。

#### 発揮したバリュー
Scala、Goともに初経験であったが、持ち前の速習力を発揮して短期間でキャッチアップ。
Sparkおよび分散処理フレームワークとMap/Reduceの概念、文書マッチングの際のTF-IDFや機械学習系ライブラリの使用方法に関しても見識はほぼゼロの状態だったが、こちらも短期間でキャッチアップ。
Scala/Golang/Ruby/JavaScriptと、タスクごとに多言語を行き来する環境であったが、強みである速習力とユーティリティ性を発揮して多面的にチームに貢献。

### 【Elixir/Phoenix】メディア系Webサービスの雛形開発 (2016年)

#### プロジェクト概要
Elixir/Phoenixの技術検証、および外部への技術アピール用(主目的はリクルーティング)にメディア系Webサービスのサンプルプロジェクトを開発。

#### 担当業務
認証/認可/ソーシャルログイン/多言語対応/DBのマスタースレーブ対応/ページネーション/S3への画像ファイルアップロード/SESによるメール送信/OGP/サイトマップ/RSS/ElasticSearchによる全文検索等、通常のメディア系Webサービスで必要になる機能を、ElixirとPhoenixで実装。

#### 発揮したバリュー
不足している機能は専用のパッケージを開発してhexにアップ、Phoenixや各種パッケージの不具合を多数発見してプルリクを送信する等、Elixirのエコシステムにも貢献。Qiita記事の投稿やイベントでの登壇等、チームおよび企業自体のプレゼンスの向上に貢献。
