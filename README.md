# ProjExD_05

# ふらっとん
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
Flappy Birdがモチーフ。こうかとんが土管に当たらないようにジャンプさせるゲーム

## ゲームの実装
### 共通基本機能
* 主人公キャラクターに関するクラス+描画
* 土管に関するクラス+描画
* 背景描画
  
### 担当追加機能
* コイン, 点数追加: ~~土管を通過した際に~~コインを獲得した時に1ポイント獲得
* 一定点数で無敵(+表示変更): 50ポイントとか取れたら無敵
* 土管の長さ調整
* アイテム機能: 土管の幅広げるとかジャンプ量増えるとか
* ゲームオーバー画面
  
### ToDo
- [ ] アイテム機能実装
      
* コイン機能: コイン集め　浮いてる
* 良いアイテム機能: 移動速度が低下
* 悪いアイテム機能: 移動速度が上昇
* gameover画像追加: こうかとんが土管に当たったらgameoverとスコアを表示

### ToDo
- [ ] 点数機能
- [ ] 無敵機能
- [x] コイン機能
- [X] アイテム(良)機能
- [X] アイテム(悪)機能
- [x] gameover画像追記

* コイン機能: コイン集め　浮いてる
* 良いアイテム機能: 土管の幅広げるとか
* 悪いアイテム機能: ジャンプ量が増加する


### メモ
ゲットするとスコアが１上がるコイン(class Coin)と、ゲットするとスコアが１０上がるレアなコイン(class CoinRare)を実装
金色のコインがスコア１、ピンクのコインがスコア１０
