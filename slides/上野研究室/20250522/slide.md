---
marp: true
theme: mytheme
paginate: true

---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>



<div class="title">

# 06月06日上野研究室ミーティング
</div>
<div class="info">

**2025年06月06日**
伊藤 潤平
</div>

---

# 目次

<div class="contents">

1. プログラミング学習手法の提案
2. 想定ユーザー
3. 対象とする技術
4. jest-eval-lab
5. デモ

</div>

---

# プログラミング学習手法の提案
研究内容を振り返り
- プログラミング学習において、
LLMを活用した**個別最適化型**の演習手法を提案。
- 学習者のレベルに応じた問題を**自動生成**し、
柔軟に学習設計を調整可能。
- テストコードとLLMにより**自動評価・フィードバック**も行い、
効率的な学習を支援。

---

# 想定ユーザー
## 対象
- 大学1~2年生
- プログラミングの初学者
## 目的
- プログラミング言語の基本文法理解
- 演習による定着

---

# 対象とする技術

## JavaScript
- 初学者向きである
- 1~2年生は授業で触れておらず、
  実験開始時点での習熟度によらない結果が期待できる
- IT業界でよく使われており学ぶ意義が大いにある

---

# jest-eval-lab

- **目的**：
  - LLMとJestを用いた、
習熟度に応じたプログラミング学習支援システム。

- **特徴**：
  - 問題を自動生成し、Jestで即時評価。
出題→解答→評価→フィードバック→再挑戦のサイクルで学習を促進。

---

<div class="chapter">

# デモ

</div>

---


<div class="chapter">

# おわり

</div>