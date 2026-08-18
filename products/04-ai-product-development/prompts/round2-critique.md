# Product 4 Round 2 Prompt：作品批評コンペ

## 経緯

Product 4は「おもしろうんちく地政学。」に刷新された。旧企画は不採用であり、旧Outputは現在の企画の決定事項ではない。

Round 0でお題を決め、Round 1で7AIが同じお題について独立した作品を作った。

Round 2では、その7作品をAI同士で批評する。

## 任務

以下のRound 1作品を読み、あなたの基本役割の観点から公平に評価する。

- `products/04-ai-product-development/output/chatgpt/round1.md`
- `products/04-ai-product-development/output/claude/round1.md`
- `products/04-ai-product-development/output/gemini/round1.md`
- `products/04-ai-product-development/output/grok/round1.md`
- `products/04-ai-product-development/output/qwen/round1.md`
- `products/04-ai-product-development/output/kimi/round1.md`
- `products/04-ai-product-development/output/musespark/round1.md`

さらに、自分より前のAIが作成したRound 2批評ファイルが存在する場合は、それも読む。

実行順：

ChatGPT → Claude → Gemini → Grok → Qwen → Kimi → MuseSpark

したがって、後ろのAIほど前のAIの批評を読んだ状態で評価することになる。

### 前のAIの批評ファイル

- `products/04-ai-product-development/output/chatgpt/round2.md`
- `products/04-ai-product-development/output/claude/round2.md`
- `products/04-ai-product-development/output/gemini/round2.md`
- `products/04-ai-product-development/output/grok/round2.md`
- `products/04-ai-product-development/output/qwen/round2.md`
- `products/04-ai-product-development/output/kimi/round2.md`

自分自身のファイルは読めなくても構わない。

## 評価

共通評価軸：

- 面白さ
- 意外性
- 分かりやすさ
- 地政学的な正確性
- 説得力
- 読者価値
- 構成
- 読みやすさ
- 事実と推測の区別
- note記事としての魅力

さらに、自分の基本役割に応じた評価を重視する。

## 重要

- 自分の作品を贔屓しない
- 「AIだから自分が優秀」という評価をしない
- 他AIが優れていれば明確に認める
- 面白さと正確性のトレードオフを指摘する
- 他AIの批評そのものに妥当性があるかも検討する
- 前のAIの評価に盲従しない
- 実際のファイルにない発言を捏造しない

## 出力

`products/04-ai-product-development/output/<あなたのAI名>/round2.md`

以下を含める。

1. 各作品の批評
2. 各作品の長所
3. 各作品の弱点
4. 事実確認上の問題
5. 総合順位
6. 順位の理由
7. 前のAIの批評への同意・反論
8. 最優秀作品候補
9. 無料公開するならどれか
10. 改善すれば最も伸びる作品
11. 自分の作品への最も厳しい評価

最終判定は人間が行う。