# 業務経歴書

## 基本情報
|key|value|
|---|---|
|名前|小椋 幸平|
|所在地|大阪府 八尾市|
|生年月日|1996年6月26日|
|Twitter|[@gurico0516](https://twitter.com/gurico0516/)|
|Instagram|[@koheeei26](https://www.instagram.com/koheeei26/)|
|ポートフォリオ|[chomane](https://github.com/gurico0516/chomane/)|
|サイト|[GuriLab](https://gurilab.com/)|
|英語力|TOEIC705点


## 概要
バックエンド開発を中心にWeb開発全般の経験があるWebエンジニアです。主にLaravelとFastAPIを使用し、要件定義、設計、実装、ユニットテスト、技術選定の経験があります。TypeScript、Vue.js、Reactを用いたフロントエンド保守開発やAWSの運用も行いました。チケットアプリプロジェクトでWebチームリーダー、自動車会社プロジェクトでサブPMを担当しました。直近では、バックエンドエンジニアとしてLLMベースのデータ統合・解析プラットフォームのPoC開発でAPIサーバーを設計・実装し、コンテナ環境整備やGitHub ActionsによるCI導入、クローラーバッチとベクトル化バッチの開発、OAuth2.0認証の導入を行い、プロジェクトに貢献しました。

## スキル
- 基本的に実務で関わった技術のみ記載しています。

### 言語
PHP | Python | TypeScript | JavaScript

### フレームワーク/ライブラリ
Laravel | FastAPI | Scrapy | Vue | React | Astro | jQuery | Bootstrap

### RDB/NoSQL
MySQL | PostgreSQL | Oracle | MongoDB

### SaaS/PaaS
GitHub | GitHub Actions | GitLab | Cloud Source Repositories

### Cloud
AWS | Google Cloud | Oracle Cloud

### その他
Mermaid | KeyCloak | MinIO | GitBook | PHPUnit | Linux | Apache | nginx | Podman | Docker | Vagrant | Vite | Webpack | Kibana | OpenAPI | Notion | SourceTree | Jira | Confluence | Backlog | Redmine | Figma | Miro | Adobe Photoshop | Adobe Illustrator

## 本業の業務経歴

### LLMベースのデータ統合・解析プラットフォームの開発【FastAPI, Scrapy, MongoDB, KeyCloak, MinIO, Google Cloud】(2024年)

【プロジェクト概要】
LLMベースのデータ統合・解析プラットフォームのPoC開発

【担当業務1】APIサーバーの開発担当を担当し、以下の業務を行いました。
- 技術スタック（FastAPI, MongoDB, MySQL, Keycloak, MinIO）選定とコンテナ環境の整備
- APIサーバーの全体設計とリモートコンテナ環境（DevContainer）の構築
- LangChainサーバーとフロントエンドの連携機能を含むAPIサーバーの開発
- ドキュメントのアップロード、LLMによる回答生成、対話型チャットの機能実装（入力、新規作成、履歴表示、削除、名称変更）
- チャット履歴とフォルダ内の検索機能の実装
- Keycloakを利用したOAuth2.0の認証サービスの導入
- Mermaidを利用したER図の作成
- 各APIのログ設定を実施
- GitHub Actionsを用いてCIパイプラインを構築し、以下の自動化を実現
  - flake8による静的解析とPEP8規約検査
  - blackを用いたコード整形
  - reviewdogを活用した自動コードレビュー
  - pip-auditを利用したセキュリティ脆弱性スキャン

【担当業務2】クローラーバッチの開発担当を担当し、以下の業務を行いました。
- 技術スタック（Scrapy, MinIO）選定とコンテナ環境整備
- ログ設定を実施
- クローリングによるWebサイトからのテキストデータと添付ファイルデータ抽出結果をオブジェクトストレージへ格納するプロセスの実装

【担当業務3】ベクトル化バッチの開発担当を担当し、以下の業務を行いました。
- 技術スタック（Python, MongoDB, MinIO）選定とコンテナ環境整備
- ログ設定を実施
- MongoDBからドキュメントデータを取得し、オブジェクトストレージに保存されたテキストファイルをベクトル化
- バッチサーバーを介してLangChainサーバーにテキストファイルを送信し、ベクトル化を行うプロセスの実装

【発揮したバリュー】
PoC開発では、効率的なAPIサーバーの設計・実装を行い、迅速で効果的なデータ解析機能を提供しました。コンテナ環境の整備により開発環境のセットアップを簡素化し、チーム全体の生産性を向上させました。また、GitHub Actionsを活用したCIパイプラインの導入により、コードの品質とセキュリティを確保しました。さらに、クローラーバッチの実装により大量のデータを効率的に収集し、解析の基盤を構築しました。ベクトル化バッチの開発では、データの詳細な解析を実現し、OAuth2.0認証の導入によりセキュアなユーザー認証を提供しました。これらの取り組みにより、プロジェクトに大きく貢献しました。

### 企業ウェブサイトの開発【TypeScript, React, Astro, SCSS】(2024年)

【プロジェクト概要】
企業ウェブサイトのリニューアルに伴う新規ページの開発

【担当業務】主にフロントエンド部分を担当し、以下の業務を行いました。
- Astroフレームワークを用いた、静的サイトの構築
- WordPress REST APIを使用して、バックエンドから提供されるコンテンツをフロントエンドに動的に表示する実装
- react swiperライブラリを用いて、ユーザーが簡単にコンテンツを閲覧できるスライダー機能実装
- Fisher-Yates shuffleアルゴリズムを使用し、ページリロード毎にロゴ画像がランダムにシャッフル表示される機能実装
- SCSSを利用した、コードの再利用とメンテナンス性の向上
- TypeScriptを活用した、バグの事前排除と可読性を考慮した実装

【発揮したバリュー】
Astroでの開発は初めてでしたが、公式ドキュメントを読み込み、迅速にキャッチアップしました。その結果、AstroへのReact導入やWordPress REST APIの連携もスムーズに行うことができ、短期間のプロジェクトでも遅延を発生させることなく貢献できました。

### 大手レコード会社のチケットアプリのAPI開発/CMS保守/イベントサイトの改修/クローズドサイトの開発【TypeScript, Vue, React, Laravel, AWS】(2022年〜2024年)

【プロジェクト概要】
アーティストやアニメのイベント系チケットアプリのAPI開発/保守、チケットアプリ管理用のCMS保守、イベントサイトの改修、ファンクラブ限定のクローズドサイトの開発

[担当業務1] チケットアプリAPIリプレイス開発を担当し、以下の業務を行いました。
- OpenAPIを用いたRest APIの設計・開発
- チームメンバーのコードレビューと技術サポート
- CloudWatchログに基づくソースコード・DBデータの修正
- アクセス急増に備えたECSサーバーのAuto Scaling対応とELB監視
- 本番・検証・開発環境へのCodePipelineによるデプロイ
- EventBridgeとStep Functionsを用いた通知バッチ設定
- IAMポリシー設定とユーザー作成
- 懸念事項や顧客要望に関する技術検証と仕様調査

[担当業務2] チケットアプリ管理用CMSの保守を担当し、以下の業務を行いました。
- CSVダウンロード機能のデータ改修
- イベント作成時のリロード処理改修
- イベント当選/落選機能の改修
- イベント応募者のCSVデータ改修

[担当業務3] イベントサイトの開発を担当し、以下の業務を行いました。
- OSに基づくストアまたはアプリ遷移処理のフロントエンド実装
- バックエンドとフロントエンド、外部APIとの連携部分の実装
- Reactのバージョンアップ対応（17から18）

[担当業務4] ファンクラブ限定のクローズドサイトの開発を担当し、以下の業務を行いました。
- Webチームの開発リーダーとしてタスク管理、CMS/API/DB設計、実装、単体テストを担当
- 要件定義と確認事項の整理、デザイナーやアプリエンジニアとの仕様調整
- 推測不可のURL生成、アクセス制御対応
- フロントエンド処理の実装

【発揮したバリュー】
設計からリリースまで一貫して担当し、Laravelでの型定義を必須としたコーディングや各APIにおけるユニットテスト、結合テストを作成しました。主要サービスの外部APIの完全リプレイスも大きな不具合なく完了しました。TypeScriptとVue.jsの開発は初めてでしたが、個人学習で迅速にキャッチアップし、プロジェクトに貢献しました。

### 大手自動車会社のWebアプリの開発【Laravel, JavaScript, Jenkins, Oracle Cloud】(2023年)

【プロジェクト概要】
自動車オーナー向けの整備記録を管理するアプリの保守開発

【担当業務】別プロジェクトと並行して主にマネジメント業務を担当し、以下の業務を行いました。
- チームメンバーのコードレビューと技術フォロー
- タスク進捗管理とタスクアサイン
- Oracle CloudへのJenkinsを用いたデプロイ作業
- 顧客窓口対応
- 画面設計書の作成とレビュー
- PHP7.3からPHP8.2へのバージョンアップデート
- Laravel6からLaravel10へのバージョンアップデート
- PHPおよびLaravelのバージョンアップに伴うライブラリの更新
- Ansibleを利用したリモートサーバーのアップデート

【発揮したバリュー】
リモートでのマネジメントであるため、メンバーのタスク進捗や課題が不透明になりがちでしたが、隔週ミーティングを設定し、各メンバーの状況を確認することで、プロジェクトの遅延を防ぎ、円滑な進行を実現しました。

### 介護業界向けSaaSの開発【JavaScript, PHP, AWS】(2021年〜2022年)

【プロジェクト概要】
2400事業所に導入済みで、利用ヘルパー数7万人、利用高齢者数約22万人の介護事業所向けSaaSの開発

【担当業務】
設計から製造、テストまで一貫して新規機能開発を担当。ペーパーレス化を推進する介護計画書作成機能や、非同期通信を用いて介護計画書のデータを介護モニタリングシートに反映する機能など、多機能なSaaSの開発に従事。また、ユーザーからの問い合わせや障害報告に対応し、不具合修正を行う。

【発揮したバリュー】
製品担当者と仕様を擦り合わせながら基本設計から詳細設計、実装までを担当。その後のテストフェーズでは、ホワイトボックスおよびブラックボックスの両観点からテストを実施。新機能実装時には介護現場での利用状況をイメージするため、実際に介護事業所を見学し、代表者からICT導入後のメリットやデメリットをヒアリング。これらの意見をプロダクトに反映させ、現場のニーズに合った機能を提供。

### 勤怠管理システムの開発【Bootstrap, JavaScript, Laravel】(2020年)

【プロジェクト概要】
勤怠管理システムの新規開発

【担当業務】
フロントエンドとバックエンドの両方を実装。入退室時刻データと週報の勤怠、社員データを結合し、勤怠差分データを抽出。差分を表示する一覧画面の作成や、社員の勤怠が登録されていない場合にアラートを送信するバッジの作成、管理者への勤怠送信時のコメント機能、Google APIを利用したGoogleカレンダーとの連携機能を担当。

【発揮したバリュー】
Laravelを用いた初めての新規開発プロジェクトであったが、公式ドキュメントやチームリーダーのサポートを活用し、迅速にキャッチアップ。新規開発フェーズで多機能の開発に携わり、プロジェクトに大きく貢献。現在もシステムは安定して稼働しており、勤怠管理が効率化された。

## 副業の業務経歴

### 生成AIを利用したAIヘルスケアアプリの開発【Laravel】(2023年)

【プロジェクト概要】
生成AIを利用したAIヘルスケアアプリの保守開発

【担当業務】WebアプリのAPIサーバーの新規開発を担当を担当し、以下の業務を行いました。
- API設計書の作成とレビュー
- Laravelでの型定義を必須とした実装
- ユーザーの健康記録とプロンプトを結合した生成AI用レスポンスの作成
- 複数テーブルのリレーションを用いたAPI開発
- PSR-12に準じたコーディング（Laravel Pint使用）

【発揮したバリュー】
設計から実装まで一貫してAPI開発を担当。初めての生成AIを利用したアプリ開発経験でしたが、ユーザーの健康記録情報と要件に基づくプロンプトを組み合わせたレスポンスを返すAPIなどを開発し、ヘルスケアアプリのプロジェクトに貢献しました。

### 地方特化型総合HRサービスの開発【Laravel】(2023年)

【プロジェクト概要】
地方企業プロジェクトと都市部経営人材を繋ぐ地方特化型総合HRサービスの新規開発

【担当業務】WebアプリのAPIサーバーの新規開発を担当し、以下の業務を行いました。
- API設計書の作成とレビュー
- declare(strict_types=1)を含む静的解析ツールを利用した厳格な型チェックを含む実装
- AWS S3を利用した画像ファイルのアップロード機能の実装
- 複数テーブルのリレーションを用いたAPI開発
- PSR-12に準じたコーディング（Laravel Pint使用）

【発揮したバリュー】
参画から1ヶ月後に第1リリースが予定されていたため、納期厳守と不具合のないAPI開発を求められるプロジェクトでした。複雑な要件の設計ではチームメンバーと入念に確認し、スムーズに実装を進めることができました。結果として、大きな不具合なくプロジェクトを成功に導きました。

### 建築設計事務所向けWebアプリの開発【Laravel】(2023年)

【プロジェクト概要】
建築士と現場の職人のコミュニケーションの円滑化を図るためのチャット機能、設計書共有、書類等の電子化を含んだWebアプリの新規開発

【担当業務】WebアプリのAPIサーバーの新規開発を担当し、以下の業務を行いました。
- API設計書のレビュー
- Docker環境にFirebase Emulatorの導入
- Notificationを利用したメール送信機能とSMS通知機能の実装
- 単一アクションの実行を行うシングルアクションコントローラーでの実装
- declare(strict_types=1)を含む静的解析ツールを利用した厳格な型チェックを含む実装
- 複数テーブルのリレーションを用いたAPI開発
- Tenancyを利用したマルチテナント環境での開発
- PSR-12に準じたコーディング（Laravel Pint使用）

【発揮したバリュー】
ローカル環境にFirebase Emulator UIを導入するDockerfileを作成。また、API開発の効率化を図るため、コントローラー、リクエスト、リソース、ユニットテストの各ファイルを1コマンドで作成する仕組みを導入。その結果、限られた稼働時間内で12本以上のAPI開発に貢献し、安定した品質を保つことができました。

### 大手プログラミングスクールの講師【JavaScript, Ruby on Rails, AWS】(2022年)

【プロジェクト概要】
エンジニア転職を目指す方向けプログラミングスクールの講師業務

【担当業務】
受講生へのプログラミング指導およびコードレビューを担当。

【発揮したバリュー】
1on1でのメンタリングを通じて、受講生個々の理解度や課題に応じた指導を行いました。各受講生のペースに合わせたサポートを提供することで、学習効率を最大化しました。また、リアルタイムでのフィードバックを重視し、問題解決能力を向上させるためのアプローチを取りました。その結果、受講生のプログラミングスキルを向上させることに貢献しました。
