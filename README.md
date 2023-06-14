# 職務経歴書

公開職務経歴書です。

## スキルセット: ソフトウェア研究開発

大学・大学院の専門は分散並列処理。大学院修了以降もプライベートの時間や副業などで研究開発活動を継続。2021/09からはトヨタ自動車株式会社にてデータベース・ストリーム処理・秘密計算などの研究。
他、OSなど低レイヤなシステム全般が興味。コンピュータサイエンスに関する分野は一通り押さえている。

### 査読付国際学会発表

- **Sho Nakatani**, "Memory Efficient Stream Processing for IoT Devices," 2022 International Conference on Algorithms, Data Mining, and Information Technology (ADMIT), 2022, pp. 129-139, doi: 10.1109/ADMIT57209.2022.00029.
- Jun Nakashima, **Sho Nakatani**, and Kenjiro Taura. "Design and Implementation of a Customizable Work Stealing Scheduler." ROSS2013

### 国内学会発表

- **中谷翔**, "End-to-end 秘密計算ストリーム処理の構想", 第15回データ工学と情報マネジメントに関するフォーラム (DEIM2023)
- **中谷翔**, Ting Chen, 田浦健次朗, "ストリーミングデータを扱うワークフローの外部モジュールの扱いに着目した低遅延実行", SWoPP2013
- 中島潤, **中谷翔**, 田浦健次朗, "スケジューリング方針をカスタマイズ可能な軽量スレッド処理系の提案", SWoPP2012
- **中谷翔**, Ting Chen, 田浦健次朗, "ワークフローアプリケーション基盤としての並列DBの性能評価", SWoPP2012
- **中谷翔**, 中島潤, 田浦健次朗, 近山隆, "再帰的に生成したタスクに対するデータ局所性を考慮するスケジューラの実装と評価", 情報処理学会 第74回全国大会
(学生奨励賞，推奨卒業論文認定)

### 講演等

- [ET & IoT West 2022 招待講演 "IoT・車載機で動作するストリーム処理系SpringQLの紹介"](https://f2ff.jp/introduction/6498?event_id=et-west-2022) (2022)
- [Beam Summit 2023 "Developing (Experimental) Rust SDKs And A Beam Engine For IoT Devices"](https://beamsummit.org/sessions/2023/developing-experimental-rust-sdks-beam-engine-iot/) (2023)

### 表彰等

- [IPA未踏プロジェクト](https://www.ipa.go.jp/jinzai/mitou/2012/2012_1/gaiyou/s-3.html) (2012)
    - "High Performance SQLite": SQLiteに対し、適応的プリアロケーションとハッシュ値によるGROUP-BYの手法を適用し、2.8倍の高速化を達成。
- [ICTプログラミングコンテスト  DeNA賞](http://ictepc.jp/events/2011/110831_000113.php) (2012)
    - "DDDFS (Dynamically-Duplicate Distributed File System)": 冗長性・レイテンシ低下を意図した広域分散分散ファイルシステムの実装を2名で共同開発。

### その他発表等

- [Streaming Systems輪読会](https://read-streaming-systems.connpass.com/)主催。発表多数

### その他、アンオフィシャルな成果

- 業務委託として、[Anonify](https://layerx.co.jp/labs/product/anonify) の開発や、それを利用した新プロダクトのためのリサーチ業務に従事。Anonifyへの自身のコントリビューション状況は[こちら](https://github.com/LayerXcom/anonify/pulls?q=is%3Apr+author%3Alaysakura)。リサーチ業務では、HPCや大規模データ処理の知見を活かし、論文調査やプロダクト構想のための技術調査を行っている。
  - 関連技術: TEE (Intel SGX), 差分プライバシー, 仮名加工・匿名加工, 分散システム, Rust

- Immutable Schema という、「既存レコードを破壊せず成功するDDL・DML」をメイン機能として備えたRDBMS [apllodb](https://github.com/apllodb/apllodb) の開発を業務委託として行っている。学芸員などアナログデータを持つ主体がアジャイルに情報整理・データ整理するツールの基盤として。会社様と要件のすり合わせや、事業ロードマップの確認を密に行いつつ、設計・実装は1名で担当。詳細は上記リポジトリのREADMEを参照のこと。
  - 関連技術: RDBMS, 関係代数, Rust

- [serde-encrypt](https://github.com/laysakura/serde-encrypt) という、Rustの暗号・シリアライズライブラリを開発している。Rustでは serde というシリアライズライブラリが広く使用され、他言語と比べると多くのデータ構造がシリアライズ可能である。serde-encrypt は、serde でシリアライズ可能なデータ構造なら何でもシンプルに公開鍵・共通鍵暗号化できるものとして作成している。
  - 関連技術: 公開鍵暗号, 共通鍵暗号, シリアライゼーション, Rust

- [MySQLite: SQLiteデータベースを読み書きするMySQLストレージエンジン](http://laysakura.github.io/20140218-MySQLite/) というのを実装し、成果発表。
  - 関連技術: RDBMS, C

- [Linux のスケジューリング調査と超低優先度プロセスの実装](https://laysakura.github.io/archives/page/3/#:~:text=%E3%81%A6%E3%81%8A%E3%81%8D%E3%81%BE%E3%81%99%E3%80%82-,%E5%85%83PDF,-Linux%20Kernel)
  - 関連技術: OS, スケジューラ, Linux Kernel, C

- [真・SSEを使って8flops/clockを実現する](https://laysakura.github.io/2012/01/06/sse-8flops-clock/) という記事を書いた。SSEは（今はAVXに取って代わられた） x86_64 のSIMD命令セットだが、その理論性能である「単精度浮動小数での8flops/clock」の実現のためのノウハウ。
  - 関連技術: SIMD, 最適化, C, x86_64

- その他、以下の分野については定期的にトップカンファレンスの論文や仕様などチェックし、先端の知識を維持している。
  - RDBMS, NewSQL, 分散データストア

- また、以下の技術についてはフルスクラッチで実装した経験がある。
  - RDBMS, ストリーム処理系, OS, C(サブセット)言語コンパイラ, Python(サブセット)インタプリタ, CPU (FPGA x Verilogで、load/store, ALU程度の簡単な命令セットのもの)

- 研究色は薄いが、Webサーバサイドアプリケーションやその基盤の開発・運用の経験も豊富。
  - ソーシャルゲームのように高負荷・高頻度トランザクションのシステムの基幹部分を、インフラ層まで含めて高速・高信頼に作るための設計からリリースまでを行える。また、金融システムのように複雑なドメインに関しても、ドメインエキスパートと対話しながらモデリングし、それをクリーンアーキテクチャでコードに落とし込むことができる。更に、ソフトウェア開発に限らず、CI/CD基盤導入・改善やリリースフロー整備なども多数経験。
  - 関連技術: Scala, Ruby, Go, C++, DDD, Clean Architecture, GitHub Actions, CircleCI, TravisCI


## スキルセット: プロジェクトマネージメント

認定スクラムマスター資格保有。

プロジェクトメンバーが最大限力を発揮するためのプロジェクトゴール制定やプロジェクト進行（スクラムで言うところのスクラムイベントの活用）と、ソフトウェア工学に基づいた計画・見積もりに強み。また、これを再現性のある技法としてコーチングすることができる。

大規模なプロジェクトマネージメントは未経験で、プロジェクトメンバーが15名程度までの実績のみがある。

以下、プロジェクトマネージメントに関してコーチング可能なレベルに習熟している事項を記載。なお、これらはあくまでも「適用可能なツール」であって、これらを適用するかはプロジェクトや外界の状況次第で選択することを常とする。

- プロジェクトゴール制定
    - CSF
- プロジェクト進行
    - スクラム全般
- 見積り
    - 幅見積もり
    - SRSS法
- 計画
    - CCPM
    - Velocity計測

ある会社様にコーチングした際の資料: [開発プロセス・スケジューリング基礎](https://docs.google.com/document/d/1qo_CV2dmYtQbSdlE51hbtYOsBXQCy4vHLKpYfcapDqA)

## 職務経歴・学歴

複業先は特別に許可をとっていない限り非公開。本業の経歴を記載。

### [トヨタ自動車株式会社](https://www.toyota-tokyo.tech/) (2021/09 - )

#### コネクティッド先行開発部 / 主幹 / Principal Researcher (2021/09 - )

- 車載機〜クラウドにおける、データのセンサリングから分析までのデータフロー・データ基盤の研究開発
  - [SpringQL](https://github.com/SpringQL/SpringQL)のOSS開発(author)
  - Culvert (E2E秘密計算ストリーム処理) の研究
- コネクティッドカンパニーの先端技術戦略

### [株式会社Scalar](https://scalar-labs.com/) (2022/12 - )

- [ScalarDB](https://github.com/scalar-labs/scalardb/) の開発（業務委託）

### [Idein株式会社](https://idein.jp/) (2020/03 - 2021/08)

IoTデバイスへのソフトウェア遠隔インストールを実現するための研究開発を行う。

### 株式会社FOLIO (2016/07 - 2020/02)

- 事業内容：インターネット証券事業
- 資本金：91億2万1636円（2019年3月末時点）

#### 顧客基盤部部長 / バックエンドエンジニア (2019/09 - 2020/02)

部員最大9名のマネージメントと部門のロードマップ作成を行う。

顧客のサービスへのエントリ（口座開設）に関する箇所を管轄とするシステム基盤を担当する部門であり、金融庁などの行政機関の厳しい法令要件がある中、現実世界の顧客をシステムで集約・活用できるようにモデリングすることが重要。

部長としての仕事は3割程度で、残りはバックエンドシステム開発を行う。

#### 執行役員 / フィナンシャル・テクノロジー部部長 (2018/10 - 2019/08)

フィナンシャル・テクノロジー部（開発部門）部長。2019/05より兼執行役員。最大40名程度のエンジニアのマネージメントを行う。

経営とエンジニアリングを双方向につなぐ動きや、プロダクト開発に最適化した横断的な組織づくりに注力。

#### フィナンシャル・テクノロジー部プロジェクトマネージャー (2017/11 - 2018/11)

開発プロジェクトマネージメントを主に担当。

いわゆるプロジェクトマネージメントの動き（ステークホルダーと協調し、開発内容を明らかにする / 開発計画を立案）と、スクラムマスターとしての動き（開発チームの自律的な活動を支援）を半々で行う。

見積り, 制約理論, CCPMなど、ソフトウェア工学の知見を用いて、再現性のあるプロジェクト運営を心がける。プロジェクトのゴールを達成することのみならず、開発チームの成長を重視している。

#### フィナンシャル・テクノロジー部バックエンドエンジニア (2016/07 - 2017/11)

マーケットデータ（株価・ファンダメンタルズ）を取得/配信するサービスの開発や、証券システムの裏方の設計・開発。

ソーシャルゲームと比べて法整備などが厳格なことから、実世界をモデリングしてプログラムに落とし込むことの重要性を学び、DDDを身につける。

スキマ時間にチームの開発を加速させるためのフロー整備やツール整備を実施。


### 株式会社ディー・エヌ・エー (2014/04 - 2016/07)

- 事業内容: ソーシャルゲーム事業、インターネットサービス事業等
- 資本金：103億97百万円 (2015年度)

#### ジャパンリージョンゲーム本部　技術部　ソーシャルゲームタイトルチーム (2016/05 - 2016/07)

月間10億円規模の売上を持つアプリの運用・業務フロー改善担当。チーム全体で100人規模となっておりコミュニケーションコストの増大などの弊害が生まれているが、業務フローを改善することでチームの人数を削減してより低コストな運用ができるよう素地づくりを行う。

#### ジャパンリージョンゲーム本部　開発基盤部　次世代mBaaS開発チーム (2015/11 - 2016/04)

ソーシャルゲームの汎用開発基盤Sakasho (下記参照) の運用が本格化し、顕在化した各種の問題を解消するため、Sakashoの流れを汲む次世代mBaaSの開発チームが立ち上がり、そのチームの初期メンバーとして参画。

##### プロキシの再設計・実装

Sakashoのプロキシはセッション確立などDBアクセスを伴う処理を多く行っており、プロキシをスケールアウトさせるためにはDBサーバの増築も行う必要があった。一方でプロキシでは通信暗号化を行っていてCPU負荷も高いため、スケールアウトは必須だった。次世代mBaaSのプロキシでは、通信暗号化と圧縮のみを行うこととし、DBアクセスを排除してスケールアウトが容易な構成を実現。

##### 通信暗号/圧縮の設計・実装

上述の通り、次世代mBaaSのプロキシは暗号化と圧縮処理を行う。Sakashoでは通信路での圧縮は行っていなかったが、ゲームのステージ内情報などの大きなデータをアプリで取得する際にネットワークボトルネックになることが観測されていたため、次世代mBaaSではプロキシとSDKの間で圧縮処理を行うこととした。圧縮方式の選定の際は実データを用いていくつかの圧縮アルゴリズムのベンチマークを取り、特にモバイル端末でのCPU消費とメモリ消費を考慮に入れた。

暗号化についてだが、複数のアプリが1つの共通サーバサイド基盤に対して通信を行うため、この通信路が盗聴されると複数のアプリに対するビジネス上の脅威になる。Sakashoでは社内のセキュリティ部署からいくつか攻撃のリスクが提示されていたため、次世代mBaaSでは暗号方式を刷新し、暗号強度を高めた。アプリのバイナリ解析により暗号方式が露呈するのはリスクとし、独自の暗号方式を作成することが要件であった。設計・実装を2日程度でクイックに行い、セキュリティ部署の脆弱性診断をパスした。また、Sakashoでは暗号処理をRubyで行っておりCPU負荷が非常に高かったが、次世代mBaaSでは暗号処理・復号処理をC++で実装し、大きな速度向上に成功。

##### 各種共通機能の設計・開発

#### ジャパンリージョンゲーム本部　開発基盤部　Sakashoチーム (2014/04 - 2015/10)

ソーシャルゲームモバイルアプリが共通に使うサーバサイド機能を提供する [Sakasho](http://www.slideshare.net/blueskyblue/de-na-game-backend-as-a-service-20150129) の開発・運用

##### ・ランキング機能など、各種機能の設計・開発

ソーシャルゲームアプリ市場調査による要件定義、設計、開発までを一括して行った。ビジネス上クリティカルである課金機能のサーバサイド設計、開発も担当。

##### アプリ開発者が各機能を利用設定するためのWebインターフェイスの開発

ランキング機能を例に取ると、バトル時のスコアやクリア時間などの多様なランキングが利用される。それらをアプリに応じて自由に設定できるためのWebインターフェイスを提供。

##### C++ SDK, Java SDKの開発

##### Sakashoを使ったアプリの運用
日頃パフォーマンスレポートを注視し、高負荷の原因になっている箇所を特定し、いち早く修正を加えた。特に、Sakasho利用アプリとして本格的に売上を見込んでいる初のアプリがリリースされた際にユーザが一気に流入してプレイ開始に支障をきたす事案が発生した際には、短時間で原因の特定をし修正を加えることに成功した。

##### 業務フロー改善
Sakashoでは隔週のリリース毎に利用者にリリースノートを配布したが、その作成にはチームリーダーが半日を要していた。また、それでもリリース内に行った作業をリリースノートに漏らしてしまうことが時折起こっていた。その問題を発見し、チーム内のタスク管理ツールからリリースノートのPDFを自動生成する仕組みを作成し、チームリーダーの業務フロー改善並びにユーザへ提供する情報の精度向上に貢献した。その他にも、Slackによるチャットデプロイの導入などを行った。

#### 機械学習を各種事業領域に活用するプロジェクト (2015/10 - 2016/05)

機械学習（特に深層学習）を各種事業領域に活用するための少人数プロジェクトに参画。主にジャパンリージョンゲーム本部への活用を担当し、ソーシャルゲームのプレイログを活用したユーザ運用改善の立案と、機械学習そのものが楽しさの核であるようなゲームのPoC開発を行った。

#### ジャパンリージョンゲーム本部　開発基盤部　社内・協力会社へのアプリ配信基盤開発チーム (2014/08 - 2016/07)

リリース前のアプリはApple StoreやGoogle Playで公開配信することはできない。一方、アプリはWebからダウンロード・インストールできる形にしておかなければ、QAや実機確認を行う多数の端末で一々USBケーブルを繋いでインストールせねばならず、大変な時間的コストとなる。それを解決するため、 [DeployGate](https://deploygate.com) のようなアプリ配信基盤Webサービスを社内で開発・運用してた。DeployGateとは異なり、iOSアプリのインストールに必須である署名も全てサーバサイドで透過的に行えるシステムになっていて、iOSアプリのインストールの時短に貢献。2015年10月からチームリーダー。


### 東京大学 (2008/04 - 2014/03)

#### 修士課程: 情報理工学系研究科 電子情報学専攻 田浦研究室 (2012/04 - 2014/03)
#### 工学部電気電子工学科 田浦研究室 (2011/04 - 2012/03)
#### 工学部電気電子工学科 (2010/04 - 2012/03)
#### 理科I類 (2008/04 - 2010/03)

## 保有資格

- 認定スクラムマスター
- 証券外務員一種・二種
- 統計検定2級

## 各種ID

| サービス | URL                                |
|----------|------------------------------------|
| ブログ   | https://laysakura.github.io        |
| GitHub   | https://github.com/laysakura       |
| Twitter  | https://twitter.com/laysakura      |
| Booklog  | https://booklog.jp/users/laysakura |

## 連絡先

中谷 翔 <lay.sakura@gmail.com>

その他各種SNSでのご連絡でもOKです。
