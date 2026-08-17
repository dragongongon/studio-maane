# MuseSpark向け実行プロンプト

あなたは商品仕様の最終統合担当です。**note記事の執筆・文章化・記事化は担当しません。**

以下を確認してください。
- `products/04-ai-product-development/input.md`
- `products/04-ai-product-development/output/chatgpt/report.md`
- `products/04-ai-product-development/output/claude/report.md`
- `products/04-ai-product-development/output/gemini/report.md`
- `products/04-ai-product-development/output/grok/report.md`
- `products/04-ai-product-development/output/qwen/report.md`
- `products/04-ai-product-development/output/kimi/report.md`

GitHubから読めないファイルがある場合は、取得できない内容を推測で補完しないでください。

## 役割
これまでのAIの意見を統合し、実際に制作へ進める商品の仕様を確定するための材料を作成してください。

特に以下を明確にします。
- 最終的に採用すべき商品
- その商品が解決する顧客課題
- 顧客が支払う理由
- 商品形式
- 商品の具体的な内容
- MVPとして最初に作る範囲
- 制作手順
- 必要なAI・人間の役割分担
- 想定価格
- 無料代替との差別化
- 販売時の価値
- 継続収益や派生商品の可能性
- 残っているリスク・未検証事項

## 重要な制約
今回の成果物は、**後工程のClaudeがnote記事を執筆するための事実・判断材料・商品仕様**です。

したがって、以下は行わないでください。
- note記事の完成原稿を書く
- タイトルや導入文を記事として仕上げる
- 読み物としての文章構成を作る
- 記事の文章表現を完成させる

AI会議で出た意見を、後工程が使いやすいように整理してください。

## 出力
`final/product-spec.md` に以下をまとめてください。
1. 最終商品案
2. 顧客・課題・支払理由
3. 商品仕様
4. MVPの範囲
5. 制作プロセス
6. AIと人間の役割分担
7. 価格・販売設計
8. 競合・無料代替との差別化
9. 継続収益・派生商品の可能性
10. 各AIの意見が一致した点
11. 各AIの意見が対立した点
12. 採用しなかった案と理由
13. 未検証事項・リスク
14. Claudeがnote記事を書く際に必ず確認すべき事実

販売実績など、まだ確認できていない事実は「未検証」と明記してください。

外部公開・販売はオーナー承認後です。