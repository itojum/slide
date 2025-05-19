---
marp: true
theme: mytheme
paginate: true
header: "技術スタックってそもそも何があるの？"

---

<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>


<div class="title">

# 技術スタックってそもそも何があるの？
</div>
<div class="info">

**福プロ 第一回講座 2025-05-21**
伊藤潤平 / @itojum1230
</div>

---

<div class="chapter">

# エンジニアリングやってますか？！

</div>

---

# 目次

1. 用語解説
2. プログラミング言語たち
3. ライブラリ・フレームワークたち
4. 開発で使うサービスたち
5. まとめ

---

<div class="chapter">

# 用語解説

</div>

---


## 1. 技術スタック

<img src="./techStack.png" width="100%">

本講座では技術全般を指すときに使う言葉と考えてください


---

## 2. ライブラリ

- よく使われるコードや機能を再利用できる形にまとめたもの
- フレームワークと比べると規模は小さめ
  - 学習コストが小さい
- 例
  - TKinter(Python)
  - jQuery(JavaScript)

---

## 3. フレームワーク
- 開発効率を向上するために、最低限の骨組みを用意したもの
- ライブラリは開発する上の部品に過ぎないが、
フレームワークは全体の骨組み
- 例
  - Ruby on Rails(Ruby)
  - Next.js(JavaScript)

---

## 4. フロントエンド

- フロントエンドはユーザーが直接触る部分
- ユーザーが見る画面や操作画面のこと

## 5. バックエンド
- バックエンドはユーザーが直接触らない部分
- サーバー側の処理やデータベースの呼び出しのこと
---

<div class="chapter">

# プログラミング言語たち

</div>

---

## Python
- 授業でも触れているお馴染みのプログラミング言語
- データ分析やAI開発によく使われる
- 簡潔な構文とライブラリが充実しているのが特徴

<img src="https://s3.dualstack.us-east-2.amazonaws.com/pythondotorg-assets/media/community/logos/python-logo-only.png" height="200px">

---

<div class="flex gap-20 text-3xl">

<div class="w-1/2">

## JavaScript
- フロントエンド開発で使われる
- ウェブブラウザで動作する
プログラミング言語

<img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" height="200px">

</div>

<div class="w-1/2">

## TypeScript
- JavaScriptのスーパーセット
- 静的型付けをサポート
- コードの安全性と可読性を向上

<img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg" height="200px">

</div>

---

## Java
- 授業でお馴染み
- バックエンド開発でよく使われる
- 既存の業務アプリで使われていることが多い

<div class="flex items-center gap-20">

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/30/Java_programming_language_logo.svg/1200px-Java_programming_language_logo.svg.png" height="200px">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/Duke_%28Java_mascot%29_waving.svg/1137px-Duke_%28Java_mascot%29_waving.svg.png" height="200px">

</div>

---

<div class="flex gap-20 text-3xl">

<div class="w-1/2">

## Kotlin
- Androidアプリ開発や
バックエンド開発で使われる
- Javaの後継言語

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/06/Kotlin_Icon.svg/1200px-Kotlin_Icon.svg.png" height="200px">

</div>

<div class="w-1/2">

## Swift
- iOSアプリ開発や
MacOSアプリ開発で使われる
- Objective-Cの後継言語

<img src="https://developer.apple.com/swift/images/swift-og.png" height="200px">

</div>


</div>

---

## Ruby
- バックエンド開発でよく使われる
- 様々な便利な機能が充実している言語
- 日本人が開発したプログラミング言語

<img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Ruby_logo.svg" height="200px">


---

## Go
- バックエンド開発でよく使われる
- 高速な実行速度とシンプルな構文が特徴
- バックエンドやってる学生使いがち(偏見)

<div class="flex items-center gap-20">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Go_Logo_Blue.svg/250px-Go_Logo_Blue.svg.png" height="150px">

<img src="https://upload.wikimedia.org/wikipedia/commons/2/23/Golang.png" height="150px">

</div>

---

## C言語
- 組み込みやOSなど低レイヤーな開発でよく使われる
- 教育機関で用いられるため、
初めて触るプログラミング言語がCの人が多い


<img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" height="200px">

---

## C++
- C言語の拡張版
- 高いパフォーマンスが要求される開発によく使われる
  - 組み込み開発、ゲーム開発、AI開発など

<img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" height="200px">

---

## C#
- C++の拡張と思いきやJavaのほうが近いらしい
- バックエンド開発やゲーム開発でよく使われる
- 業務システムで使われがち

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Logo_C_sharp.svg/1200px-Logo_C_sharp.svg.png" height="200px">

---



---

# まとめ

- 結論1
- 結論2
- 今後の展望 