# P30 調査・事実確認メモ

最終更新：2026-10-20

## 主要な一次資料
1. 原論文（arXiv）
   - https://arxiv.org/abs/1706.03762
   - 投稿日：2017-06-12
   - 著者8人、Transformer、機械翻訳実験。
2. NeurIPS 2017掲載版PDF
   - https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf
   - Table 2のTransformer big：英独BLEU 28.4、英仏BLEU 41.0。
3. NeurIPS HTML要旨ページ
   - https://papers.nips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html
   - 単一モデル（165 million parameters）の英独BLEU 27.5、英仏BLEU 41.1。PDF Table 2のTransformer bigとモデル設定が同一とは限らないため、数字を混同しない。
4. NeurIPSの査読記録
   - https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Reviews.html
   - 研究コミュニティ内の評価を確認する際に参照する。「誰も気づかなかった」といった一般化を避ける。
5. Google ResearchによるBERT発表
   - https://research.google/blog/open-sourcing-bert-state-of-the-art-pre-training-for-natural-language-processing/
   - 2018-11-02。
6. GoogleによるLaMDA紹介
   - https://blog.google/innovation-and-ai/products/lamda/
   - 2021-05-18。Google側の対話AI研究を説明する一次資料。
7. GPT-3論文・紹介
   - https://openai.com/index/language-models-are-few-shot-learners/
   - 2020-05-28。175 billion parameters（1,750億）。
8. ChatGPT発表
   - https://openai.com/index/chatgpt/
   - 2022-11-30。research previewとしての公開、RLHFに関する説明。
9. Noam Shazeer / Character.AI関連の報道
   - https://techcrunch.com/2024/08/02/character-ai-ceo-noam-shazeer-returns-to-google/
   - 2024年の動向を確認するための報道。現在の役職を記載する場合は追加確認する。
10. Character.AI Chapter 11に関する報道（時事記述を残す場合のみ）
   - https://www.reuters.com/legal/litigation/characterai-files-bankruptcy-agrees-sell-some-assets-disney-20-million-2026-10-13/
   - 2026-10-13付報道。記事公開直前に状況・表現を再確認し、不要なら削除する。

## 確認済み・採用方針
- 2017-06-12はarXivへの投稿日。NeurIPS 2017で発表されたことと区別する。
- BLEU値は参照ページとモデル設定を明示する。NeurIPS PDF Table 2のTransformer bigは英独28.4／英仏41.0、NeurIPS HTML要旨の単一モデルは英独27.5／英仏41.1、arXiv改訂版要旨は英仏41.8。単純な「版違い」だけで説明しない。
- 「Attention Is All You Need」は誇張を含む印象的なタイトルであり、モデルがAttentionだけで構成されるという説明は誤り。
- 当時の研究者による評価と、一般社会での知名度・理解は別の軸で記述する。
- Google対OpenAIを「片方が発明を理解し、もう片方が理解できなかった」という単純な勝敗物語にしない。
- Transformerから現在の生成AIへの発展を、単一論文だけで全て説明できるかのように書かない。

## 公開前に要確認
- 8人の著者の現在の所属・職務。更新日と出典を付ける。
- Niki Parmar、Łukasz Kaiserなど、現職を断定しない。一次情報で確認できない情報は削るか、過去の経歴として出典付きで記載する。
- Character.AIの2026年の法的・事業上の動向を記載する場合、公開直前に一次資料または複数の信頼できる報道で確認する。
- 本文の各リンクが現在も有効か、公開前に確認する。

## 公開前リンク・事実確認ログ（2026-10-21）

### 今回、本文内容または検索結果で確認できた資料
- arXiv原論文：https://arxiv.org/abs/1706.03762 — 投稿履歴に2017-06-12、改訂版v7の日付、著者8名を確認。
- NeurIPS 2017掲載版PDF：https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf — 冒頭に8人のequal contribution／掲載順ランダムの注記、Abstractに英独28.4・英仏41.0を確認。
- NeurIPS査読記録：https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Reviews.html — 査読者の一人が「すでにコミュニティの話題で、多くの人が再現を試みている」と記述。研究コミュニティ内の反応を「無風」と描くのは不適切。ただし、この査読記録だけで一般社会の認知度は判断できない。
- BERT論文：https://arxiv.org/abs/1810.04805 — arXivページでタイトル・投稿日2018-10-11を確認。Google ResearchのBERT発表記事は検索結果から2018-11-02と確認。
- GPT-3紹介：https://openai.com/index/language-models-are-few-shot-learners/ — OpenAIページで2020-05-28、GPT-3の175 billion parametersを確認。
- ChatGPT発表：https://openai.com/index/chatgpt/ — OpenAIページで2022-11-30、research previewおよびRLHFの説明を確認。
- LaMDA紹介：https://blog.google/innovation-and-ai/products/lamda/ — Google公式ページが閲覧可能。
- Google Bard発表：https://blog.google/innovation-and-ai/technology/ai/bard-google-ai-search-updates/ — Google公式ページの公開日2023-02-06と、LaMDAを用いた実験的対話サービスとしての説明を確認。
- Google Researchの原論文紹介：https://research.google/pubs/attention-is-all-you-need/ — ページは開いたが、本文抽出上は論文詳細が十分に確認できず。原論文の一次資料としてはarXiv／NeurIPS PDFを優先。
- Essential AI／Rnj-1：https://www.essential.ai/about ／ https://essential.ai/research/rnj-1 — 公式ページでRnj-1発表日2025-12-05、Ashish Vaswani名義、モデル紹介を確認。
- Noam Shazeer本人プロフィール：https://www.noamshazeer.com/ — 2026-10-21時点でOpenAIのcomputer scientist／entrepreneurとして紹介されている。
- Sakana AI：https://sakana.ai/company-info/?lang=en — 公式会社概要でLlion Jonesを共同創業者兼CTOと記載。
- Cohere：https://cohere.com/about — 公式Aboutページは閲覧可能。今回の抽出範囲ではAidan Gomezの現在のCEO肩書きを直接確認できなかったため、公開直前に人物／Leadership欄を再確認する。
- Inceptive：https://inceptive.com/ — 公式サイトでAIと生化学を用いた生物学的医薬品設計という事業説明を確認。共同創業者の現職肩書きは断定しない。
- AlnylamとInceptiveの提携：https://alnylampharmaceuticalsinc.gcs-web.com/news-releases/news-release-details/alnylam-and-inceptive-form-strategic-ai-collaboration-accelerate — 2026-06-03付の公式発表を確認。
- OpenAI Forum：https://forum.openai.com/en/public/videos/event-replay-learning-powerful-models-from-transformers-to-reasoners-and-beyond-2025-10-06 — イベントページが開く。
- NEAR：https://near.org/blog/nvidia-gtc-2025 — NEAR公式ページのタイトルとIllia Polosukhinの発表を確認。
- Character.AI公式発表：https://blog.character.ai/an-update-on-character-ai/ — 2026-10-12付でChapter 11手続き開始、裁判所監督下の売却手続き、発表時点ではサービス継続中と説明。
- Reuters：https://www.reuters.com/technology/artificial-intelligence/rise-fall-an-ai-chatbot-darling-2026-10-14/ — 検索結果で2026-10-14付のCharacter.AIに関する記事を確認。閲覧ツールでは記事本文を直接開けなかったため、詳細の裏付けは公式発表と照合する。

### 未完了・注意
- 今回の確認は閲覧ツール上のページ表示・検索結果を用いた監査であり、全リンクを実端末ブラウザで開いた確認ではない。ツールのアクセスエラーはリンク切れを意味しない。
- 第4部の公開直前には、Aidan Gomezの肩書き、8人全員の現況、Character.AIの法的手続きとサービス状況を再確認する。
- 「2026年10月19日時点で確認」と本文に書く場合、その基準日を維持するか、公開日へ更新する。
- 参照リンクの全件監査とnote上のスマートフォン表示確認は未完了。
