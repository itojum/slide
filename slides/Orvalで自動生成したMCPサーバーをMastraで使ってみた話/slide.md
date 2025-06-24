---
marp: true
theme: mytheme
paginate: true

---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>



<div class="title">

# Orvalでconnpass MCPサーバーを</br>自動生成してみた
</div>
<div class="info">

**Setory 2025-06-28**
いとじゅん / @itojum1230
</div>

---

# 自己紹介

<div class="flex">
<img src="https://lh3.googleusercontent.com/a/ACg8ocJxcTtJdUnbmEE6vjkZXYiem9Bf5wUF-_G_cmdwTv9lz63VMEI2Lp9i4p97EIvVU9xt_l_vXhgXF17GQvJPErmjh_UEZb0=s288-c-no" alt="いとじゅん" class="w-[300px] h-[300px] my-auto">


- いとじゅん(@itojum1230)
- 福プロ 元代表
- 趣味
  - VRChat
- 好きなテキストエディタ
  - Cursor

</div>

---

# OrvalとMCPサーバー

<div class="flex">
  <div class="flex flex-col">
    <img src="https://orval.dev/images/emblem.svg" alt="Orval" class="w-[200px] my-auto">
    <img src="https://avatars.githubusercontent.com/u/182288589?s=200&v=4" alt="MCP" class="w-[200px] my-auto">
  </div>

  - Orvalとは
    - OpenAPIからWebAPIのクライアントを<br/>自動生成するライブラリ
  - MCPサーバーとは
    - AIエージェントと外部サービス(WebAPIなど)を繋ぐサーバー(雑)

</div>

---

# OrvalとMCPサーバー

<div class="flex">
  <div class="flex flex-col">
    <img src="https://orval.dev/images/emblem.svg" alt="Orval" class="w-[200px] my-auto">
    <img src="https://avatars.githubusercontent.com/u/182288589?s=200&v=4" alt="MCP" class="w-[200px] my-auto">
  </div>

  - Orvalとは
    - OpenAPIから<u>WebAPIのクライアント</u>を<br/>自動生成するライブラリ
  - MCPサーバーとは
    - AIエージェントと<u>外部サービス(WebAPIなど)</u>を繋ぐサーバー(雑)

</div>

---

<div class="chapter">

# できちゃうんです...

</div>

---

<div class="chapter">

# OrvalでMCPサーバーが...!

</div>

---

# ステップ1
- connpassのAPI Keyを利用申請して発行してもらいます
- 数回メールでやり取りしたら1営業日で発行してもらえました

<img src="./connpass.png" class="w-full">

---

# ステップ2

<div class="flex">
  <div class="flex flex-col">
    <img src="./connpass_openapi.png" alt="MCP" class="w-[700px] mt-10">
  </div>

  - connpass APIのドキュメントを<br/>参考にOpenAPIを書きます
  - 普段よりパラメータのdescriptionを丁寧に書きます

</div>

