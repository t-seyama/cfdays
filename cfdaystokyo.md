# Making the Cloud Business Ready - Chip Childers(CTO, Cloud Foundry Foundation)
* ソフトウェア開発の重要性
* Cloud Foundryの意義
** 継続的イノベーションをエンタープライズにもたらす

# Everyday life with CF in a big Organization - Carlo Alberto Ferraris, Ronak Banka (Rakuten)
* Cloud Foundryの社内利用話
* どのようにCloud Foundryを組織で利用してもらうか
** APIとプラグインを開発し、ユーザー利用の敷居を下げる
** 各チームにCloud Foundryに詳しいプロダクトマネージャーを配置

# Data Service Patterns for Cloud Foundry - JULIAN FISCHER (CEO, ANYNINES)
* データベースなどCFサービス提供話
* どのようにクラウドサービスに期待する要素を満たし、サービスを提供するか
** 自動化
*** BOSHを用いて、CloudFoundryとの親和性、インフラの非依存性をあげる
** 堅牢性
*** cf create service毎に仮想マシンを作ることによって隔離を実現する
** 自己回復
*** BOSHによって仮想マシンレベルで回復可能
**  拡張性
*** BOSH
** オンデマンド
*** BOSH

# Circle of Code - Tomohiro Ichimura, Gwenn Etourneau (Pivotal)
* Circle of Code
** アイディア/プラン => Pivotal Tracker
** コーディング => Spring
** CI => Concource 
** インフラ => Cloud Foundry
** メトリクスの取得 => Pivotal metrics 
* Pivotal Labsの取り組み
* Concource CI TOKYO イベントの告知

# Routeサービスを使ったCloud FoundryアプリのAPI管理Using CF Route Service to Publish, Secure, Monitor APIs - Kazuchika Sekiya(Apigee)
*APIGWのCloud Foundryサービス
** route-serviceを用いる
** IBMとPivotalのマーケットプレイスで利用可能

# Cloud Nativeと企業向けプラットフォーム "Enterprise Cloud - Cloud Foundry"Cloud Native and Enterprise oriented platform "Enterprise Cloud - Cloud Foundry" - Ayaka Furuta (NTT Communications Corporation)
* TCPルーティングの所が抜けている

# 富士通のCloud Foundryへの取り組み～Cloud Foundry構築・運用裏話～The inside story about how Fujitsu tackles Cloud Foundry with conventional mission critical oriented mind - Toshio Takeda, Tsuyoshi Nagai(FUJITSU LIMITED) / Dies Koper(Fujitsu Australia Software Technology)
* aaa 

# Cloud Foundryに関する日本国内コミュニティについてAbout Cloud Foundry community in Japan - Ken Ojiri (Chairperson, Japan Cloud Foundry Group / NTT)
* 日本Cloud Foundryグループのかつどうについて

# DEAがサポートされなくなると聞いてDiego についてちょっとまとめてみたOverview of Diego because of DEA End of Life plan announcement - Takehiko Amano(Board member, Japan Cloud Foundry Group.)
* DEAとDiegoの違い

# Cloud Foundry as Containerized Services -   @jyoshise
* Dockerイメージを用いたCloud Foundryの構築
** Fissibleの利用 (bosh-releaseをDocker imageに変換)
** 利点: デプロイが容易
** 欠点: Docker Imageの作成が難しい and そのクオリティに左右される。トラブルシュートのノウハウが少ない。

# Yahoo! JAPANのCloud Foundry導入状況How Yahoo Japan Corporation is using Cloud Foundry - Yasuhiko Kubono(Yahoo Japan Corporation)
* 社内利用話
** アプローチや苦労したところは楽天と類似
** CIはConcourceを利用
