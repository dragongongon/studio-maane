# ファイル管理方針準拠 調査結果

**Product:** ai-side-business-note
**AI:** metaspark
**Date:** 2026-08-14
**Path:** products/ai-side-business-note/outputs/metaspark/2026-08-14_file-management-audit.md

## 結論
- リポジトリ構造は方針通りだが、COMPANY_POLICY.mdとagents/*.mdの実体が未確認。
- Product名は `ai-side-business-note` に統一が必要。
- 今後のOutputは必ず `products/ai-side-business-note/outputs/<AI名>/` に日付付きで保存。

## 根拠
- GitHub Topで company/, products/ai-side-business-note/, README.md を確認。
- READMEに「input.md → 7AI outputs → 統合AI → final/product.md」と明記。

## 確認済み情報
- リポジトリURL: https://github.com/dragongongon/studio-maane
- Productフォルダ名は ai-side-business-note
- 7AI構成: ChatGPT, Claude, Gemini, Grok, Qwen, Kimi, MuseSpark

## 仮説・推測
- company/内にCOMPANY_POLICY.mdがあると推測
- agents/フォルダは未作成かcompany配下の可能性
- shared/フォルダは未作成の可能性

## リスク
- ファイル名不統一による誤保存
- COMPANY_POLICY.md未整備によるAIの暴走 (課金・公開)
- 他AI Outputの上書きによる履歴消失

## 推奨
1. 命名統一: ai-side-business-note に統一
2. COMPANY_POLICY.md作成
3. agents/metaspark.md作成
4. input.md確認・作成
5. outputs/metaspark/, shared/decisions/, shared/research/, shared/knowledge/ 作成

## 他AIへの申し送り
- MetaSparkは監査を実施。基本構造は準拠。
- 他AIは作業前にCOMPANY_POLICY.md, agents/<自分>.md, input.md, shared/, 他AI outputsを確認すること。
- 売上に繋がるかを常に自問すること。