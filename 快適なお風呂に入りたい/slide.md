---
marp: true
theme: mytheme
paginate: true
header: "Raspberry Piで快適な入浴を"
footer: "2025-04-26 itoJum"




---

<div class="title">

# Raspberry Piで快適な入浴を
</div>
<div class="info">

**エンジニア集会 2025-04-26**
いとじゅん / @itojum1230
</div>

<style>
.columns {
  display: flex;
  justify-content: space-around;
}
.minitxt {
  font-size: 24px;
}
</style>

---

# 自己紹介

<div class="columns">
  <img src="./itojum.png" width="300px" height="300px">
  <div>

  ## いとじゅん
  - 情報系大学生
  - 内定者インターンで死んでる
  - RubyKaigi2025行ってきた
    - 鯛おいしかった

  </div>

</div>

---

# レギュレーション順守

<div class="chapter">

## **ハード**スキル + ソフト**ウェア**
</div>

みんなもLet's LT


---

# もくじ

<div class="columns">
  <div>

  - 作ったもの
  - 素材集め
  - 技術構成と実装
  - 運用してみた感想

  </div>
  <div>
    <img src="./kanifuro.png" width="450px">
  </div>
</div>

---

<div class="chapter">

# 学生の一人暮らしでお風呂って面倒

</div>

---


# 作ったもの

<div class="columns">
  <img src="./dashboard.png" width="320px">
  <div>

  - お風呂の水位が一定になると
  Discordに通知
  - スプレッドシートで
  水温の推移を可視化

  </div>

--- 

# 素材集め

<div class="columns">

  <div>

  - 水温センサー：DS18B20
  - Raspberry Pi 3, その他部品
  - 段ボール
    - ケース用
  - モバイルバッテリー

  </div>
  <div>
    
  <img src="./kairo.png" width="450px">
  </div>
</div>

---

# 技術構成と実装

<div class="columns">
  <div>

  - なでしこで10秒ごとに
  温度を取得して送信
  - GASがスプレッドシートに温度を記録
  - GASでしきい値チェック
  - しきい値を超えたらDiscordに通知

  </div>
  <div>
    <img src="./dev.png" width="400px">
  </div>
</div>

---

## なでしこ
<img src="./nadesiko.png" width="800px">

---

## なでしこ

<img src="./nadesiko-code.png" width="800px">



---

## 水位問題
<style>
  .margin {
    margin-left: 50px;
  }
</style>

<div class="margin">

  #### Q. 水位を取得するには
  - 距離センサー
  - 水位センサー

</div>

---


## 水位問題

<div class="columns">
  <div>

  #### Q. 水位を取得するには
  - 距離センサー?
  - 水位センサー?
  #### A. 水温センサーを垂らす
  </div>
  <div>
    <img src="./tarasu.png" width="350px">
  </div>
</div>

---
<style>
  .center {
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

## グラフ & 通知
<div class="columns">
  <div>

  <img src="./graph.png" width="650px">

  </div>
  <div class="center">
    <img src="./discord.png" width="400px">
  </div>
</div>

---

# 感想

<div class="columns">
  <div>

  - ちょうどいい温度＆水位の風呂に
  久しぶりに入れた

- ケースは段ボール → 湿気&水滴に脆弱
  - 防水ケースいるかな

  </div>
  <div>
    <img src="./hako.png" width="300px">
  </div>
</div>

---

<div class="chapter">

# おわり

</div>

