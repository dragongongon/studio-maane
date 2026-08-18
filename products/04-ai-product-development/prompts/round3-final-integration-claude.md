# Product 4 Round 3 Prompt：最終統合・記事化（Claude）

## 経緯

Product 4の旧企画「7つのAIに、ひとつの商品を本気で作らせてみた」は不採用となった。

現在の企画は「おもしろうんちく地政学。」。

この企画では、AI同士のやり取り自体を技術解説として売るのではなく、AIコンペを通じて生まれた面白い読み物を読者価値の中心にする。

今回の流れは、

Round 0：7AIがお題候補を出し、互いに批評 → 人間がお題を決定
Round 1：7AIが同じお題について独立して執筆
Round 2：7AIが作品を批評し、前のAIの批評にも反応
Round 3：Claudeが全体を統合し、note記事にする

である。

## あなたの任務

Round 3の最終統合担当として、Round 0〜2の資料をすべて読み、AIコンペそのものが面白い物語として成立するnote記事を作る。

## 読む資料

### 企画情報

- `products/04-ai-product-development/STATUS.md`
- `products/04-ai-product-development/input.md`

### Round 0

- `products/04-ai-product-development/output/chatgpt/round0.md`
- `products/04-ai-product-development/output/claude/round0.md`
- `products/04-ai-product-development/output/gemini/round0.md`
- `products/04-ai-product-development/output/grok/round0.md`
- `products/04-ai-product-development/output/qwen/round0.md`
- `products/04-ai-product-development/output/kimi/round0.md`
- `products/04-ai-product-development/output/musespark/round0.md`

お題候補批評：

- `products/04-ai-product-development/output/chatgpt/round0-critique.md`
- `products/04-ai-product-development/output/claude/round0-critique.md`
- `products/04-ai-product-development/output/gemini/round0-critique.md`
- `products/04-ai-product-development/output/grok/round0-critique.md`
- `products/04-ai-product-development/output/qwen/round0-critique.md`
- `products/04-ai-product-development/output/kimi/round0-critique.md`
- `products/04-ai-product-development/output/musespark/round0-critique.md`

### Round 1

各AIの `round1.md`

### Round 2

各AIの `round2.md`

## 重要な注意

GitHubから一部ファイルが読めない場合は、そのファイルを推測で補完してはいけない。対象ファイルのパスを明示し、人間に内容の提示を依頼する。

実際のOutputに存在しないAIの発言・評価・会話を作ってはいけない。

## 記事の目的

読者に売るものは「AIの使い方」ではない。

読者が楽しめる、地政学うんちくのコンテンツと、そこに至るAIコンペの物語である。

読者に、

「次のコンペも見たい」

と思ってもらうことを目標とする。

## 記事構成の基本

### 無料部分

1. 今回の企画を始めた理由
2. 7AIにお題を考えさせた
3. お題候補の比較
4. 人間が今回のお題を決めた
5. 7AIがそれぞれ作品を書いた
6. 作品の特徴を紹介
7. AI同士の批評開始
8. 評価が割れたポイント
9. 意外な批評・逆転・自画自賛・自己否定など
10. 最終順位
11. 最優秀作品を無料公開

### 有料部分

基本的には、最優秀作品以外の作品と、より詳細なコンペ記録を掲載する。

候補：

- 2位以下の作品
- 各AIの詳細な批評
- 採点の詳細
- AIによる評価の食い違い
- 面白かった反論
- ボツ案
- 作品ごとの弱点
- 最終順位に至った理由
- 次回に向けた改善点

ただし、無料部分だけでも読者が満足できることを優先し、有料部分には明確な追加価値を持たせる。

## 最優秀作品について

最初のシリーズでは、最優秀作品を無料公開することを基本案とする。

ただし、最終的に有料化した方が商品として合理的だと判断する場合は、その理由を明確に示し、人間に判断を委ねる。

## 記事のトーン

- 軽快
- 面白い
- 少し自虐的
- 読みやすい
- AIを神格化しない
- AIの失敗も隠さない
- 技術解説に寄りすぎない
- 地政学については正確性を重視

「AIのすごさ」を見せる記事ではなく、「AI同士を競わせたら、こんな面白いことになった」という読み物にする。

## note向け表現

noteでそのまま使いやすいMarkdown・見出し・箇条書きを使う。

複雑なHTMLや特殊なMarkdownに依存しない。

## 公開時の名称

内部名称「スタジオまあね」は公開記事では使用しない。

「このチーム」「今回のAIチーム」「7つのAI」などに置き換える。

## 出力

`products/04-ai-product-development/output/claude/round3-final.md`

以下を含める。

1. 完成したnote記事
2. 無料部分と有料部分の境界
3. 有料部分に置く理由
4. 記事タイトル候補3案
5. 推奨タイトル
6. 最優秀作品を無料にすることへの評価
7. 記事としての弱点
8. 次回シリーズへの改善提案

最後に、今回の記事を商品として成立させるために人間が判断すべき事項を整理する。