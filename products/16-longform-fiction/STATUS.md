# Product 16 長編フィクション STATUS

最終更新：2026-09-03

## 現在のRound

**Round 8**

## 現在の目的

6人のキャラクターを「呪いの文法」に沿って具体設計し、Round 9以降で15話を書けるレベルまで人物設計を固める。

## 情報の優先順位

1. `CANON.md`：現在の確定設定
2. `NOT_CANON.md`：明確に不採用・除外された重要設定
3. `RoundXX.md`：各Roundの議論記録

## Roundファイル運用

Roundはフォルダを作らず、1Round＝1ファイルとする。

命名規則：

`Round01.md`
`Round02.md`
`...`
`Round08.md`

二桁固定とする。

## Roundファイルのライフサイクル

Round開始時の`RoundXX.md`は、そのRoundを実行するための**プロンプト兼コンテキスト**として使用する。

Round終了後、人間がGitHub Discussionの**トピック本文＋全コメントをマージ**し、その内容で`RoundXX.md`を置き換える。

Round終了後の`RoundXX.md`は、そのRoundの**議論記録**として保存する。

議論記録をAIに別途要約・再編集させることを基本としない。

## CANON更新

各Round終了後、議論で確定した内容を`CANON.md`へ反映する。

`CANON.md`の更新は、可能な限りAIに実施させる。AIは「確定」「未確定」「不採用」を区別し、提案段階の設定をCANONへ混入させない。

最終的な確定判断はオーナーが行う。

## 基本ワークフロー

`CANON.md`
↓
`RoundXX.md`（実行用プロンプト）
↓
GitHub Discussion（実際の議論）
↓
AIによるCANON更新
↓
人間がDiscussion本文＋全コメントを`RoundXX.md`へ保存

次Roundでは、更新済み`CANON.md`を一次情報として新しい`RoundXX.md`を作成する。
