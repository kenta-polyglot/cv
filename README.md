# 業務経歴書

## 基本情報

|key|value|
|----|----|
|名前|勝又 健太|
|生息地|東京都 渋谷区|
|オンラインサロン|[雑食系エンジニアサロン](https://kentakatsumata.net/archives/10) (参加者数1,500超)|
|Twitter|[@poly_soft](https://twitter.com/poly_soft) (フォロワー18,000超)|
|Qiita|[@poly_soft](https://qiita.com/poly_soft) (Contribution数15,000超)|
|Youtube|[雑食系エンジニアTV](https://www.youtube.com/channel/UC_HLK-ksslL-Z_2wiIZDlMg) (チャンネル登録者数35,000超)|
|ポートフォリオ|[kenta-aktsk](https://github.com/kenta-aktsk) (ほぼElixirのみ)|
|小説|[鬼喰い](https://ncode.syosetu.com/n1075ct/)|
|英語力|TOEIC820点|
|bokete力|[星13,000超](https://bokete.jp/user/polysoft)|

## 概要

- クラウドアーキテクチャ設計、クラウドインフラ構築管理、基盤コード開発、DevOps/MLOpsが現在の専門です。

- バックエンドの多種多様な言語/DB/フレームワークを用いた豊富な開発経験があり、AWS/GCPの様々なマネージドサービスに精通しています。(一応AndroidアプリとiOSアプリの開発経験もあります。元々はWindows系のエンジニアなので.NET系の開発も多数経験しておりますが現在はLinuxプラットフォームでの開発がメインです)

- 小規模〜中規模サービスの新規開発フェーズや、サービスのリプレイスフェーズにおいて非常に有用なエンジニアだと思います。(改修フェーズや保守運用フェーズも対応可能ではありますが、サービスのアーキテクチャ設計の段階から参画させて頂くことで最もバリューを発揮できるタイプです)

- 「手を動かすエンジニア」としての業務から「開発コンサル」「技術コンサル」「技術顧問」まで幅広く対応可能です。お仕事に関するお問い合わせはTwitterのDM等からお気軽にどうぞ。

## スキル

- 基本的にすべて実業務で使用した技術だけを列挙しています。

### 言語

Rust | Kotlin | Scala | Java | Go | Elixir | Ruby | Python | PHP | Perl | JavaScript | TypeScript | VC++ | C# | VB.NET | Delphi | Objective-C | Action Script

### フレームワーク等

Iron | Vert.x | Finch | Cats | Shapeless | Scaldi | PlayFramework | Slick | ScalideJDBC | Spec2 | Struts | Revel | Phoenix | Ruby on Rails | Flask | Django | Zend Framework | CodeIgniter | CakePHP | Ethna | Symfony | jQuery | Vue.js | MFC | .NET Framerowk

### RDB/NoSQL

MySQL | PostgreSQL | Greenplum | Oracle | SQL Server | Redis | Memcached | Tokyo Tyrant | Kyoto Tycoon

### クラウド

#### AWS

VPC | S3 | Cloud Front | API Gateway | Lambda | ELB | EC2 | ECS | Beanstalk | EKS(Kubernetes) | Route53 | IAM | Cognito | Elasticsearch Service | RDS(MySQL|PostgreSQL) | Aurora | DynamoDB | ElastiCache(Redis) | Kinesis | Kinesis firehose | SQS | SNS | SES | Redshift | EMR(Spark) | Cloud Formation | Cloud Watch | AWS Batch | AWS Organizations


#### GCP

VPC | GCS | Cloud Functions | GCE | GKE(Kubernetes) | GAE/SE(Standard Environment) | GAE/FE(Flexible Environment) | IAM | Cloud SQL | Cloud Memorystore(Redis) | Cloud Pub/Sub | Cloud NAT | Cloud Armor | BigQuery | Dataflow(Apache Beam) | Composer(Airflow) | ML Engine | Datalab | Deployment Manager | Cloud Build | Stackdriver Logging | Stackdriver Monitoring

### SaaS/PaaS

GitHub | GitHub Actions | BitBucket(Stash) | CircleCI | Wercker | DataDog | Sentry | NewRelic | TreasureData | DeployGate | TestFlight

### その他

Terraform | Spinnaker | Envoy | Docker | Xen | Jenkins | Fluentd | Capistrano | Chef | nginx | unicorn | Apache | Tomcat | Gulp | Webpack | Pug | SASS | Mecab | Zabbix | munin | Elasticsearch | Kibana | RabbitMQ | LDAP | LVS | BIND | DHCP | IIS | Active Directory | DirectShow | Sharepoint Server | Exchage Server

## バリューを発揮しやすい業務

- クラウドアーキテクチャ設計
- クラウドインフラ構築管理
- 基盤コード開発
- パッケージマネージャの導入
- LinterやFormatterの導入
- 単体テストや統合テストの導入
- local/dev/stg/prod環境の適切な切り分け
- Gitブランチモデルの適切な定義
- アプリケーションのマイクロサービス化
- サーバーレスアーキテクチャの導入
- 認証サービスの導入
- メッセージングサービスの導入
- 全文検索サービスの導入
- CDNの導入
- CIサービスの導入
- コンテナ化(Docker化)
- インフラのコード化
- オートスケールの設定
- デプロイの自動化
- データベースマイグレーションの自動化
- バッチジョブのフロー制御
- クラウドの権限管理
- 監視ダッシュボードの導入
- ログ収集と分析基盤の構築

## 主な業務経歴

### ブロックチェーン系BtoBサービスのインフラ構築/DevOps基盤構築【Go/EKS/Envoy/Spinnaker/Terraform/AWS】(2019年)

【プロジェクト概要】ブロックチェーン系BtoBサービスの新規開発チームにおいて、インフラの構築/DevOps基盤構築、検証用アプリケーションの開発作業等を担当

【担当業務】Terraformによるインフラのコード化、SpinnakerによるCDパイプラインのコード化、Envoyによるサイドカーパターンの構築、KubernetesのManifest作成、各種自動化スクリプトの作成等を担当。具体的には下記。

- Terraformによるインフラのコード化(VPC/EKS/Aurora/ElastiCache等)
- EKSを使用したマイクロサービス基盤の構築
- Envoyを使用したサイドカーパターンによるマイクロサービスアーキテクチャの構築
- SpinnakerのPipelineとArtifacts機能を使用したCDパイプラインのコード化
- KubernetesのManifestファイル作成
- shellcheck/hadolint/kubeval等を使用したバリデーションの実装
- GitHub Actionsを使用したCI/CDパイプラインの構築
- 上記の全ての機能が実装された検証用アプリケーション(Go + gRPC)の作成と本体アプリケーションへの機能の組み込み

【発揮したバリュー】これまでの案件で培ったAWSやDevOpsの知見を活かし、インフラのコード化やCI/CDパイプラインの構築、各種自動化作業等に大きく貢献。Spinnakerは初体験であったがPipelineやArtifacts等の機能を速習して短期間でキャッチアップ。Envoyを使用したサイドカーパターンも初体験であったがこちらも速習して短期間で対応。

### ニュース配信系サービスのアーキテクチャ設計/インフラ構築/API開発/DevOps基盤構築【Go/Python/EKS/Terraform/AWS】(2019年)

【プロジェクト概要】ニュース配信サービスの新規開発チームにおいて、アーキテクチャ設計やインフラの構築管理、基盤コードの作成作業等を担当

【担当業務】サービス全体のアーキテクチャ設計、Terraformによるインフラのコード化、各種デプロイスクリプトの作成、バッチジョブの作成、ゲートウェイ用APIの開発等を担当。具体的には下記。

- Terraformによるインフラのコード化(VPC/EKS/ElastiCache/Aurora等)
- EKSを使用したマイクロサービス基盤の構築
- App Meshを使用したサービスメッシュの検証
- Elastic Beanstalkを使用したAPI基盤の開発
- Go + gRPCによるマイクロサービスの基盤コードの開発
- Python + Flaskによる機械学習APIの基盤コードの開発
- CloudWatch + AWS Batchによる各種バッチジョブの作成

【発揮したバリュー】AWSを使った案件は久々であったが、前案件で培ったマイクロサービスおよびMLOpsの知見を活かしてモダンなアーキテクチャ設計やインフラのコード化、デプロイの自動化作業等に大きく貢献。Terraformは初体験であったがCloudFormation等の知識を活かして短期間でキャッチアップ。EKSの構築管理も未体験であったがGKE/Kubernetesの経験を活かしてこちらも短期間で学習。

### 機械学習系システムの開発ワークフロー整備/API開発/インフラ構築【Go/Python/AWS/MLOps】(2018年〜2019年)

【プロジェクト概要】国内最大級の情報サイトを運営している企業様の機械学習チームにおいて、開発ワークフローの整備やクラウドインフラの構築管理等、いわゆる「DevOps」「MLOps」系の業務を担当。

【担当業務】複数のマイクロサービスにおける共通の開発ワークフロー整備やサービス全体のアーキテクチャ設計、WebAPIと機械学習APIの連携、GCP上のインフラ構築等多種多様なタスクを担当。具体的には下記。

- Istio導入によるサービスメッシュ化のメリットの調査。
- Knative+Istioを使用したサーバーレスプラットフォーム環境の調査。
- GKE + Go + gRPC + Pythonの組み合わせによるマイクロサービス構成の調査と開発。
- Go + OpenAPI3.0 + go-swaggerによるREST API定義とモデルの自動生成によるAPI開発。
- Gitリポジトリのブランチモデルの定義およびBitbucketを使用したレビュー＆デプロイフローの整備。
- Cloud Source RepositoryとCloud Buildを使用したCI/CD環境の構築
- Cloud DatalabとML EngineとCloud Composer(Airflow)を使用した機械学習ワークフローの構築。
- Cloud Dataflow(Apache Beam)を使用したビッグデータ分散処理に関する調査と開発。
- Cloud Composer(Airflow)を使用したジョブフロー制御基盤の構築。
- Cloud Memorystore(Redis)の導入。
- Pipenvの導入によるPython開発環境の共通化と環境毎の差異の解消。
- flake8とblackの導入によるコードフォーマットの統一とコードレビューの効率化。
- GAE/FEとGKE(Kubernetes)を用いたBitbucket連携サーバの開発。
- GAE/FEとCloud SQLを用いた簡易推薦APIの開発。
- VPCとGAEのファイアウォール設定。
- GCEを用いたNAT Gatewayの構築とルーティング設定。
- GCEを用いた踏み台サーバの構築。
- Cloud Deployment Managerとgcloudを使用したインフラのコード化。
- Cloud Functionsを使用したDBの自動マイグレーション機能の導入。
- Stackdriver Monitoringを使用した監視ダッシュボードの構築。

【発揮したバリュー】「GitHubが使えない」「サードパーティのCIツールが使えない」「ローカル環境から外部ネットワークへのSSH接続が禁止されている」「インフラに対する外部からのアクセス元IPの制限が非常に厳しい」「GCPのプロジェクトを自由に作成出来ない」等、様々な制約条件のある中での業務であったが、幅広い知識とスキルと速習能力を活かし、「モダンな開発ワークフローのスムーズな導入」および「少人数で管理可能な省力化された機械学習インフラ構成」を実現してチームに大きく貢献。

### 汎用レコメンダシステムの開発【Kotlin/Vert.x/TypeScript/Vue.js】(2017年〜2018年)

【プロジェクト概要】機械学習系のプロダクト開発に強みをもつ企業様において、汎用レコメンダシステムの開発作業を担当。

【担当業務】主にインフラ設計やアプリケーションのアーキテクチャ設計作業を担当し、CloudFormationによるAWSのインフラ構築と管理、CircleCIによるCI/CD環境の構築、APIサーバのWebフレームワークの選定、各種実装作業等を担当。
言語はKotlin。WebフレームワークはVert.x。データベースはDynamoDBとAurora、認証基盤にはCognito、ログ収集にはFluentd、分析基盤にはBigQuery、監視系ダッシュボードにはDataDogを使用。
フロントエンド(管理系画面)の実装も担当。言語はTypeScript、フレームワークはVue.jsを使用。(HTMLはPug化、CSSはSASS化)

【発揮したバリュー】CloudFormationによるAWS構成管理は初体験であったが短期間で学習しキャッチアップ。インフラのコード化とデプロイの完全自動化を実現。またAWSサポート等を有効に活用して適切なAWSサービスを選択/提案しサービス全体のシンプル化に貢献。フロントエンドの担当も久々であったが最新のトレンド(Flux/Webpack/Babel/TypeScript等)を短期間で学習してモダンな構成を実現。

### 大規模DMPの開発・運用業務【Scala/Rust/GCP】(2017年)

【プロジェクト概要】大規模DMPの開発・運用業務を担当。

【担当業務】主にAPIの開発・改修・移植作業を担当。使用言語はScala/Rust。使用した主なライブラリはScalaがFinch/Cats/Shapeless、RustはIron。
サーバー環境はGCP(Kubernetes/GKE/GCS/Cloud Pubsub)。
分散処理基盤としてApache Spark、分析基盤としてTresure Dataを使用。

【発揮したバリュー】Scalaに関しては「Better Java」ではなく「関数型スタイルでの開発」が徹底されている環境だったため、CatsやShapeless等の関数型ライブラリの使用方法や概念に慣れるまで非常に苦労したが、「Scala関数型デザイン＆プログラミング」等で学習し短時間でキャッチアップ。GKE(Kubernetes)も同様に短期間でキャッチアップして早い段階で戦力として貢献。
Rustに関しては未経験(チーム内にも経験者ゼロの状態)であったが、こちらも短時間で「オーナーシップ」や「ライフタイム」等の概念を理解して2ヶ月ほどでAPIの移植作業を完了。

### ネイティブ広告プラットフォームの開発【Scala/Go/Spark】(2016年)

【プロジェクト概要】SEOコンサルティングやトレーディングデスク事業等を行っておられる企業様において、ネイティブ広告プラットフォームの開発作業を担当。

【担当業務】Apache SparkとScalaを使用した大量データのバッチ処理システムの機能追加、Golangを使用した配信サーバーの機能追加、広告タグ(JavaScript)の改修、クローラー(Ruby)の改修作業等を担当。

【発揮したバリュー】Scala、Goともに初経験であったが、持ち前の速習力を発揮して短期間でキャッチアップ。
Sparkおよび分散処理フレームワークとMap/Reduceの概念、文書マッチングの際のTF-IDFや機械学習系ライブラリの使用方法に関しても見識はほぼゼロの状態だったが、こちらも短期間でキャッチアップ。
Scala/Golang/Ruby/JavaScriptと、タスクごとに多言語を行き来する環境であったが、強みである速習力とユーティリティ性を発揮して多面的にチームに貢献。

### メディア系Webサービスの雛形開発【Elixir/Phoenix】(2016年)

【プロジェクト概要】Elixir/Phoenixの技術検証、および外部への技術アピール用(主目的はリクルーティング)にメディア系Webサービスのサンプルプロジェクトを開発。

【担当業務】認証/認可/ソーシャルログイン/多言語対応/DBのマスタースレーブ対応/ページネーション/S3への画像ファイルアップロード/SESによるメール送信/OGP/サイトマップ/RSS/ElasticSearchによる全文検索等、通常のメディア系Webサービスで必要になる機能を、ElixirとPhoenixで実装。

【発揮したバリュー】不足している機能は専用のパッケージを開発してhexにアップ、Phoenixや各種パッケージの不具合を多数発見してプルリクを送信する等、Elixirのエコシステムにも貢献。Qiita記事の投稿やイベントでの登壇等、チームおよび企業自体のプレゼンスの向上に貢献。

### オタク女性向けのニュースまとめ系Webサービスの開発【Rails/AWS】(2015年)

【プロジェクト概要】オタク女性向けのニュースWebサイトの開発。

【担当業務】サーバーサイドの開発およびインフラ構築を担当。
DB設計/管理画面/認証/API/画像アップロード/ソーシャルログイン/多言語対応/サイトマップ/RSS/OGP/Cron設定/ランキング算出用バッチ/Capistranoによるデプロイスクリプト/WerckerによるCI/Fluendによるログ集約/NewRelic/フロントエンドへのGulp導入/XSS対策/CSRF対策/n+1問題対策/SEO対応等、様々な機能の設計/実装をメインエンジニアとして担当。

【発揮したバリュー】Railsを使用してゼロからコードを書くこと、およびAWSを本格的に使用するのはこれが初体験であったが、持ち前の速習力を発揮して短期間でキャッチアップ。様々な情報を参考にしてその時点のベストプラクティスな手法やライブラリを入念に調査＆積極的に採用し、良い意味でコモディティ化された保守性の高い構成を実現。

### プライベートクラウドの構築管理【Bash/Chef/LDAP/LVS/BIND】(2012年)

【プロジェクト概要】プライベートクラウドの各種管理作業

【担当業務】プライベートクラウドの各種管理作業(ノード追加やLDAP設定等)、ロードバランサーの設定作業(仮想IPの追加や冗長化構成の変更作業等)、社内DNSの設定作業(ゾーンの移動や冗長化構成の変更作業等)、Cassandra/Redis/RabbitMQ等のrpm作成やインストール/初期設定作業、Capistrano/Chef-Soloを使用した構成管理作業等を担当。

【発揮したバリュー】本格的なインフラエンジニア業務は初体験であったが、書籍やネット等でBashスクリプトやLDAP、LVS、BIND等を速習し、短期間で戦力化してチームに貢献。後半は当時まだ情報の少なかったChef-Soloを使用したノードの構成管理業務等の難易度の高い業務も任されたがこちらも完遂してタスク処理能力の高さを発揮。

### カードバトル系ソーシャルゲームの開発【PHP/MySQL】(2012年)

【プロジェクト概要】カードバトル系ソーシャルゲームの開発とDB負荷対策

【担当業務】招待機能、日記機能、Flash Liteとの連携機能、クエスト系イベント機能の改修作業、およびイベントランキング用バッチの改修作業等を担当。
後半は技術調査チームにジョインしてMySQL周りの調査・負荷測定作業の担当となり、パーティション設定、レプリケーション設定、my.cnfの適切なパラメータ設定等に関する各種提案作業を行う。その他mysqlslapを使用した負荷測定のマニュアル作成や、HandlerSocketの適切な使用法の解説、blackholeストレージエンジンの調査、MySQLソースコードの局所的な解析作業等も担当。

【発揮したバリュー】ソーシャルゲーム開発の黎明期から培ってきたノウハウを活かしてチームの生産性向上に大きく貢献。技術調査チームにおけるMySQL周りの負荷対策やチューニング業務は初体験であったが各種書籍やネット情報をフル活用して異常な高負荷の原因を突き止めるなど技術調査業務でも貢献。

### 動画キャプチャソフトの開発【C#/VC++】(2009年)

【プロジェクト概要】動画キャプチャソフトの開発

【担当業務】DirectShowとC#を使用した動画キャプチャソフトのほぼ全ての機能の開発を担当(ゲームプレイヤーがプレイ動画をYoutube等にアップすることをメインの用途として想定)。動画変換部分にffdshow等のフリーウェアを使用した以外は、C#によるフォーム作成や動画キャプチャ＆保存機能等のほぼ全ての実装/テスト/デバッグ作業等を一人で担当。

【発揮したバリュー】録画時の音ズレ発生に悩まされたが、動画キャプチャ後にAVIファイルのヘッダを書き換える方式を独自に考案して対応。(実際にキャプチャできたフレーム数と録画時間の差異を計算して、再生時用のフレームレートを書き換える等の処理を行った)

### 旅行先での各種観光スポットのクチコミ情報投稿サイトの開発【Java/Struts2】(2009年)

【プロジェクト概要】旅行先の各種スポット(レストラン/ホテル等)のクチコミ情報投稿/閲覧Webサイトの新規開発を担当。

【担当業務】開発用フレームワーク(Struts/iBatis/Spring等)の連携方法やDIに関する調査、各種画面の実装作業、テスト/デバッグ作業等を担当。(作業人員は約3名)

【発揮したバリュー】Linux環境もJavaもほぼ初体験であったが、書籍やネット上の情報、およびチームリーダーのサポートを得て迅速にキャッチアップ。この時点ではチームリーダーも知らなかった「DI」の概念を調査および理解してシステムに落としこむ等、ここでも学習能力の高さを発揮。

### 世界初のマンガ作成用グラフィックソフトの開発【VC++/MFC】(遥か昔)

【プロジェクト概要】当時としては世界初の、マンガ作成用グラフィックソフトの新規開発を担当。

【担当業務】言語はVisual C++、フレームワークとライブラリはMFCとSTLを使用し、主にアプリケーション全体のクラス設計と、画像ファイル処理、画像変形処理(回転/拡縮等)、変形時の画像補間処理、ディスプレイへの描画処理等の実装、デバッグ作業等を担当。

【発揮したバリュー】画像処理アルゴリズム等は全く未経験であったが、各種書籍や、当時画像処理系の記事が連載されていた「C Magazine」のバックナンバーを購入する等して対応。(C Magazineの連載に掲載されていたアルゴリズムにはいくつか誤りがあったが、自分でそれを発見して修正対応するなど、学習能力の高さを発揮)
