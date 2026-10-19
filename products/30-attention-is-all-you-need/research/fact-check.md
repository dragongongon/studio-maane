# P30 調査・事実確認メモ

最終更新：2026-10-19

## 主要な一次資料
1. 原論文（arXiv）
   - https://arxiv.org/abs/1706.03762
   - 投稿日：2017-06-12
   - 著者8人、Transformer、機械翻訳実験。
2. NeurIPS 2017掲載版
   - https://proceedings.neurips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html
   - NeurIPS版の英独BLEU 28.4、英仏BLEU 41.0。
3. NeurIPSの査読記録
   - https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Reviews.html
   - 研究コミュニティ内の評価を確認する際に参照する。「誰も気づかなかった」といった一般化を避ける。
4. Google ResearchによるBERT発表
   - https://research.google/blog/open-sourcing-bert-state-of-the-art-pre-training-for-natural-language-processing/
   - 2018-11-02。
5. GoogleによるLaMDA紹介
   - https://blog.google/innovation-and-ai/products/lamda/
   - 2021-05-18。Google側の対話AI研究を説明する一次資料。
6. GPT-3論文・紹介
   - https://openai.com/index/language-models-are-few-shot-learners/
   - 2020-05-28。175 billion parameters（1,750億）。
7. ChatGPT発表
   - https://openai.com/index/chatgpt/
   - 2022-11-30。research previewとしての公開、RLHFに関する説明。
8. Noam Shazeer / Character.AI関連の報道
   - https://techcrunch.com/2024/08/02/character-ai-ceo-noam-shazeer-returns-to-google/
   - 2024年の動向を確認するための報道。現在の役職を記載する場合は追加確認する。
9. Character.AI Chapter 11に関する報道（時事記述を残す場合のみ）
   - https://www.reuters.com/legal/litigation/characterai-files-bankruptcy-agrees-sell-some-assets-disney-20-million-2026-10-13/
   - 2026-10-13付報道。記事公開直前に状況・表現を再確認し、不要なら削除する。

## 確認済み・採用方針
- 2017-06-12はarXivへの投稿日。NeurIPS 2017で発表されたことと区別する。
- BLEU値は論文バージョンにより英仏値が異なる。NeurIPS版を使うなら41.0、改訂版arXivを使うなら41.8と、バージョンを明記する。
- 「Attention Is All You Need」は誇張を含む印象的なタイトルであり、モデルがAttentionだけで構成されるという説明は誤り。
- 当時の研究者による評価と、一般社会での知名度・理解は別の軸で記述する。
- Google対OpenAIを「片方が発明を理解し、もう片方が理解できなかった」という単純な勝敗物語にしない。
- Transformerから現在の生成AIへの発展を、単一論文だけで全て説明できるかのように書かない。

## 公開前に要確認
- 8人の著者の現在の所属・職務。更新日と出典を付ける。
- Niki Parmar、Łukasz Kaiserなど、現職を断定しない。一次情報で確認できない情報は削るか、過去の経歴として出典付きで記載する。
- Character.AIの2026年の法的・事業上の動向を記載する場合、公開直前に一次資料または複数の信頼できる報道で確認する。
- 本文の各リンクが現在も有効か、公開前に確認する。
