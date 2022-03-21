# compornent（共通部品）

## イメージ画像
<img width="406" alt="image" src="https://user-images.githubusercontent.com/99580997/159238073-574f44d6-734e-4b15-bf8b-1aa3c7a20c61.png">
<img width="780" alt="image" src="https://user-images.githubusercontent.com/99580997/159238148-28beeaec-412b-4b85-bf74-70adb5493648.png">
<img width="1089" alt="image" src="https://user-images.githubusercontent.com/99580997/159238324-47c86724-7fdd-4e53-9cad-67665b0d603a.png">



## 概要

- css で斜め線を表現(linear-gradient)、模擬案件

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- 斜め線は表現できたけど、レスポンシブすると始点がずれる。これでは使えない。
- before(赤線)が width:1024 以降で切れるのも理解できない。100vw、100vh を設定してるのに。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> line をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
- <img width="1004" alt="image" src="https://user-images.githubusercontent.com/99580997/159238411-916dcb9e-3350-4cb7-8c18-6aea592d35bb.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
- <img width="1666" alt="image" src="https://user-images.githubusercontent.com/99580997/159238517-3abfceea-9c3f-4c86-b25e-93bc26a115e5.png">


## portfolio url:

- https://c-0030.wtb.cfbx.jp/

## 参考にしたサイト

- 【CSS】背景（background）を 2 色にする
- https://125naroom.com/web/3028
- CSS のグラデーション（linear-gradient）の使い方を総まとめ！
- https://tinyurl.com/yde8625u
- linear-gradient() で斜線を表現する際のアンチエイリアス
- https://onl.la/2CUEqFn
- 【css】background の linear-gradient で使った斜めの線ががギザギザになる件
- https://twotone.me/web/3725/
- 【css】background の linear-gradient で使った斜めの線ががギザギザになる件
- https://twotone.me/web/3725/
- CSS の疑似要素とは？before と after の使い方まとめ
- https://onl.la/PyXDpcy
- 知らないと損！CSS の vh/vw の使いこなしでレスポンシブなサイト制作が捗る
- https://tinyurl.com/ycnnqnq9
- 【CSS】before・after を 3 つ以上複数使えるか？
- https://tinyurl.com/y8j7n5ks

## 更新履歴

- 2022/3/21 初版 作成完了

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
