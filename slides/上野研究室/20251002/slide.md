---
marp: true
theme: mytheme
paginate: true

---
<script src="https://cdn.tailwindcss.com/3.0.16"></script>
<script>tailwind.config = { corePlugins: { preflight: false } }</script>

<div class="title">

# 上野研究室ミーティング
## 次のアクション候補
学習支援プラットフォーム改善に向けて

</div>

---

# 今日の焦点
- 演習・評価・計画・体験の4領域を整理
- 各領域の課題とゴールを共有

---

# 演習問題の整備
- `exercises/` を基礎→応用へ段階化
- `problem.md` / `solution.js` / `solution.test.js` のテンプレ統一

---

# 自動評価フロー
- MCP経由でJestを実行し結果を取得
- テスト失敗理由をLLMで自然言語フィードバック
- エディタ内で「再挑戦」ループを回せる仕組みを試作

---

# 学習計画との接続
- `plan/learning-plan.md` の内容を演習生成に反映
- `goals.md` を基に出題難易度を制御
- 演習履歴をログ化して学習進捗を可視化

---

# VSCode専用MCP実装
- VSCodeのチャットから問題生成・テスト実行・FBを操作
- `problem.md` と `solution.js` を自動で開くフロー
- 学習体験をVSCode内で完結させるUXを検証
