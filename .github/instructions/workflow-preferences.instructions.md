---
description: "Use when making code or UI changes, preparing commit messages, or running terminal commands in this workspace. Covers commit format, design consistency, and command execution."
---

# 作業時の指示

## コミットメッセージ

- `半角英字prefix: 日本語の説明` 形式で、説明は簡潔にする。
- prefix は `feat`（機能追加）、`fix`（不具合修正）、`style`（見た目調整）、`refactor`（構造整理）、`docs`（文書変更）から選ぶ。
- 適切な prefix がなければ、日本語だけでもよい。
- 例: `feat: 曜日チェックを追加` / `fix: タイマー停止の不具合を修正`

## 既存デザインとの整合性

- 提示された画像・SVG・コードなどのサンプルは意図や機能の参考として扱い、外観をそのまま流用しない。
- 色・寸法・線幅・余白・質感などは既存デザインに合わせ、指定された意味や機能は保つ。

## ターミナル実行

- ターミナルではコマンドを1つずつ個別に実行する。
- セミコロン（`;`）や `&&` で複数コマンドを連結しない。
