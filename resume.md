# 職務経歴書
<div style="text-align:right;color:#999999">2020年5月25日</div>

## プロフィール
---
* 氏名：中村　優吾
* Mail：alice7mm.harusakura@gmail.com

<br>

## 職務経歴概要
---
- 株式会社グリフォン(2020/12 ~ ) ※副業
- 虎の穴ラボ株式会社(2020/08 ~ )
- 富士ソフト株式会社(2017/04 ~ 2020/07)

バックエンド、フロントエンド、インフラにとらわれずフルスタックでの開発を行っており、現在はNext.js、Kotlin(ktor)を用いたWebアプリケーションのフルスクラッチ開発案件に従事しています。  
技術スタックは、Javascript, Typescript, Javaを中心に幅広く案件に適した柔軟な開発ができるよう経験を積んでいます。  
副業経験もあり、GCP上でのKubernetesインフラ構築・整備を行うSREの立場としてサポートをしています。  

<div style="page-break-before:always"></div>

## スキル
---
### フロントエンド(HTML/CSS/Javascript)
#### Javascriptフレームワーク
* Next.js：半年
* Vue.js：半年
* Angular7：1年
* AngularJS(1.6)：1年
#### CSSフレームワーク
* Tailwind：半年
* Bootstrap：2年
#### CSSプリプロセッサ
* Sass：2年
* Less：1年
#### テスト
* jest：半年
* Selenium Webdriver：1年
### サーバサイド
* Node.js: 3年以上
* Java：3年以上
  * JSP：1年
  * Thymeleaf：2年
* Kotlin：1年
  * サーバサイドKotlinでWEBアプリケーションの開発を行っています。
* C#：半年
  * Webサーバ開発
  * ネイティブアプリ開発
* C/C++：半年
* Python：数ヶ月程度
### データベース
* PostgreSQL：3年
* Oracle：2年

<div style="page-break-before:always"></div>

### その他
#### クラウドコンピューティング
* AWS：2年
* GCP：2年
#### コンテナ
* Docker：3年以上
* Kubernetes：2年
#### WEBサーバ
* Tomcat：2年
* Nginx：2年
#### CI/CD
* Jenkins：3年以上
* Code Pipeline, Code Build, Code Deploy：半年
* GitHub Actions：1年
#### VCS
* Git：5年以上
* GitHub：3年以上
* Subversion：2年

<div style="page-break-before:always"></div>

## 職務経歴
---
### ユーザ用管理ポータルサイトのリプレイス
* 開発期間  
2022年12月〜

* 開発規模  
人数：計6名（スクラムマスター、開発メンバー4名、SRE1名）  
担当：開発メンバー  

* 開発環境  
フロントエンド：React、Next.js、TailwindCSS  
BFF：Node.js
サーバサイド：Kotlin
データベース：Oracle  
VCS：GitHub  
インフラ：AWS(ECS)  
CI/CD：GitHub Actions、CodePipeline、CodeBuild、CodeDeploy

* 開発内容  
他社で開発・保守されていたユーザ用管理ポータルサイトを自社管理にするためのリプレイスプロジェクト  
オンプレ・PerlからAWS・Next.js・Kotlinへの移行のため、フルスクラッチでの開発  
アプリケーション開発からCI/CD環境の整備までフルスタックで開発を行っています。  
---
### Kubernetesインフラの整備
* 開発期間  
2020年12月〜

* 開発規模  
人数：計5名  

* 開発環境  
実行環境：Google Kubernetes Engine  
VCS：GitHub  
インフラ：GCP  
CI/CD：GitHub Actions、Terraform / Terraform Cloud  
ミドルウェア
  * GitOpsCDツール：flux
  * ワークフローエンジン：argo-workflow
  * 証明書管理：cert-manager
  * 設定構成管理：config-sync
  * データ解析：datadog
  * ロギング：fluentbit  

* 開発内容
SREのサポートメンバーとして参画  
AWSで動作していたアプリケーションをKubernetesインフラに移行するための、Kubernetesインフラの構築・整備を実施  
cert-managerの導入やロギング周りの設計、構築  
現在は移行完了したため、ミドルウェアのバージョン管理等を担当  
---
### 自社通販サイトの開発・運用
* 開発期間  
2020年9月〜2022年11月

* 開発規模  
人数：計11名（スクラムマスター、フロントチーム3名、サーバチーム7名）  
担当：メンバー（サーバチーム）  

* 開発環境  
対象OS：Linux  
フロントエンド：Thymeleaf、Javascript  
サーバサイド：Java  
Webサーバ：tomcat、nginx  
データベース：Oracle、PostgreSQL  
VCS：GitHub  
その他：AWS(EC2)、Jenkins

* 開発内容  
年間売上100億円を超える自社ECサイトの保守・開発  
売上向上を狙うための新機能開発を主に担当。  
主な開発実績  
  * ポイント値引き機能
  * 作者関連作品のレコメンド機能
  * 外部サイト埋め込み用ウィジェットの開発　等
---
### 社内図書貸出管理ツールの開発（研修）
* 開発期間  
2020年8月

* 開発規模  
自分のみ

* 開発環境  
対象OS：Linux  
フロントエンド：Thymeleaf
サーバサイド：Kotlin、Ktor  
Webサーバ：tomcat、nginx  
データベース：PostgreSQL  
VCS：GitHub  
その他：AWS(EC2)、Jenkins

* 開発内容  
スプレッドシートで行っていた社内図書の貸出情報をWEBアプリケーション化  
入社時研修課題として一人で開発  
---
### 研削盤向けIoTWebアプリケーション開発
* 開発期間  
2020年3月〜2020年7月

* 開発規模  
人数：3名  
担当：リーダー

* 開発環境  
対象OS：Linux(Docker、Ubuntu 18.04)  
フロントエンド：Vue.js、Vuetify、Sass  
サーバサイド：C#、ASP.NET Core  
データベース：PostgreSQL  
VCS：GitBucket  
その他：Docker  


* 開発内容  
お客様が開発している工作機械のデータを収集し、グラフィカルにデータを表示するWebアプリケーションの開発。  
---
### IoTプラットフォームのリプレイス設計
* 開発期間  
2020年1月〜2020年2月  

* 開発規模  
人数：15名  
担当：メンバー  

* 開発内容  
工作機械のデータ収集、サードパーティアプリベンダーのアプリケーション配布を行うIoTプラットフォームの問題提起と再設計。
---

<div style="page-break-before:always"></div>

### PLCレジスタ設定アプリケーション開発
* 開発期間  
2019年10月〜2019年12月  

* 開発規模  
人数：4名  
担当：見積もり作成、メンバー  

* 開発環境  
対象OS：Windows 10（Windowsフォームアプリケーション）  
開発言語：C#、.NET Framework、PLCラダー  
VCS：Git  
その他：Gx Works3  

* 開発内容  
三菱製のシーケンサ(PLC)という機械のレジスタ情報を三菱独自のプロトコルを用いた通信でリアルタイムに取得し、画面に表示、また画面から編集し保存するアプリケーションの開発。
---
### 工場火災監視システム WebAPI開発
* 開発期間  
2019年7月〜2019年9月  

* 開発規模  
人数：2名  
担当：メンバー  

* 開発環境  
対象OS：Windows 10  
開発言語：C#、ASP.NET  
Webサーバ：IIS  
VCS：Git  

* 開発内容  
お客様の開発するシステムから呼び出されるWebAPIの開発。
---

<div style="page-break-before:always"></div>

### 工作機械向けグラフ表示アプリケーション開発
* 開発期間  
2019年6月〜2019年7月  

* 開発規模  
人数：2名  
担当：リーダー  

* 開発環境  
対象OS：Windows Embedded Compact 7(以下、Windows CE)(Windowsフォームアプリケーション)  
開発言語：C#、.NET Compact Framework  
VCS：Git  

* 開発内容  
工作機械に搭載されているWindows CE上で動作し、データをCSVファイルに出力、CSVファイルをグラフに描画し表示するフォームアプリケーションの開発。
---
### レーザー加工機向けIoTWebアプリケーション開発
* 開発期間  
2019年3月〜2019年5月  

* 開発規模  
人数：2名  
担当：メンバー  

* 開発環境  
対象OS：Windows 10  
フロントエンド：Angular7、Bootstrap3、chart.js、canvasJS  
サーバサイド：Node.js(Express)  
データベース：PostgreSQL  
VCS：Git

* 開発内容  
レーザー加工機のデータを収集しているPostgreSQLのデータを監視し画面にグラフィカルに表示、データがリアルタイムに更新されるWebアプリケーションの開発。
---

<div style="page-break-before:always"></div>

### 新人教育カリキュラムの作成
* 期間  
2019年1月〜2019年2月  

* 規模  
新人：6名（内訳：プログラミング経験者1名、未経験5名）  
メンター：6名  
自分の担当：目標設定、カリキュラムの作成、教育進行の管理  

* 内容  
新人6名に基本的なコーディングスキル（読み書き、調べ方、デバッグ）や、お客様の業界知識を教育し、プロジェクトにアサインできる人材となれるようなカリキュラムを作成した。
---
### ビルドサーバの移植
* 開発期間  
2018年10月〜2018年12月  

* 開発規模  
人数：6名  
担当：メンバー  

* 開発環境  
対象OS：Windows Server 2016、Ubuntu16.04  
VCS：VSS、Subversion → Microsoft Team Foundation Server（Git）  

* 開発内容  
お客様チーム内で使用しているビルドサーバの性能改善のための移植。  
また、チーム内で開発している複数のアプリケーションで、共通で使用するライブラリを別々のリポジトリで管理していたため、マージ時に大量のコンフリクトが発生する問題を解決すべく、VCSをGitに変更、リポジトリ構成の再設計、ブランチモデルの検討を行った。  
---

<div style="page-break-before:always"></div>

### Windows CE版CNCシミュレータ開発
* 開発期間  
2018年6月〜2018年9月  

* 開発規模  
人数：4名  
担当：メンバー  

* 開発環境  
対象OS：Windows CE  
開発言語：C/C++  
VCS：Subversion  

* 開発内容  
CNCの機械構成データとプログラムを読み取り結果を計算するシミュレータのエンジンアプリをWindows CE上で動作させるための移植とチューニング。GUI部分はお客様が開発。
---
### Webアプリ版CNCシミュレータフロントエンド開発
* 開発期間  
2017年6月〜2018年5月  

* 開発規模  
人数：5名  
担当：メンバー  

* 開発環境  
対象OS：Linux(Docker、Ubuntu16.04)  
フロントエンド：AngularJS 1.6、Bootstrap3、jQuery、JSP  
サーバサイド：nginx、Node.js(Express)、Spring  
データベース：MongoDB  
VCS：Subversion  
その他：Docker、Jenkins、Selenium WebDriver  

* 開発内容  
CNCの機械構成データとプログラムを読み取り結果を計算するシミュレータのWebアプリ開発。  
Nginxでリバースプロキシを構築し、自社で開発したNode.jsのアプリと他社が開発したJavaのアプリを結合。Javaで開発されたアプリは、途中で引き継ぎ保守を行った。  
シミュレーションを行うエンジンアプリは他チームで開発。

