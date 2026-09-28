# Product 19 STATUS

最終更新：2026-09-29（Discussion #48全文の再照合を反映）

## 現在の状態

**Round 2（6話プロットの確定）の統合まで完了。次工程は初稿の執筆。**

- Round 1（Discussion #47）：完了。全体構成を3話から6話（3ユニット×各2話）に変更。
- Round 2（Discussion #48）：完了。ChatGPT・Grok・MuseSpark・Qwen・Geminiが投稿。Claudeの回答はチャットで提示（Discussion未投稿。Roundファイルへ保存する前に#48へ貼り付ける）。
- Claude統合：完了。6話それぞれの「いつ・どこ・何が起きるか」「同じ形」「反転の仕掛け」「題」をCANONに反映。
- Dragon承認：【承認待ち】（承認後、この行を「承認済み（日付）」に変更する）。
- 初稿・本文：未着手。

## 現在の目的

6話の初稿（v1）を執筆し、CANON・NOT_CANONに照らして品質確認する。

次工程（Claude推奨）：Round 3（プロットの再検証）は行わず、承認後に初稿v1（全6話）を執筆し、品質確認Roundへ進む（Product 17・18と同じ運用）。

## Round 2の統合結果（要点）

- 一致点（5AI）：6話構成、B→C→A、相方を会わせない、Aで動機を書かない、物の完全一致を避ける、「6人ともその時点では間違っていなかった」。
- 全文照合の結果、ChatGPT・Grok・MuseSpark・Geminiの一致は独立した一致ではない：Grokは「ChatGPTの案をベース」と明言し、るいの題の文言もChatGPT案をそのまま踏襲（Grok自身が書いた本文の台詞とは微妙に異なる）。MuseSparkは他AI名を挙げないが、内容はChatGPT案の要約に留まり独自のシーン提案がない。Geminiはユニット B の筋（創が裏返す／るいが削除する）はChatGPT・Grokとほぼ同型だが、ユニットCの物（チョーク→トラロープ・鋲）とユニットAの細部（NDLC）では独自色を出している。Qwenは6話の場面提案を行わず、依頼文の要約とDragonへの確認質問のみ。
- CANON原文との照合で、ユニットBの核・クセの位置・題・藤原の時期を修正。ユニットAの「同じ形」を「助かる」から「紙を手渡す」に差し替え。詳細はCANONとNOT_CANON。
- 採用した他AI案：ChatGPT＝各話を一つの動作で成立させる原則・「6人ともその時点では間違っていなかった」／Grok・Gemini＝高2の冬・拓海の祭り設営・物を揃えない／Gemini＝境界標の鋲・感情を制度のフォーマットに変換する見せ方・回想を書かないルール。
- 自己利益の開示：ユニットBの核とユニットAの同じ形の差し替え案は、Claudeの回答（Discussion未投稿）に由来する。根拠はP16 CANON（6人の詳細設定・12〜14話）とP16 NOT_CANON（Round 18）の原文で確認できる。
- 参考：題はProduct 18の題の裏返しとして読める（藤原「お兄ちゃんには関係ないでしょ」→「それ、そのまま付けといてくれる？」、倫子「お前が謝ることじゃないだろ」→「その手のは、小柳さんにお願いするね」）。ルールではない。

## 現時点で把握している決定事項

Dragon決定：

- Product 19は、6人の内何人かのユニットで展開する過去ストーリー（ユニット編）として進める（2026-09-27）。
- 話数は短めにして、テンポ良く進める。
- 分量の懸念には、1話の文字数を増やさず、話数を増やして対応する（2026-09-28）。
- Round 1のClaudeの提案を承認（2026-09-28）。

## 作業分担

- ChatGPT：GitHubのP19フォルダ・初期ファイルの用意（指示書はClaudeが作成。2026-09-27）。作成状況は本ファイルでは未確認。
- Claude：Round統合、CANON／NOT_CANON／STATUSの更新案、初稿の執筆（Dragon承認後）。
- Dragon：最終確定、本文の執筆担当の決定、公開判断、GitHubへの反映。

## Round 2の参加AI

ChatGPT・Claude・Gemini・Grok・MuseSpark・Qwen（Kimi・Microsoft Copilotは不参加）。

## 執筆前に確認すること

- Product 18の各話原稿（`manuscript/`）：クセの初出（拓海・藤原・理香・るい）、語りの人称・時制、各話の字数。
- 1話あたりの分量（目安：Product 18の実測平均1,432字）。
- 題名。

## GitHub反映状況（2026-09-28）

- `CANON.md`／`NOT_CANON.md`／`STATUS.md`：Round 2版を作成。Dragon承認後、Dragonが反映する。
- `discussions/Round02.md`：Discussion #48の本文＋全コメント（Claudeの回答を含む）を保存する。

## Roundファイル運用

Product 18と同じ。Roundはフォルダを作らず、1Round＝1ファイル（`discussions/Round02.md`）。Round終了後、人間がDiscussionのトピック本文＋全コメントをマージして置き換える。議論記録をAIに別途要約・再編集させることを基本としない。
