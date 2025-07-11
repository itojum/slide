---
marp: true
theme: mytheme
paginate: true

---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>



<div class="title">

# connpass AIボットを作りたかった
</div>
<div class="info">

JR中央線 Developers もくもく&LT大会！ #23 2025/7/12
いとじゅん / @itojum1230
</div>

---

# 自己紹介

<div class="flex">

<img src="https://lh3.googleusercontent.com/a/ACg8ocJxcTtJdUnbmEE6vjkZXYiem9Bf5wUF-_G_cmdwTv9lz63VMEI2Lp9i4p97EIvVU9xt_l_vXhgXF17GQvJPErmjh_UEZb0=s288-c-no" alt="いとじゅん" class="w-[300px] h-[300px] mr-[50px] mt-10">

- いとじゅん
- Student / PdE
- 在住: 広島県
- 出身: 鳥取県

</div>

<img src="./work-nya.png" class="absolute bottom-10 right-40 w-[150px]">

---

# connpass AIボット
<div class="flex gap-20">

- connpassのイベントやユーザーを
取得できるAIエージェント
- LINE上で簡単に応答してくれる

<img src="https://lh3.googleusercontent.com/pw/AP1GczMfxSYYEvyA0-Pq15jJsVzMMJ0JKK6fsKKwmK8afKCWC_qA_YuomgA7r6qqyKvDig_-V0kbl5IbRKkD7gz9UvO7dY8ULUwIcdvs3fz7HtsXBf2jShMuNPo5bQdjBtYAdE1z0ZCUDvF8dmn0qTHziK8=w646-h1436-s-no-gm?authuser=0" width="30%">

</div>

---

# 簡単な構成図
<img src="https://lh3.googleusercontent.com/pw/AP1GczPkU4c0n4YfyTcFP-8nCUQfDaZzAPLWI-UYdzlzvqvQH4OJ913Oj4gWjeF2CVeoZcLGm00xttmRtNY0IE-gA-dlNdrrJSh7Z94PXvV7TKPRIaU1bKeiSymwhMyGhfI_CLhyWPvnot3qkDRRQ1xjRlY=w1556-h412-s-no-gm?authuser=0" class="mt-[100px]">

---

# 進捗

<div class="flex">

<div>

## できているところ
- AIエージェントによる応答
- connpass MCP
- LINEボットとの接続
</div>

</div>

<img src="./doya-nya.png" class="absolute bottom-10 right-40 w-[150px]">

---

# 進捗

<div class="flex">

<div>

## できているところ
- AIエージェントによる応答
- connpass MCP
- LINEボットとの接続
</div>

<div>

## できていないところ
- Mastraサーバーのデプロイ
- 会話ログ保存方法の確立

</div>

<img src="./mechanaki-nya.png" class="absolute bottom-10 right-40 w-[150px]">

---

# 今後

- デプロイ
  - Vercelデプロイを試す
  - Mastra Cloudのデプロイがなぜ失敗しているかを調査
- ワークフロー
  - 求める処理に再現性を
- いっぱい使いたい

<img src="./thanks-nya.png" class="absolute bottom-10 right-40 w-[150px]">