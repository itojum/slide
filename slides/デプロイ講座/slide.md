---
marp: true
theme: mytheme
paginate: true

---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>



<div class="title">

# デプロイ講座
## ~Webアプリを公開してみよう！~
</div>
<div class="info">

**福プロ 2025-07-23**
いとじゅん / @itojum1230
</div>

---

# 目次

<div class="contents">

1. はじめに
2. Webアプリケーションの仕組み
3. デプロイとは
4. Webアプリを動かしてみよう！
5. デプロイしてみよう！
6. まとめ

</div>

---

# はじめに

## 準備してもらったもの
- PC
- GitHubアカウント
- インストールしているもの
  - Node.js
  - Git

準備できてない方はこの後の時間で準備お願いします<span class="emoji pray-nya"></span>


---

# Webアプリケーションの仕組み

<img src="https://lh3.googleusercontent.com/pw/AP1GczNtRGAbGTFf9kOyFnK9XfWGhbF5b0krKdsHVGeHHcUi5slWSWeR9dMp9dOLWB9vfdZUw9LVNaYKaagmcsWyCVpfbr0I-xO6l_noaa6J9s0XojtNb12EBBclJomx5ABXlY1MLLihvybcyNCKO3JzVx4G=w1346-h419-s-no-gm?authuser=0" width="100%">

- めっちゃ簡略化するとこんな感じ

---

# Webアプリケーションの仕組み

<img src="https://lh3.googleusercontent.com/pw/AP1GczPj7InAenEH9QU3DiMbOLfKPweNR_iEFdlXTFdfmJTp3qd7tASVvtn_jx_x7I6NKedXY6-DbJIz00xwCszZ18KL8ls9P1mgnmKd4dPzcW-pVD-33TqLQz8MpRUuOUy8DgnrbdryKY5u2pAB9Ro2gknx=w1346-h471-s-no-gm?authuser=0" width="100%">

- 今回の講座の内容だとこんな感じ

---

# デプロイとは

<img src="https://lh3.googleusercontent.com/pw/AP1GczNWH9b4mJHlrbHSg0uPlFZIIAUJGoGRsthZYivDboXQIyMkKlmEsaIfEnSALi6_E0xbmLpHUhFQIGMDVsm29XQ2ULwIljItv4HfyBJdbyOI8RKWd-oXcM2mZt0gPXm0Co8jEGqeddCSb6F2O5hi5Q7-=w812-h615-s-no-gm?authuser=0" class="p-8 h-[500px]">

<img src="https://lh3.googleusercontent.com/pw/AP1GczOXbgrW6t-R-nEJRECUHyDo1c_2M9ABkSVPeqnLcsesTD_3_L2KTtK9ZcUtGtvElr-hRd9b4VJbO12-Fj51v9x4CQvz4NKpAFL1pgAFaQJ1DeLi6N9cvbBd5s5jLbE7ShXu3sUCStNCL0OrK5-BKTDs=w128-h128-s-no-gm?authuser=0" class="absolute bottom-[100px] right-[150px]">

---

# Webアプリを動かしてみよう！

以下のリポジトリを**fork**して、**clone**してください
https://github.com/itojum/deploy_course

<img src="https://lh3.googleusercontent.com/pw/AP1GczO1LXz_SO-mwSxkpnfjG7WmGipMsp8JWbr6bQUvM6zkw6kyBu5fDdPDKJarcETVDLE2MxciLXe8IK6cOjBvKzAlpwG3dS_fSjDdM3iq_C80mToVsHvIVoxdH_REv7GO1X0KuM2e9dAbW5gK6X5TKppW=w713-h574-s-no-gm?authuser=0" class="h-[480px]">


---

# Webアプリを動かしてみよう！

- READMEの実行方法に従って実行してみてください

<div class="flex justify-center gap-4">
  <img src="./quiz.png" class="w-1/3">
  <img src="./tetris.png" class="w-1/3">
  <img src="./todo.png" class="w-1/3">
</div>

---

# デプロイしてみよう！

- 簡単にグローバルに公開するためには、
クラウドサービスを使うのがおすすめです
- Cloudflare Pages、GitHub Pages、Vercelを利用します
- 時間がある人はWebアプリのコードリーディングや
改造をしてみてください

---

# デプロイしてみよう！Cloudflare Pages編

## Cloudflare Pages
- Cloudflareのサービスの1つ
- 無料で結構いい感じに動く
- 凝ったアプリをデプロイするときは、Cloudflare Workersを使う

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSvaaS6cz2-k_AywDZ0twr_KFwOC5CHQPiFNA&s" class="h-[180px]">


---

# デプロイしてみよう！Cloudflare Pages編

<div class="flex justify-center gap-4 mt-8">
  <img src="./cloudflare_1.png" class="h-[400px]">
  
  1. Cloudflareのアカウントを作成
    - Googleログインがおすすめ
  2. 「アプリケーションを作成する」をクリック
  3. Pagesを選択
  4. 「既存のGitリポジトリをインポートする」

</div>

---

# デプロイしてみよう！Cloudflare Pages編

<div class="flex justify-center gap-4 mt-8">
  <img src="./cloudflare_2.png" class="h-[550px]">

  5. `deploy_course`リポジトリを選択
  6. ビルド出力ディレクトリに`tetris`を入力
  7. 「保存してデプロイする」

</div>

---

# デプロイしてみよう！Cloudflare Pages編

<div class="flex justify-center gap-4 mt-8">
  <img src="./tetris2.png" class="h-[550px]">

  8. デプロイが完了すると、URLが表示されます
  9. URLをクリックして表示されたら完了

</div>

<img src="https://lh3.googleusercontent.com/pw/AP1GczN4Y9a0sklZ1M1NLSw0lPfRSwMGM_rDKnreEUofS4KwrD7WpTx2n3EqGBUsJrPi-MEGXa1tLPOk_feE19nSmtxBK7kbAOQZdvYybeS3yrrwZg5HQ7l6cibFTKWTjVXdLjsZCs_eD1ZEDlOeGAvgBclh=w128-h128-s-no-gm?authuser=0" class="absolute bottom-[100px] right-[150px]">

---

# デプロイしてみよう！GitHub Pages編

## GitHub Pages
- GitHubのサービスの1つ
- 静的なWebアプリをデプロイするのには使える
- サーバーサイドは無理

<img src="https://assets.st-note.com/production/uploads/images/152590177/rectangle_large_type_2_a5942dbfa406ac336d45e23360d55600.png?fit=bounds&quality=85&width=1280" class="h-[200px]">

---

# デプロイしてみよう！GitHub Pages編

<div class="flex justify-center gap-4 mt-8">
  <img src="./github_1.png" class="h-[500px]">

  1. forkしたリポジトリのSettingsを開く
  2. Pagesを開く
  3. Branchのmainを選択
  4. 「Save」をクリック


</div>

---

# デプロイしてみよう！GitHub Pages編

<div class="flex justify-center gap-4 mt-8">
  <img src="./github_2.png" class="h-[550px]">

  5. Actionsタブを開く
  6. これが✅になったらクリック

</div>

---

# デプロイしてみよう！GitHub Pages編

`https://[ユーザー名].github.io/deploy_course/quiz/`

<div class="flex justify-center gap-4 mt-8">
  <img src="./github_3.png" class="h-[450px]">

   7. 表示されたら完了

</div>

<img src="https://lh3.googleusercontent.com/pw/AP1GczN4Y9a0sklZ1M1NLSw0lPfRSwMGM_rDKnreEUofS4KwrD7WpTx2n3EqGBUsJrPi-MEGXa1tLPOk_feE19nSmtxBK7kbAOQZdvYybeS3yrrwZg5HQ7l6cibFTKWTjVXdLjsZCs_eD1ZEDlOeGAvgBclh=w128-h128-s-no-gm?authuser=0" class="absolute bottom-[100px] right-[150px]">

---

# デプロイしてみよう！Vercel編

## Vercel
- Web系のライブラリやフレームワークを大体デプロイできる
- Next.jsのデプロイをするならVercelが最適
- 今回はReactのアプリをデプロイしてみる

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Vercel_logo_black.svg/2560px-Vercel_logo_black.svg.png" class="h-[200px]">

---

# デプロイしてみよう！Vercel編

<div class="flex justify-center gap-4 mt-8">
  <img src="./vercel_1.png" class="h-[500px]">

  1. Vercelのアカウントを作成
  2. 「Add New...」→「Project」をクリック
  3. `deploy_course`リポジトリをimport
  4. Root DirectoryのEditをクリックして`todo`を選択
  5. 「Deploy」をクリック

---

# デプロイしてみよう！Vercel編

<div class="flex justify-center gap-4 mt-8">
  <img src="./vercel_2.png" class="h-[500px]">

  6. アプリの画面をクリック
  7. 表示されたら完了

</div>

<img src="https://lh3.googleusercontent.com/pw/AP1GczN4Y9a0sklZ1M1NLSw0lPfRSwMGM_rDKnreEUofS4KwrD7WpTx2n3EqGBUsJrPi-MEGXa1tLPOk_feE19nSmtxBK7kbAOQZdvYybeS3yrrwZg5HQ7l6cibFTKWTjVXdLjsZCs_eD1ZEDlOeGAvgBclh=w128-h128-s-no-gm?authuser=0" class="absolute bottom-[100px] right-[150px]">

---

# まとめ

- Webアプリケーションの仕組み
  - ユーザー、ブラウザ、サーバー
- デプロイは割と簡単にできる
  - 今回はGitHub Pages、Cloudflare Pages、
  Vercelを利用した
  - どれが簡単だったかな?
- 自分が作ったアプリを公開してみよう！
