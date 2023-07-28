# 業務経歴書

## 基本情報
|key|value|
|---|---|
|名前|小椋 幸平|
|所在地|大阪府 大阪市|
|生年月日|1996年6月26日|
|Twitter|[@gurico0516](https://twitter.com/gurico0516/)|
|Instagram|[@koheeei26](https://www.instagram.com/koheeei26/)|
|ポートフォリオ|[chomane](https://github.com/gurico0516/chomane/)|
|サイト|[GuriLab](https://gurilab.com/)|
|英語力|TOEIC700点|


## 概要
- アプリケーションアーキテクチャ設計、アプリケーション開発、基盤コード開発、バックエンド開発が専門です。
- バックエンドの豊富な開発経験があり、バックエンドとフロントエンドの連携を伴うTypeScript + Vue.jsでのフロントエンド開発経験やAWSでのシステム運用経験もあります。
- 新規開発フェーズ、リプレイスフェーズ、改修フェーズ、保守運用フェーズの各フェーズ経験があるため、どのフェーズでもお役に立つことが可能です。
- 「手を動かすエンジニア」として幅広く対応可能です。お仕事に関するお問い合わせは [GuriLab](https://gurilab.com/) のページよりお気軽にお願いします。


## スキル
- 基本的に実務で関わった技術のみ記載しています。

### 言語
JavaScript | TypeScript | PHP | Ruby

### フレームワーク等
Laravel | Ruby on Rails | Vue.js | React.js | jQuery | Tailwind | Bootstrap

### RDB/NoSQL
MySQL | PostgreSQL | Oracle | Realtime Database

### AWS
VPC | S3 | CloudFront | EC2 | ELB | ECS | Fargate | Route53 | Kinesis | Kinesis Firehose | SNS | SES | IAM | RDS(MySQL|PostgreSQL) | Aurora | CloudFormation | CloudWatch | Step Functions | CloudTrail | EventBridge | KMS | CodePipeline | CodeBuild | CodeDeploy | CodeWhisperer | Systems Manager | Amazon Corretto

### SaaS/PaaS
GitHub | GitLab | GitHub Actions

### その他
Ansible | PHPUnit | Linux | Apache | nginx | Docker | Vagrant | Vite | Webpack | Gulp | Kibana | OpenAPI | Netlify | Notion | Backlog | Redmine | Canva | Adobe Photoshop | Adobe Illustrator

## バリューを発揮しやすい業務
- アプリケーションアーキテクチャ設計
- アプリケーション開発
- API開発
- 基盤コード開発
- パッケージマネージャの導入
- PHPStanやLaravel Pintの導入
- 単体テストや結合テストの導入
- Gitブランチモデルの適切な定義
- 認証サービスの導入
- ログベースでの不具合調査

## 主な業務経歴

### 大手音楽ソフト会社向けチケットアプリのAPI開発/CMS保守/サイト改修【TypeScript, Vue.js, React.js, Laravel, AWS】(2022年〜2023年)

【プロジェクト概要】
アーティストやアニメのイベント系チケットアプリのAPIリプレイス開発、チケットアプリ管理用のCMS保守、イベント詳細サイトの改修を担当。

[担当業務1] チケットアプリAPIリプレイス開発から保守を担当。具体的には下記。
- APIのOpenAPIでのRest API定義による設計及び開発。
- チームメンバーのコードレビュー作業。
- チームメンバーの技術フォロー対応。
- Cloudwatchのログベースでのソースコード修正、DBデータ修正作業。
- イベント抽選時や先行申し込み時に特定の日時、時刻にアプリへのアクセスが急増することに備えて、アプリのECSサーバー台数を増加させるAuto Scaling対応、ELB内のリクエスト数を監視しアプリの可用性を保つ作業。
- 本番環境、検証環境、開発環境それぞれに対して、CodePipelineによるデプロイ作業。
- EventBridgeとStep Functionsでの通知バッチ設定作業。
- IAMにて適切なポリシーを設定したユーザー作成作業。
- 懸念事項や顧客要望の仕様実現可否の技術検証及び調査、フロントエンドとバックエンドの連携に関するチームメンバーとの認識合わせ、及び各機能の工数見積。

[担当業務2] チケットアプリ管理用CMSの保守開発、イベント詳細サイトの改修を担当。具体的には下記。
- Vue.js + Compositon API + TypeScriptによるフロントエンド部分の実装。
- CSVダウンロード機能のデータ処理修正、CMSでのイベント作成時のリロード処理の修正作業。
- イベント詳細サイトにてOSに基づいたストアまたはインストール済みアプリに遷移するフロントエンド処理の実装。
- バックエンドとフロントエンドの連携、バックエンドでの外部APIとの連携部分の実装。
- React17から18へのバージョンアップ対応。

【発揮したバリュー】
設計〜リリースまで一貫して業務を担当。Laravelでの型定義を必須としたコーディングや各APIにおけるユニットテスト、結合テストのテストコードを作成し、テストカバレッジをリプレイス開発期間内に90％以上達成。主要サービスの外部APIの完全リプレイスという大きなプレッシャーを伴う作業も大きな不具合等なく完了。TypeScriptとVue.jsでの開発は初めてであり、特にTypeScript + Composition API + Vue.jsの組み合わせは情報も少なく大変だったが、個人学習でもキャッチアップを行い習得。

### 大手自動車メーカー向けWebアプリの開発【Laravel, Jenkins, Oracle】(2023年)

【プロジェクト概要】
自動車オーナー向けの整備記録を行うアプリの保守開発。

【担当業務】別プロジェクトと並行して、主にマネジメント業務を担当。具体的には下記。
- チームメンバーのコードレビュー。
- チームメンバーの技術フォロー対応。
- チームメンバーのタスク進捗管理。
- タスクの洗い出しを行い、メンバーのタスクアサイン作業。
- Oracle CloudへのJenkinsでのデプロイ作業。
- 顧客の窓口対応。
- PHP7.3からPHP8.2へのバージョンアップデート対応。
- Laravel6からLaravel10へのバージョンアップデート対応。
- PHP, Laravelバージョンアップに伴うライブラリ等のアップデート対応。
- Ansibleを利用したリモートサーバーのアップデート対応。

【発揮したバリュー】
マネジメント業務は初めてであったが、チームメンバーとの信頼関係を構築することに焦点を置き、相談しやすく依頼しやすい関係を築くことができ、プロジェクトを円滑に進めることができた。

### 建築設計事務所向けWebアプリの開発【TypeScript, Vue.js, Laravel】(2023年)

【プロジェクト概要】
建築士と現場の職人のコミュニケーションの円滑化を図るためのチャット機能、設計書共有、書類等の電子化を含んだWebアプリの新規開発。

【担当業務】WebアプリのAPIサーバーの新規開発を担当。具体的には下記。
- API設計書のレビュー作業。
- Docker環境にFirebaseEmulatorの導入。
- Notificationを利用したメール送信機能とSMS通知機能の実装。
- 複数テーブルのリレーションでのAPI開発。
- 単一アクションの実行のみ行うシングルアクションコントローラーでの実装。
- Abstruct Classを利用したController-Service-Repositoryパターンでの実装。
- ServiceクラスとRepositoryクラスでのビジネスロジックとデータアクセスの切り分け。
- declare(strict_types=1)を含み静的解析ツールを利用した厳格な型チェックを含めた実装。
- psr-12に準じたフォーマットでのコーディング。（Laravel Pint使用）

【発揮したバリュー】
ローカル環境にFirebase Emulator UIを導入するDockerfile作成。また、API開発のスピードをあげるために関連ファイル（コントローラー、リクエスト、リソース、ユニットテスト）それぞれのファイルを1コマンドで作成できるよう簡潔化。その結果、限られた稼働時間でありながら12本以上のAPI開発に携わりプロジェクトに貢献。またテストカバレッジは90％以上を達成。

### 介護事業所向けSaaSの開発【JavaScript, PHP, AWS】(2021年〜2022年)

【プロジェクト概要】
2400事業所に導入済で利用ヘルパー、看護師数7万人、利用高齢者数約22万人の介護事業所向けSaaSの開発。

【担当業務】
SaaSプロダクトの設計フェーズから製造、テストまで一貫して主に新規機能開発を行う。ペーパーレス化による介護計画書作成機能や非同期通信を用いて、介護計画書のデータを介護モニタリングシートに既存データをもとに反映する機能などSaaSの多機能に渡る開発に携わる。また、ユーザーからの問い合わせや障害報告があった場合には、不具合対応も行う。

【発揮したバリュー】
製品担当者と仕様を擦り合わせながら基本設計から詳細設計まで担当し、実装まで行う。その後のテストフェーズでは、ホワイトボックス/ブラックボックス両方の観点から実施。新機能実装時に介護現場で機能がどのように使われているのかイメージができなかったため、実際に介護事業所に現場見学にいき、事業所の代表からICT導入後のメリットやデメリットをヒアリングを行い、意見を参考にプロダクトに反映。

### 勤怠管理システムの開発【Bootstrap, JavaScript, Laravel】(2020年)
【プロジェクト概要】
勤怠管理システムの新規開発。

【担当業務】
フロントエンド、バックエンド両方の実装を行い、入退室時刻データと週報の勤怠、社員データなど複数のテーブルを結合し勤怠差分データを抽出。その差分を表示する一覧画面の作成や社員の勤怠が登録されていないときにアラートが送信されるバッジの作成、管理者へ勤怠送信時のコメント機能の実装、Google APIを利用してGoogleカレンダーと勤怠管理システムのカレンダーの連携などを担当。

【発揮したバリュー】
Laravelを使っての初めての新規開発のプロジェクトであったが、公式ドキュメントの情報及びチームリーダーのサポートを得て迅速にキャッチアップ。新規開発フェーズにおいて多機能の開発に携わりプロジェクトに貢献。現在もシステムは滞りなく稼働し続けており、煩雑であった勤怠管理体制が勤怠管理システムの導入により管理しやすい状態になった。

### 大手プログラミングスクールの講師【JavaScript, Rails, AWS】(2022年)

【プロジェクト概要】
エンジニア転職を目指す方向けプログラミングスクールの講師業務。

【担当業務】
受講生へのプログラミング指導やコードレビュー業務を行う。

【発揮したバリュー】
プログラミングの経験の浅い受講生に寄り添った指導を行い、講師として高く評価頂く。自身も文系出身で0からプログラミングを学習した経験を活かして、初学者の方が躓きやすい箇所や専門用語を身近な例に言い換える等の工夫を行い、わかりやすく学習できるように配慮した結果、受講生評価の5段階中4.5を獲得。
