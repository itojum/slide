---
marp: true
theme: mytheme
paginate: true

---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>



<div class="title">

## 福プロ 第一回講座
# 技術スタックって何があるの？

</div>
<div class="info">

**2025/05/21**
伊藤 潤平 / @itojum1230
</div>

---

# 目次

<div class="contents">

1. 技術スタックとは？
2. 用語紹介
3. 技術領域別紹介
4. まとめ

</div>

---

# 技術スタックとは？

今回の講座において技術スタックとは、

<div class="flex justify-center">

<div>

- プログラミング言語
- フレームワーク
</div>

<div>

- ライブラリ
- 開発ツール
</div>

</div>

<div class="flex justify-end">
などの技術要素を指します。
</div>

技術スタックや技術領域を知ることで、
- 自分が「**何を学んでいるのか**」が整理できる
- キャリアや進路のイメージが持てる

---

# 用語紹介

<div class="flex justify-center gap-4">
  <div class="w-1/2">
  
  ### ライブラリとは

  特定の機能を提供する**部品**
  規模の小さいものが多い

  <br/>
  例:

  <div class="flex justify-center gap-8">
    <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/800px-React-icon.svg.png" class="h-32"/>
      <span class="text-2xl">React.js</span>
    </div>
    <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/1280px-Bootstrap_logo.svg.png" class="h-32"/>
      <span class="text-2xl">Bootstrap</span>
    </div>
    <div>
      <img src="https://cdn.worldvectorlogo.com/logos/numpy-1.svg" class="h-32"/>
      <span class="text-2xl">Numpy</span>
    </div>
  </div>


  </div>
  <div class="w-1/2">
  
  ### フレームワークとは
  アプリの**骨組み**を提供する仕組み
  規模の大きいものが多い

  <br/>
  例:

  <div class="flex justify-center gap-8">
    <div>
      <img src="https://cdn.worldvectorlogo.com/logos/next-js.svg" class="h-32"/>
      <span class="text-2xl">Next.js</span>
    </div>
    <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Ruby_On_Rails_Logo.svg/512px-Ruby_On_Rails_Logo.svg.png?20240926221852" class="h-32"/>
      <span class="text-2xl">Ruby on Rails</span>
    </div>
  </div>

  </div>
</div>

---

<div class="chapter">

# 技術領域別紹介

</div>

---

# フロントエンドとは？

- 広義ではユーザーが直接触れる画面を作る領域
- 一般的にはWebサイトやWebアプリの
見た目・操作を制御する技術領域

技術スタックの例:

<div class="flex justify-right gap-8">
  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">言語</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1200px-HTML5_logo_and_wordmark.svg.png" class="h-32"/>
        <span class="text-2xl text-center">HTML</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png" class="h-32"/>
        <span class="text-2xl text-center">CSS</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://www.w3schools.com/whatis/img_js.png" class="h-32"/>
        <span class="text-2xl text-center">JavaScript</span>
      </div>
    </div>
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">ライブラリ</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/800px-React-icon.svg.png" class="h-32"/>
        <span class="text-2xl text-center">React.js</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/2367px-Vue.js_Logo_2.svg.png" class="h-32"/>
        <span class="text-2xl text-center">Vue.js</span>
      </div>
    </div>
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">フレームワーク</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://cdn.worldvectorlogo.com/logos/next-js.svg" class="h-32"/>
        <span class="text-2xl text-center">Next.js</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Nuxt_logo.svg/512px-Nuxt_logo.svg.png" class="h-32"/>
        <span class="text-2xl text-center">Nuxt.js</span>
      </div>
    </div>
  </div>
  
</div>

---

# バックエンドとは？

- ユーザーの目に見えない裏側の処理を担当
- データの保存や処理、認証などの仕組みを作る

技術スタックの例:

<div class="flex justify-right gap-8">

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">言語</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7f-wJWs8YeKnpOyd6Rh0wr1yUaB2JjksCMQ&s" class="h-32"/>
        <span class="text-2xl text-center">Ruby</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://cdn.worldvectorlogo.com/logos/java-14.svg" class="h-32"/>
        <span class="text-2xl text-center">Java</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://cdn.worldvectorlogo.com/logos/python-5.svg" class="h-32"/>
        <span class="text-2xl text-center">Python</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://cdn.worldvectorlogo.com/logos/go-8.svg" class="h-32"/>
        <span class="text-2xl text-center">Go</span>
      </div>  
    </div>
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">フレームワーク</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Ruby_On_Rails_Logo.svg/512px-Ruby_On_Rails_Logo.svg.png?20240926221852" class="h-32"/>
        <span class="text-2xl text-center">Ruby on Rails</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8i4zPog-0j0JR_yZglxPhTPZXxN2iMTQ3Dw&s" class="h-32"/>
        <span class="text-2xl text-center">Spring</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://cdn.worldvectorlogo.com/logos/django.svg" class="h-32"/>
        <span class="text-2xl text-center">Django</span>
      </div>
    </div>
  </div>

</div>

---

# インフラとは？

- サーバーやネットワークなど、システムの土台を支える部分
- アプリやサービスを動かすための環境を整える役割

技術スタックの例:

<div class="flex justify-right gap-8">

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">クラウド</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://cdn.iconscout.com/icon/free/png-256/free-aws-1869025-1583149.png?f=webp" class="h-32"/>
        <span class="text-2xl text-center">AWS</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://static-00.iconduck.com/assets.00/google-cloud-icon-1024x823-wiwlyizc.png" class="h-32"/>
        <span class="text-xl text-center">Google Cloud</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/2048px-Microsoft_Azure.svg.png" class="h-32"/>
        <span class="text-2xl text-center">Azure</span>
      </div>
    </div>
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">データベース</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://download.logo.wine/logo/MySQL/MySQL-Logo.wine.png" class="h-32"/>
        <span class="text-2xl text-center">MySQL</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/1985px-Postgresql_elephant.svg.png" class="h-32"/>
        <span class="text-xl text-center">PostgreSQL</span>
      </div>
    </div>
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">コンテナ</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://cdn.worldvectorlogo.com/logos/docker-4.svg" class="h-32"/>
        <span class="text-2xl text-center">Docker</span>
      </div>
    </div>
  </div>

</div>

</div>

---

# モバイル開発とは？

- スマホやタブレットなどモバイル端末で動作するアプリの開発
- iOSやAndroidで別々に開発したり、
クロスプラットフォームで開発したりする

技術スタックの例:

<div class="flex justify-right gap-8">

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">言語</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRQPpQdaKwLkyNz7dDhTIh2uC9ETp3Z1pVGPw&s" class="h-32"/>
        <span class="text-2xl text-center">Kotlin</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://developer.apple.com/swift/images/swift-og.png" class="h-32"/>
        <span class="text-2xl text-center">Swift</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://img.icons8.com/?size=256&id=7AFcZ2zirX6Y&format=png" class="h-32"/>
        <span class="text-2xl text-center">Dart</span>
      </div>
    </div>
  </div>
  
  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">開発環境</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c1/Android_Studio_icon_%282023%29.svg/2048px-Android_Studio_icon_%282023%29.svg.png" class="h-32"/>
        <span class="text-lg text-center">Android Studio</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://developer.apple.com/assets/elements/icons/xcode-12/xcode-12-96x96_2x.png" class="h-32"/>
        <span class="text-2xl text-center">Xcode</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://storage.googleapis.com/cms-storage-bucket/4fd5520fe28ebf839174.svg" class="h-32"/>
        <span class="text-2xl text-center">Flutter</span>
      </div>
    </div>
  </div>
  
</div>

---

# ゲーム開発とは？
- コンピューターやスマホ、ゲーム機向けのゲームを作る領域
- グラフィックや操作性、リアルタイム処理が重要

技術スタックの例:

<div class="flex justify-right gap-8">

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">言語</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1200px-ISO_C%2B%2B_Logo.svg.png" class="h-32"/>
        <span class="text-2xl text-center">C++</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRcSzlS1T05i8p4MVlYWRT4cJZOd273HeRKUg&s" class="h-32"/>
        <span class="text-2xl text-center">C#</span>
      </div>
    </div>
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">開発環境</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://www.svgrepo.com/show/342328/unreal-engine.svg" class="h-32"/>
        <span class="text-2xl text-center">Unreal Engine</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://cdn.sanity.io/images/fuvbjjlp/production/2495ab2daae11fd3ed5d6b84477d513869f9a1b4-89x100.png" class="h-32"/>
        <span class="text-2xl text-center">Unity</span>
      </div>
    </div>
  </div>

</div>

---

# LLM・AIツールとは？

- 自然言語を理解・生成するAI技術
- それらを使ったAIツールが多く存在する

技術スタックの例:

<div class="flex justify-right gap-8">

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">LLM</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://freelogopng.com/images/all_img/1681038242chatgpt-logo-png.png" class="h-32"/>
        <span class="text-2xl text-center">ChatGPT</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcThr7qrIazsvZwJuw-uZCtLzIjaAyVW_ZrlEQ&s" class="h-32"/>
        <span class="text-2xl text-center">Gemini</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnM91o7r1wba01xcHW15PLqbe-ONaTIjOO3g&s" class="h-32"/>
        <span class="text-2xl text-center">Claude</span>
      </div>
    </div>
    
  </div>

  <div class="flex flex-col gap-4 mt-4">
    <span class="text-4xl">AIツール</span>
    <div class="flex gap-4">
      <div class="flex flex-col gap-4">
        <img src="https://paulstamatiou.com/gear/cursor-app-icon.png" class="h-32"/>
        <span class="text-2xl text-center">Cursor</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIEHwdM5-Izn_jbXmAoGuOp68EG61K4H3vsw&s" class="h-32"/>
        <span class="text-lg text-center">GitHub Copilot</span>
      </div>
      <div class="flex flex-col gap-4">
        <img src="https://app.devin.ai/devin_v4.png" class="h-32"/>
        <span class="text-2xl text-center">Devin</span>
      </div>
    </div>
  </div>

</div>

---


# まとめ

- 技術スタックを知ることで**将来像**を意識することができる
- 各技術領域ごとに**役割**や**代表例**を理解することが大切
- 興味のある分野から実際に触ってみて、
自分の技術スタックを広げていこう
- 技術は日々進化しているので、常に**学び続ける姿勢**も重要
  - 特にフロントエンドとAIは進化が早い

---

<div class="chapter">

# おわり

</div>