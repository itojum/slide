---
marp: true
theme: mytheme
paginate: true
header: "昔作ったオセロゲームのソースコードを笑う会"
footer: "2025-03-29 いとじゅん"

---
<style>
.columns {
  display: flex;
  justify-content: space-around;
}
.minitxt {
  font-size: 24px;
}
</style>

<div class="title">

# 昔作ったオセロゲームの</br>ソースコードを笑う会
## ~ Cursor vs 私 ~
</div>
<br>

<div class="info">

**エンジニア集会LT会 2025-03-29**
いとじゅん / @itojum1230
</div>



---

# 目次
1. 自己紹介
2. このオセロゲームについて
3. ソースコードを笑う会
4. まとめ

---

<div class="chapter">

# ⚠注意⚠

</div>

---

<div class="chapter">

# 心臓に悪いコードが含まれます<br>視聴する際はご注意ください

</div>

---

# 自己紹介

<div class="columns">
  <img src="./itojum.png" width="300px" height="300px">
  <div>

  ## いとじゅん
  - 情報系大学生
  - インターンシップのためにRails勉強中
  - 最近Noshを買ってみた
    - ちょっとおいしい

  </div>

</div>

---

# このオセロゲームについて

<div class="columns">

  <div>

  - 3年くらい前に作った<br>オンライン対戦オセロゲーム
  - アニメーションに<br>ハマってた時期の産物
  - リアルタイム要素
    - ソケットで頑張った
  </div>

  <img src="othello.png" width="500" height="420">
</div>

---
<div class="chapter">

# ソースコードを笑う会

</div>

---

# ルール

- Cursorくんにオセロゲームのコードを酷評してもらう
  - 頑張って昔の自分を擁護するのでどこまで対抗できるのか
- 以降の文字は基本的にCursorくんのコピペ

---

# 衝撃の盤面表現 - 闇の始まり

<div class="columns">
  <img src="./tile_source.png" width="350">
  <div>

  - 文字列で盤面を表現するという狂気
  - バックスラッシュによる改行の連続
  - 配列を使わないという選択

</div>

---
# じゃんけんシステム - なぜ必要なのか
<img src="./janken_source.png" width="800px">

- オセロにじゃんけんが必要な理由
- 複雑すぎる条件分岐
- コイン投げではダメだったのか

---

# 石を置く処理 - 闇の深淵
<img src="./put_source.png" width="800px">

- 文字列操作による石の配置
- 型の不一致（文字列と数値の混在）
- 謎の命名規則（AiteColor）

---

# ルーム管理 - 混沌の管理システム
<img src="./room_source.png" width="800px">

- 配列のインデックスが1から始まる
- グローバル変数の乱用
- 4部屋固定という柔軟性の欠如

---

# ソケット通信 - 闇の通信術
<div class="columns">
  <img src="./socket_source.png" width="520px" height="300px">

  <div>

  - すべてのイベントを<br>'socket'で処理
  - 引数の配列による謎の状態管理
  - 条件分岐の連続

  </div>
</div>

---

# まとめ

- Winner: Cursor
- Cursorくんの指摘が理解できる程度に<br>成長したということで
- 可読性って大事だね

---

<div class="chapter">

# おわり

</div>

