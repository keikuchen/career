# クラウドプラットフォーム上でのバッチ処理開発
AWS Step Functionsを用いたバッチ処理の開発
## 期間
2021年03月 〜 2021年03月 (1ヶ月)
## 業務内容
AWS上で構築されたバッチ処理群の追加開発を担当。
設計から試験までを一貫して実施。

### 本案件の背景
日々更新される様々なデータ(天気データ、電力データ等)をAWS環境下で効率的に収集し活用可能な状態にするバッチ処理の開発が求められていた。

### 開発の概要
特定のWebサイト等からデータを定期的に取得して、活用しやすい形に加工してクラウドストレージにアップロードする処理の開発を行った。

### 担当した機能
* 特定のWebサイトからのスクレイピング
* データ編集ロジック
* クラウドストレージへのアップロード
* インフラ構築の設定ファイル作成

### 担当業務
* 開発（設計、実装、テスト）

### 使用した技術
* AWS(CodeBuild, CloudFormation, Step Functions, Lambda, Batch, Glue, Athena, S3, DynamoDB)
* Python(pandas, dask)
* Git, GitHub, VSCode

### 習得した技術
* boto3を用いたS3の操作
* CodeBuildによるStep Functions等のデプロイ
* CloudFormation設定ファイルの作成
* Step Functionsの構築
* PythonによるLambda関数の実装
* daskを用いた大容量データの編集
* Git及びGitHubを用いた開発(リポジトリのFork〜ローカル作業〜自分のリモートリポジトリへのPush〜Pull Request作成)

### チーム構成
プロジェクト人数：3名
* リーダー：40代・ベテラン
* 開発メンバー1：本人・実務歴3年
* 開発メンバー2：20代・実務歴1年

### メンバーとしての振る舞い
メンバー各人がそれぞれ別のバッチ処理開発を行うスタイルで実施。
自分のみAWS周りの経験が不足していたため、もう1人の開発メンバーにサポートをもらいつつキャッチアップを実施。
一方でPythonの経験は比較的豊富だったため、コーディング周りで積極的にメンバーの相談に乗って開発を進めた。



# HCMシステムとのデータ連携基盤開発
連携処理資材作成ツールスクラッチ開発
## 期間
2020年11月 〜 2021年02月 (4ヶ月)
## 業務内容
システム間の連携処理の資材を生成するCLIツールの開発を担当。
設計から単体テストまでを実施。
前半1ヶ月はアジャイル、後半はウォーターフォールで開発を実施。

### 本案件の背景
ETLツールで構築しているデータ連携基盤について、連携するIFを300ファイル程度追加することとなった。
今回は追加するIFの仕組みが単純であることから生産性の向上を目的として、本来ETLツールで作成する連携処理の資材(XMLファイル)をCLIツールを使ってテーブル定義書から一括生成することが提案された。

### 開発の概要
テーブル定義書(Excelファイル)を読み込み、定義値によって異なる編集処理を加え、ETLツールに取り込み可能なフォーマットのXMLファイルを出力する。

### 担当した機能
* Excelファイル読み込み
* データ編集ロジック
* XMLファイル書き出し

### 担当業務
* 開発（設計、実装、単体テスト）
* PowerCenterに取り込み可能なXMLファイルの仕様調査

### 使用した技術
Python(pandas, ElementTree), PyCharm, Sphinx, Git

### 習得した技術
* pandasを用いたデータ分析、表データの入出力
* ElementTreeを用いたXML形式データの処理
* Sphinxを用いたドキュメント作成

### チーム構成
プロジェクト人数：11名
CLIツール開発チーム：3名
* リーダー：20代・有識者
* 開発メンバー1：本人・実務歴3年
* 開発メンバー2：20代・実務歴1年

### メンバーとしての振る舞い
Pythonの実務的な開発経験を持つのが自分のみであったため、開発環境の構築方法や実装方針の策定を率先して実施。
開発メンバー全員が主体的に成長できるよう、PMと交渉しながら開発担当の配分を調整。



# 地方自治体向け申請情報管理システム開発
パッケージを用いたウォーターフォールでの開発
## 期間
2019年01月 〜 2020年04月 (1年4ヶ月)
## 業務内容
### 本案件の背景
地方自治体の某申請情報管理システムについて、紙申請(窓口受領した申請書の情報を手動登録するパターン)のみの取扱いであった従来システムに代わり、電子申請(他システムと連携して自動で情報が登録されるパターン)にも対応した新システムの導入が全国的に推し進められていた。そこで、その自治体においても導入が決定したため開発を行った。

### 担当業務
* 全体のスケジュール管理
* お客様、協力会社等との調整
* 要件定義、総合テスト

### チーム構成
13名
* リーダー：50代・ベテラン
* サブリーダー：60代・ベテラン
* メンバー：本人・実務歴2年
* ＋各ソフト/ハードウェアベンダ10名

### 詳細・主な取り組み
各ソフト/ハードウェアベンダや、システムの連携先外部機関等、最大10団体と並行して連絡を取りながらプロジェクトを進行。
対面や電話のやり取りに当たっては、議事録や要約メールを用いて確認を欠かさず行い、認識齟齬による手戻りの発生を防止。



# 地方自治体向け業務システム新規提案
地方自治体の業務効率化のためのソリューション提案活動
## 期間
2018年04月 〜 2020年04月 (2年1ヶ月)
## 業務内容
### 本案件の背景
デジタル・ガバメントの推進が求められている中で、各地方自治体もその対応を検討する必要性を抱えている。そこで、現業務状況を踏まえた上での適切なソリューション提案を民間から主体的に行っていくことで、新規案件創出に繋げていくことが計画された。

### 担当業務
デモンストレーションに活用するためのプロトタイプの作成
* ドローンを操作するデスクトップアプリ
* 写真管理アプリ(Androidアプリ+Webアプリ)
* 某申請情報管理Webアプリのモック

### 使用した技術
Python(wxPython, Tkinter, Numpy, OpenCV), PyCharm, Kotlin, PHP, Git, Docker

### 習得した技術
* wxPythonを用いたデスクトップアプリの作成
* Kotlinを用いたAndroidアプリの作成(写真撮影、マップ連携、サーバ連携)
* Linuxサーバの構築

### チーム構成
3名
* 営業メンバー1：40代・ベテラン
* 営業メンバー2：40代・ベテラン
* 開発メンバー：本人・実務歴2年

### 詳細・主な取り組み
提案用のサンプルの開発という特性上、綿密な作り込みではなく、最小限の機能を短期間で作り上げることが求められた。そこで、目的に応じた適切な技術の選定、優先度の検討・取捨選択を通して効率的な開発を心がけた。



# 地方自治体向け申請情報管理システム保守
Webシステムの保守
## 期間
2018年04月 〜 2019年01月 (10ヶ月)
## 業務内容
### 本案件の背景
地方自治体向け申請情報管理システムを導入している全国40余りの団体からの質問・不具合等の問い合わせに的確に対応するため、本システム専門の問い合わせ窓口が設置された。

### 担当業務
* システムに関する質問・不具合等の問い合わせ対応(電話対応・試験環境での検証・駆け付け対応)
* 問い合わせ情報を蓄積・管理するためのDB作成

### 習得した技術
Access VBAによる開発(データ登録、タグ付け、検索)

### チーム構成
3名
* メンバー1：20代・有識者
* メンバー2：20代・有識者
* メンバー3：本人・実務歴1年

### 詳細・主な取り組み
自分を除くメンバー2名は同システムの開発業務を経験した直後であったため、システムに対する知識量に大きな差がある状態での開始となった。
そこで、開始1ヶ月は先輩方の問い合わせ対応方法を徹底的に見て聞いて覚え、翌月からは全ての問い合わせを受ける(電話を取る)覚悟で取り組み、知識の差を素早く埋めることに努めた。



# 大手旅行会社のデータ連携基盤開発
ウォーターフォールによる連携基盤開発
## 期間
2017年10月 〜 2018年03月 (6ヶ月)
## 業務内容
### 本案件の背景
DWHに蓄積した旅行予約データ等を経営上の意思決定に活用するため、データ連携基盤システムの開発が提案された。

### 開発機能の概要
ETLツールを用いて複数テーブルの情報を組み合わせ、BIツールで利用可能な形式に加工する。

### 担当業務
基本設計(テーブル定義書・データフロー図等)、詳細設計(ビュー定義書等)、実装、単体テスト、結合テスト

### 使用した技術
AWS(Workspaces, Redshift), Talend, Java

### 習得した技術
* Redshiftにおけるテーブル、ビューの設計
* Talendを利用したETLロジックの製造

### チーム構成
プロジェクト人数：7名
* PM：40代・ベテラン
* メンバー1：30代・有識者
* メンバー2：30代・実務歴10年
* メンバー3：20代・実務歴7年
* メンバー4：20代・実務歴6年
* メンバー5：20代・実務歴3年
* メンバー6：本人・実務歴3ヶ月

### 詳細・主な取り組み
本プロジェクトは、お客様自身の持つ完成イメージが定まらないまま開発が始動し、曖昧な要件定義を基に基本設計を行う必要があった。
そこで、必要に応じて定例の打ち合わせ外でもお客様へのヒアリングを実施することで、軌道修正を細かく繰り返すことを心がけた。
その結果、手戻りの発生も小規模なものに抑えられ、予定通りのリリースを行うことができた。



# 大手旅行会社のWebシステム改修
ウォーターフォールでの機能追加開発
## 期間
2017年07月 〜 2017年09月 (3ヶ月)
## 業務内容
### 本案件の背景
旅行予約サイトの利用者から電話問い合わせを受けるにあたり、コールセンターでは負荷が特定のオペレータに集中しない工夫が求められる。
そこで、Webサイトからの要求時点での状況に応じて、動的に問い合わせ先番号を表示させる機能の開発が提案された。

### 開発機能の概要
Webサイト上の問い合わせボタン押下をトリガーにコールセンター側システムへの状況照会を行い、最適な電話番号情報を取得して画面に表示する。

### 開発を担当した機能
* 画面(問い合わせボタン、照会結果画面)
* モーダルダイアログ表示ロジック

### 担当業務
画面設計、実装、単体テスト

### 使用した技術
ASP.NET(JavaScript, JQuery, C#)

### 習得した技術
* ASP.NETを利用したWebシステム開発
* JQueryによるダイアログ表示ロジック開発

### チーム人数
3名
* メンバー1：30代・実務歴10年
* メンバー2：20代・実務歴6年
* メンバー3：本人・実務歴0年

### メンバーとしての振る舞い
メンバー内では最も実務歴が浅いながらも、先輩方の配慮もあり、実装から単体テストまでを全面的に担当。
実装方法の調査、進捗状況の報告、課題発生時のエスカレーション等を実施。
