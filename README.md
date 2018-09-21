# sample-modules
自分でつくったベース的なあれこれを管理してるリポジトリです。

## plugins
ここには仕事でやった中で、後でも使えるようにしてあると便利じゃん。ってものたちが入ってます。
Javascriptで作るような下記のもの。

「_loaded」は読み込むためのファイルが入ってる。
- base.css, reset.css
- jQuery3.2.1

「ui」は見た目のやつ
- adjust（複数要素の高さ揃え）
- book（本みたいな画像切替）
- crossfade（フェードアウトしつつ次の画像が出てくるやつ）
- filter-sort（選択するとマッチしたものだけ上にアニメーションで移動）
- form（formのスタイリング）
- menu（）
- modal（モーダル、固定とか中にスライドするやつが入ってたりとか）
- responsive（画面幅での画像の出し分け）
- slot（スロットみたいなアニメーション）
- tab（タブ切り替え）

「utility」は見た目じゃないやつ
- analytics
- cookie
- iframe
- local-storage
- random-array
- sns-share
- url-param
- user-agent

*多々古いものがあったり、ホヤホヤの頃に作ったものだったりがある*

## templates
ここにはCSSのベース（base.css, reset.css...）が入ってたり、  
SNSのフリーのアイコンが入ってたり  
HTMLの雛形が入ってたり  
ファビコン作成のためのPSDが入ってたり

## tools
ここには、タスクランナーとバンドラーの設定・環境が入ってる
- タスクランナー（Gulp v4）
- バンドラー（Webpack v4）
