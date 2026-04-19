# Day052 Story — Handoff Gap Checker

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day052専用にテーマをseed固定して再生成時の見た目を安定化
- planning用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: handoff_gap_check
- Mechanic: filter_toggle
- Input/Output: listing_cards -> choice_cards
- Audience Promise: 渡す前に不足項目を洗い出せる。
- Publish Hook: 引き継ぎ項目を自分で追加・編集すると、不足しやすい観点が横で警告されて抜けを先に見つけられる。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day052｜引き継ぎ抜け見張り
引き継ぎの抜けを見つけやすくするためのツールです。
