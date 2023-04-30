# lonelycosmo

https://guolam.sakura.ne.jp/cosmo/

## DEMO

  - デプロイしている場合はURLを記入（任意）API抜きでのDEPLOY方法、調べ中

## 紹介と使い方

  - コンセプト：距離を測る「光年」という単位は、光速で行っても１年かかるという遠い距離です。  そんな遠い星を今この肉眼で見る、天文写真で確認することはできるけど、  その星自体が存在しているかどうか確認しようがないほど、遠い存在である。そんな遠い星を追って、自分が何回目の誕生日の時の写真とか、その時に頭の上に浮かんだ星座などを確認すると、人間って遥かに短く間に生きると実感できるではないか。

  - 使い方:日付と時間を入力して、その時間の間にあるNASAの写真を取り出して、気に入ったものをFirebaseに保存する（保存まではできませんでした。）

## 工夫した点

  - 複数のAPIから値を取ることで、作動を分けて書くようにしました。

  - BINGのAPI（位置情報）＆NASA APIで作成

  - 色使いも私なりの世界観を表しています。


## 苦戦した点

  - それぞれのAPIの値の取り方が違って、documentationを読むのに必死でした。

  - 各APIの動かし方が違うのと、documentationの書き方がよく理解できず、思うように使えませんでした。

  - まさかカード関係で翻訳APIを使えず、遺憾です。

  - APIから取った値を別の階層、Firebaseへの移行はうまく行きませんでした。

  - 値の取得だけで、かなり苦戦しました。

## 参考にした web サイトなど

  - 星座API
  https://hoshimiru.docs.apiary.io/#introduction
  
  - NASA API
  https://ssd-api.jpl.nasa.gov/doc/horizons.html

  -天気アプリの作り方
  https://www.youtube.com/watch?v=MDENx86nK4k
  
  - 天文画像のAPI取得
  https://qiita.com/precs-higa/items/adafa61ae98b35f96384
  
  - YouTube Data API v3.0 + JavaScriptで動画検索
  https://qiita.com/akihiro1977/items/55e0007d3b85f9b95223
