# P30 原稿レビュー記録（2026-10-19）

## レビュー対象
- `manuscript/1.md` 第1部「論文の向こう側にあった未来」
- `manuscript/2.md` 第2部「世界は、まだ気づいていなかった」
- `manuscript/3.md` 第3部「発明した者と、世界に届けた者」
- `manuscript/4.md` 第4部「八人は、同じ未来を選ばなかった」

本メモは初回レビュー。原稿本文はまだ編集していない。確定事実・修正候補・表現上の提案を分け、原稿の語り口を維持しながら段階的にブラッシュアップする。

## 優先度A：公開前に修正・再確認が必要

### 1. 第4部：Noam Shazeerの現在の所属
現行稿：
> 「その後の本人の公開プロフィールでは、OpenAIのAI研究者として紹介されている。」

2026-10-19時点で確認できた信頼できる資料では、この記述を裏づけられていない。2024年の報道では、ShazeerがGoogle DeepMindに戻ったと報じられている。OpenAI所属という記述は、誤記または古い情報の可能性があるため、本人・所属先の一次資料を確認するまで削除または保留する。

参考：
- Reuters（Character.AIの創業者と2024年のGoogleとの契約を含む背景）：https://www.reuters.com/technology/artificial-intelligence/rise-fall-an-ai-chatbot-darling-2026-10-14/
- TechCrunch（2024年のGoogle復帰報道）：https://techcrunch.com/2024/08/02/character-ai-ceo-noam-shazeer-returns-to-google/

### 2. 第4部：Character.AIのChapter 11手続き
2026年10月にChapter 11を申請したという記述は、2026-10-14付Reutersなどの報道で確認できる。現行稿の記述は概ね方向性が合っているが、公開時には報道日・出典を明示し、申請を「会社の技術的価値がなかった証拠」として扱わない。運営コスト・法的問題などの要因を述べる場合は、報道が具体的に裏づける範囲に限定する。

参考：
- Reuters, 2026-10-14：https://www.reuters.com/technology/artificial-intelligence/rise-fall-an-ai-chatbot-darling-2026-10-14/
- Wall Street Journal：https://www.wsj.com/tech/ai/character-ai-maker-files-for-chapter-11-bankruptcy-740e6fb1

### 3. 第4部：著者の現職・肩書き全般
Ashish Vaswani、Niki Parmar、Llion Jones、Aidan Gomez、Jakob Uszkoreit、Łukasz Kaiser、Illia Polosukhinの現在の所属や役職は、公開直前に本人または組織の一次資料で再確認する。特に「近年では」「現在」「CEOを務めている」などの現在形は更新されやすい。確認できない役職や活動は、断定を避けるか、確認日付きの表現にする。

確認済みの例：
- Essential AIは2025年12月にRnj-1を発表し、Ashish Vaswaniの関与を公式サイトで紹介：https://www.essential.ai/
- Sakana AIの公式会社情報は、Llion Jonesを共同創業者・CTOとして掲載：https://sakana.ai/company-info/?lang=en
- Cohereの公式ページは、Aidan Gomezを共同創業者・CEOとして掲載：https://cohere.com/about

## 優先度B：精度・読みやすさの改善候補

### 4. 第1部：BLEU値の版を明示する
現行稿の「英独28.4、英仏41.0」はNeurIPS 2017掲載版に対応するため、誤りではない。引用先をNeurIPS掲載版に揃えるか、「NeurIPS 2017掲載版では」と明記すると、現在のarXiv改訂版に記載された英仏41.8との混同を防げる。

参考：
- Google Research（28.4 / 41.0）：https://research.google/pubs/attention-is-all-you-need/
- arXiv v7（28.4 / 41.8）：https://arxiv.org/abs/1706.03762

### 5. 第1部：「タイトルの意味」の説明
「Attention Is All You Need」は論文の強い主張を表すタイトルとして説明されている。TransformerがAttention以外の要素も持つ点は原稿内で説明済みなので、内容上の大きな問題はない。ただし、論文要旨の「solely based on attention mechanisms」は、再帰・畳み込みを使わないという意味であり、Attention演算だけでモデル全体が構成されるという意味ではない。現行稿の説明を維持しつつ、読者が誤解しない表現を最終稿で確認する。

### 6. 第2部：「世界は、まだ気づいていなかった」
冒頭で一般社会の認知と専門家の評価を区別しているのは適切。公開査読記録を引用する箇所は、リンクを追加し、査読者の評価を「研究者全体の総意」として一般化しない。

参考：
- NeurIPS 2017論文ページ：https://papers.nips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html
- 査読記録：https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Reviews.html

### 7. 第3部：GoogleとOpenAIの対比
現行稿は「Googleは気づかなかった」という単純な説明を避けており、基本方針は適切。Googleの社内意思決定について、確認できない動機を事実として書かず、「外部から考えられる要因」と明記する現行の留保を維持する。

## 優先度C：編集工程で確認

- 4部の参考資料を、記事内の主要な事実主張と直接対応させる。現状のように資料名だけのリストでは読者が原典を見つけにくいため、クリックできるURLにする。
- 各部の末尾に、次の部へ自然につながる短い導線を設けるか検討する。物語性を過剰に煽らない。
- 「発明」「研究成果」「製品化」「事業化」を同義語のように使わず、各部の主題に合わせて区別する。
- 第4部の人物紹介は、現在の肩書きの羅列になりすぎないよう、2017年の共同研究と各人の進路の関係を明確にする。
- 4部共通で、公開前にリンク切れ、表記ゆれ（Łukasz/Lukasz等）、人名表記、英語タイトルの大文字小文字を確認する。

## 進め方
1. 本レビュー記録を基に、まず優先度Aの事実確認を完了する。
2. 原稿本文を変更する場合は、差分が追える形で更新し、必要に応じて変更理由を記録する。
3. 4部の本文と特別編を通読し、重複と導線を整える。
4. 公開・販売はオーナーの明示承認まで行わない。
