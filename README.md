# pokeWat
Titan Oneを用いた，ポケモンの無限ワット回収の自動化です．
ランクバトルを用いない，旧バージョンの回収方法です．
丸1日で約900万程度だと思われます．

# How to use
- 日付を2000年1月の1日以外の日に設定(インターネットで時間設定をオフ)
- 願いの塊を投入した穴の目の前でBボタンを一瞬押す(長押しすると最初の入力が飛ぶ恐れがあり)
- 放置
- 止めたいタイミングでBボタンorTitan Oneのボタンを押す

# 細かいこと
- 1年回すごとにセーブするよう設定してあります．

# 注意点
- 自環境(DL版シールド，PDPコン)では上手くいきましたが，ロード時間やコントローラなどが変われば上手くいかない可能性(wait()内部を適宜変更してください)
- 天候によりロード時間が変化するため，割と余裕を持たせた操作をしているので，最速ではないです．
- インターネットに繋いだままだと，もしポケモンがエラーで落ちた場合に何を起こすか不明なので，切ること．
- 責任はもちません．
