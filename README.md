■サービス概要

バスケの自主練記録を残せるアプリです。
練習メニューもランダムで選んでくれることができ、
また近くのバスケットボールができる場所を検索できます。


■ このサービスへの思い・作りたい理由

私は中学から現在までバスケをしています。
その中で一人だと自主練しにいくのを躊躇ってしまう時がありました。
さらに自宅から遠いコートとかだと尚更行くのが大変な時がありました。
原因として一人だとモチベーションが続かない、単調な練習になってしまうからと考えられました。

そのためこのアプリを使用し、改善できる点を考えました。
モチベーションが続かない→記録を残し自身の頑張り具合が把握できる
単調な練習になる→練習メニューを選択し、（例：ドリブル、シュート等）ランダムで提案してくれることで新鮮味のある状態にしてくれる

ただ記録をつけるだけだとどうしても飽きが来てしまうと思います。
そのため週何回以上行ければトップページを違うデザインにする、労いのメッセージを表示するなど考えています。


■ ユーザー層について

バスケを行うユーザーでも、特に初心者に向けて考えています。
初心者は練習などが習慣付いていないと思うので習慣づけが大切かなと思いました。
https://www.basketballtutor.com/news/20083/


■サービスの利用イメージ

・その日行ったトレーニングの記録をつけていきます。
・Open AI APIを使用し、おすすめのトレーニングを提案してもらうことができいます。
・現在地情報を取得し、近くのバスケットボールコートを探せます。
  またカテゴリー機能で条件に当てはったコートも探せます。
・タグ機能でコート近くに自販機やお手洗いがあるかをある程度確認できます。


■ ユーザーの獲得について

Xを使っての拡散
友人に使ってもらい宣伝する


■ サービスの差別化ポイント・推しポイント

https://apps.apple.com/jp/app/homecourt-basketball-training/id1258520424?platform=iphone
Home CourtというARを使った練習メニューがあるアプリがありました。
こちらとの差別化として上記のアプリにないコートを探せる機能、
また練習メニューを提案してもらえる機能を追加したいと思いました。


■ 機能候補

MVPリリース時
・会員登録
・ログイン
・パスワードリセット機能
・検索機能
・プロフィール編集機能
・Xの投稿機能
・現在地の取得(Google Geolocation API)
・場所の取得(Google Places API)、


本リリース時
・タグ機能
・自身のお気に入りコートの登録機能
・カテゴリー機能
・オートコンプリート機能
・コートの登録機能(地図上に表示されない、検索に引っかからない物)
・おすすめトレーニングの提案(YouTube Data API)
・Google認証ログイン機能

■ 機能の実装方針予定

現在地の取得(Google Geolocation API)
場所の取得(Google Places API)、
おすすめトレーニングの提案(YouTube Data API)
Google認証ログイン機能
