# 業務経歴書

## 基本情報

|key|value|
|---|---|
|名前|小椋 幸平|
|所在地|大阪府 大阪市|
|生年月日|1996年6月26日|
|Twitter|[@gurico0516](https://twitter.com/gurico0516)|
|Linkein|[kohei-ogura](https://www.linkedin.com/in/kohei-ogura/)|
|ポートフォリオサイト|[GuriLab](https://gurilab.com/)|
|英語力|TOEIC700点|

---

## 概要
- Web系システムのバックエンド開発が専門です。
- PHPでのフルスクラッチ開発やLaravelでの開発経験が豊富です。これまで、新規開発フェーズ、リプレイスフェーズ、改修フェーズ、保守運用フェーズと幅広く業務を経験しています。
- TypeScript、Vueでのフロントエンド開発経験もあるため、バックエンドと連携したフロントエンド開発を行うことができます。
- AWS運用経験もあるため一通りのマネジメントサービスに触れたことがあります。

---

## スキル

### 言語
JavaScript | TypeScript | PHP | Ruby | Python

### フレームワーク等
Laravel | Rails | React | Vue | jQuery | Tailwind | Bootstrap | Selenium

### RDB
MySQL | PostgreSQL

### Cloud/AWS
VPC | S3 | CloudFront | EC2 | ELB | ECS | Fargate | Route53 | Kinesis | Kinesis Firehose | SNS | SES | IAM | RDS(MySQL|PostgreSQL) | Aurora | CloudFormation | CloudWatch | Step Functions | CloudTrail | EventBridge | KMS | CodePipeline | CodeDeploy

### SaaS/PaaS
GitHub | GitLab | Github Actions

### その他
PHPUnit | Linux | Apache | nginx | Docker | Vagrant | Vite | Webpack | Gulp | Kibana | OpenAPI | Netlify | Notion | Backlog | Redmine | Canva | Adobe Photoshop | Adobe Illustrator | WordPress | MovableType

---

## 主な業務経歴

### イベント系チケットアプリのAPI開発/CMS保守/サイト改修【TypeScript, Vue, Laravel, AWS】(2022年〜2023年)

【プロジェクト概要】
アーティストやアニメのイベント系チケットアプリのAPIリプレイス開発、チケットアプリ管理用のCMS保守、イベント詳細サイトの改修。

【担当業務】APIのリプレイス開発、アプリのAWS保守運用、運営管理者用CMSの保守、イベント詳細サイトの改修を担当。具体的には下記。
- チケットアプリと顧客情報等を含む外部APIの橋渡しとなる中間サーバーAPIの開発。
- Rest API定義によるAPI設計。
- チームメンバー内でのコートレビュー作業。
- ユーザーから不具合の問い合わせがあった際には、Cloudwatchでログ調査を行い、原因特定し、ソースコード修正、DB不整合による本番DBのデータ修正。
- イベント抽選時や先行申し込み時に特定の日時、時刻にアプリへのアクセスが急増することに備えて、アプリのECSサーバー台数を増加させるAuto Scaling対応、ELB内のリクエスト数を監視しアプリの可用性を保つ作業。
- 本番環境、検証環境、開発環境それぞれに対して、既に整備されたデプロイスクリプトに基づいてCodepipelineによるデプロイ作業。
- チケットアプリと紐付く管理者用CMSのLaravel, Vueでの保守作業。CSVダウンロード時のデータ処理の修正、CMSでのイベント作成時のリロード処理の修正。
- チケットアプリに紐づくイベント詳細サイトの改修を担当。イベント詳細サイトのイベント選択時にios、android、pcの判別を行い、pc以外の場合はそれぞれのOSに基づいたストアまたはインストール済みアプリに遷移する処理をTypeScript, Vueで作成。また、イベントのデータをDBよりLaravelで取得し、TypeScript、Vueとの連携、イベントの手数料や支払い方法を表示するために、外部APIをコールする必要があり、その仕組みをLaravelで作成し、Typecript、Vueとの連携を実施。

【発揮したバリュー】
APIリプレイス開発の初期設計フェーズから案件に参画し、設計、開発、保守まで一貫して担当。Laravelでの型定義を必須としたコーディングや各APIにおけるユニットテスト、結合テストのテストコードを作成し、テストカバレッジをリプレイス開発期間内に90％以上達成し大きな不具合等なくAPIリプレイスが完了、管理者用CMSの保守作業、イベント詳細サイトの改修では、TypeScript、Vueの組み合わせは初めてであったが、Composition APIの初期フェーズでキャッチアップを行いプロジェクトに貢献。

### 介護事業所向けSaaSの開発【JavaScript, PHP, AWS】(2021年〜2022年)
【プロジェクト概要】
2400事業所に導入済で利用ヘルパー、看護師数七万人、利用高齢者数約27万人の介護事業所向けSaaSの開発。

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

### 大規模大学Webサイトの制作・保守【JavaScript, PHP, AWS】(2020年)
【プロジェクト概要】
大規模大学 Web サイトの制作・保守業務。

【担当業務】
大学のWeb担当者様との窓口対応を行いながら、ご要望をもとにサイト制作やバナー作成、地図制作を行う。

【発揮したバリュー】
大学の学部サイトの制作をお客様のご要望通りに迅速に作成。担当者様との窓口対応では、お客様のご要望をしっかりとヒアリングしたうえでサイトの制作を行う。また特設ページのコーディングでは、HTML/Sass, JavaScript, PHP を用いてクイズ形式でサイト訪問者にサイト概要についてわかりやすくなるように作成。

## 業務外活動

### 週単位のお小遣い管理アプリの開発【Tailwind, TypeScript, React, Laravel】(2022年)
【プロジェクト概要】
週単位のお小遣い管理アプリの新規開発。

【担当業務】
Laravel Sailを用いて開発環境の整備を行い、アプリのフロントエンド、バックエンドの開発を担当。フロントエンドでは、TailwindとReactでUIを構築し、SPAで実装。バックエンドでは、Laravelでお小遣い記録機能、収支記録機能、カレンダー機能、グラフ機能、設定画面等の開発を行う。

【発揮したバリュー】
TailwindとReactを公式ドキュメントから情報を得てキャッチアップし、アプリのフロントエンドとして導入。またLaravelでの開発時には、ファットコントローラーにならないようロジックをサービスクラスにまとめ、バリデーションをリクエストごとに分け、共通処理はメソッドにする等で煩雑なコードにならないよう注力し、アプリの保守性を意識しながら開発に取り組んだ。

### 大手プログラミングスクールの講師【JavaScript, Rails, AWS】(2022年)
【プロジェクト概要】
エンジニア転職を目指す方向けプログラミングスクールの講師業務。

【担当業務】
受講生へのプログラミング指導やコードレビュー業務を行う。

【発揮したバリュー】
プログラミングの経験の浅い受講生に寄り添った指導を行い、講師として高く評価頂く。自身も文系出身で0からプログラミングを学習した経験を活かして、初学者の方が躓きやすい箇所や専門用語を身近な例に言い換える等の工夫を行い、わかりやすく学習できるように配慮した結果、受講生評価の5段階中4.5を獲得。

### 飲食店のWebサイト制作【HTML, SCSS, JavaScript】(2022年)
【プロジェクト概要】
飲食店サイトリニューアルに伴うWebサイトの新規制作。

【担当業務】
お客様からWebサイト作成の目的などの念入りなヒアリングを行い、そのヒアリングをもとに要件定義とサイトマップを作成。そこからデザインから制作まで一貫して業務を行う。

【発揮したバリュー】
お客様からのヒアリングを念入りに実施。ヒアリングをもとに課題・問題点を洗い出しお客様と相談しながら要件定義書とデザインを決める。リニューアル前ではレスポンシブ対応がされていなかったため、レスポンシブ対応で作成。CSS設計では、SMACSS手法を用いて SCSS で保守・運用を意識した実装を行う。デザイン面も昨今のモダンデザインを意識して作成し、お客様に満足して頂く。

### タイル施工会社のWebサイト制作【HTML, SCSS, JavaScript】(2021年)
【プロジェクト概要】
タイル施工会社のサイトリニューアルに伴う Web サイトの新規制作。

【担当業務】
お客様からWebサイト作成の目的などの念入りなヒアリングを行い、そのヒアリングをもとに要件定義とサイトマップを作成。そこからデザインから制作まで一貫して業務を行う。

【発揮したバリュー】
お客様がWebサイトリニューアルにあたりどのような目的で行い、会社としての課題について当事者の気持ちになり、お客様に寄り添ってヒアリングを実施。また、リニューアル前ではレスポンシブ対応ではなかったため、SEO対策も兼ねてレスポンシブ対応を実現。CSS 設計では、SMACSS 手法を用いてCSSが保守・運用段階で破綻しないように設計を行う。デザイン面も昨今のモダンデザインを意識して作成し、お客様に満足して頂く。
