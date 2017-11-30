# はじめに
３DのWeb地図ライブラリであるCesium。
これから始める人、より深く使いこなしたい人向けに、日本語の情報を収集してみました。

github(tkama/cesium_japanese_info)にも公開中。
変更・修正依頼が御座いましたらqiitaのフォームやPull requestsを送って下さい。

Qiitaには関連する２つのタグが登録されています
 - cesium : https://qiita.com/tags/cesium
 - CZML : https://qiita.com/tags/czml

# 導入・チュートリアル

#### [Cesiumを使った開発の始め方]( https://qiita.com/rot/items/bf7434d299e58d4c5a2a)
 - @rot 様
 - Webサーバ（Node.js)の構築から導入について詳細な解説があります。

#### [Cesiumを動かしてみよう](https://www.slideshare.net/Ihizaki/cesium-63857910)
 - 北海道地図株式会社 様
 - 2016年7月8日 FOSS4G 2016 Hokkaido のハンズオンの資料です

#### [Cesium入門ハンズオン~kml読み込み~](http://sssslide.com/www.slideshare.net/sagara1020/cesiumkml)
 - [NPO法人 伊能社中](http://www.iknowshachu.org/) 西林 直哉 山内 啓之 様
 - FOSS4G TOKYO（2015）のハンズオン資料です
 
#### [WebGLを利用して3Dな地図を作成できるライブラリ「Cesium」](https://shimz.me/blog/cesium/2867)
 - @_shimizu 様
 - ライブラリの概要とサンプルコードがあります

#### [Cesium入門](http://pen.agbi.tsukuba.ac.jp/~torarimon/?Cesium%C6%FE%CC%E7)
 - [とらりもん(TRAns-laboratory REMOte sensing Network)](http://pen.agbi.tsukuba.ac.jp/~torarimon/) 様

#### [cesium.js リファレンス](https://qiita.com/ohisama@github/items/9b9788b3f62e709b6df3)
 - @ohisama@github 様

# サンプルコード/活用事例
## 事例紹介

####  [「ヒロシマ・アーカイブ」他，アーカイブズ・シリーズの技術（概要）](https://qiita.com/hwtnv/items/ee26b92429414543d3dc)
- @hwtnv 様

#### [nasa space apps challenge その２,4,6,7](https://qiita.com/ohisama@github/items/91f5f3666fd9a38361c6)
- @ohisama@github 様

## タイルデータ関連

#### [地理院タイルを用いたサイト構築サンプル集](http://maps.gsi.go.jp/development/sample.html#sample-cs)
- [github(gsi-cyberjapan/gsitiles-cesium)](https://github.com/gsi-cyberjapan/gsitiles-cesium/blob/gh-pages/index.html) 
- 国土交通 国土地理院 様

#### [Cesiumで地理院タイル（地図/DEM）を使うライブラリ作成しました。](https://qiita.com/kochizufan/items/b338ac856425c0fa925b)
 - @kochizufan 様 

#### [地理院タイル on Cesium](https://qiita.com/hwtnv/items/09428ac87ffb2ee8750a)
 - @hwtnv 様

## 3Dモデル描画
#### Cesium.js で3Dモデル表示してみるテスト 
 - その[１](http://jsdo.it/cx20/UKCJB),[１改](http://jsdo.it/cx20/8BJd),[２](http://jsdo.it/cx20/6x4K),[３](http://jsdo.it/cx20/szBJ),[4](http://jsdo.it/cx20/WAZQ),[5](http://jsdo.it/cx20/UK9I),[6](http://jsdo.it/cx20/OTgK),[7](http://jsdo.it/cx20/uCVF),[8](http://jsdo.it/cx20/Gtr7),[9](http://jsdo.it/cx20/oszd),[10](http://jsdo.it/cx20/OGzk),[11](http://jsdo.it/cx20/Mj2H),[12](http://jsdo.it/cx20/eXjf),[13](http://jsdo.it/cx20/06Sb),[14](http://jsdo.it/cx20/CXer),[15](http://jsdo.it/cx20/YL6v),[16](http://jsdo.it/cx20/Mp3v)
 - @cx20 様

#### [CesiumにMapboxのStyleを適用する](https://qiita.com/sekitaka_1214/items/41f5feab0d5af1282d50)
 - @sekitaka_1214 様

#### [エクセルに座標を入力するだけでCesiumのラインを引くツール(自己満)](https://qiita.com/nishi_bayashi/items/a01e884bd7e427165697)
 - @nishi_bayashi 様
 
#### [Cesiumで動的にオブジェクトを追加する（見せかけ）](https://qiita.com/code_monkey/items/e1a3f6c48cbda3fa0e72)
 - @code_monkey 様

#### [jsdoでヒートマップ](https://qiita.com/ohisama@github/items/4fb498363d46c8a4c4a9)
 - @ohisama@github 様 
 
## CZML関連

####  [CZML入門](https://gis-oer.github.io/gitbook/book/GIS%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E6%95%99%E6%9D%90/%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%8D%E3%83%83%E3%83%88%E3%81%AE%E6%B4%BB%E7%94%A8/CZML/CZML.html)
 - GIS Open Educational Resources WG 様

#### [CZML: Cesium Language](https://qiita.com/handygeospatial/items/93060c4c1a488f7aed99)
 - @handygeospatial 様

#### [czmlの概要](https://qiita.com/hawaii_hahaha/items/478188bdb2a128e0dfc0)
 - @hawaii_hahaha 様

#### [CZMLのUnitQuaternionの設定]()
 - @hawaii_hahaha 様

#### [unitQuaternionの自動設定](https://qiita.com/hawaii_hahaha/items/e0897d4dbafbf6a10410)
 - @hawaii_hahaha 様

#### [json2czmlを作った](https://qiita.com/hawaii_hahaha/items/bcc7885dbdaf61f08424)
 - [github (hideume/json2czml)](https://github.com/hideume/json2czml)
 - @hawaii_hahaha 様

## リアルタイム表示制御

#### [Cesiumを用いた3次元リアルタイムデータの可視化について](https://www.slideshare.net/makinux7/cesium3)
 - @wayama_ryousuke 様 

#### [cesiumでリアルタイム表示](https://qiita.com/hawaii_hahaha/items/a6f8b7881975808b5923)
 - @hawaii_hahaha 様

#### [sicket.ioでcesium](https://qiita.com/hawaii_hahaha/items/80d45460e2257c77aa10)
 - @hawaii_hahaha 様

# Cesiumを活用した日本語Webサイト
#### [台風リアルタイム・ウォッチャー](https://typhoon.mapping.jp/2014t08.html)
#### [ヒロシマ・アーカイブ](http://hiroshima.mapping.jp/index_jp.html)
 
