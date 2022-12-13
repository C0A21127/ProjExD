# 第4回
## 逃げろこうかとん
### ゲーム概要

* ex04/dodge_bomb.pyを実行すると、1600x900のスクリーンに草原が描画され、こうかとんを移動させ飛び回る爆弾から逃げるゲーム
* こうかとんが爆弾と接触するとゲームオーバーで終了する

### 追加機能
* 講義で書いたプログラムを基にvx2,vx3,vy2,vy3をの数値を追加し、爆弾の数を1つから3つに増やした。また、3つの爆弾全てに当たり判定があるため、どれか1つにこうかとんが接触するとゲームオーバーとなる。
* それぞれの爆弾の動く速さの数値を+1,+2,+3とし、色の数値も違うものに設定した
* 爆弾の大きさをそれぞれ違う数値に設定した。

### ToDo
* ゲーム開始からの経過時間を表示させることで、プレイヤーが生き残っている時間が分かるようになればもっと面白いゲームにすることができると思った。
* 爆弾に接触するとこうかとんの画像が切り替わるようにしたかった。