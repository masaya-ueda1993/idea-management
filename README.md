# アイデア・プロジェクト管理

アイデアの記録から設計・実装・リリースまでを管理するドキュメントリポジトリです。

## 管理ツール

| ツール | 用途 | リンク |
|---|---|---|
| スプレッドシート | 一覧・ステータス管理 | [アイデア・プロジェクト管理](https://docs.google.com/spreadsheets/d/15gCs9405UjB0BMl_WJZv3OADydimtAhvd8euhG-g06k/edit) |
| GitHub（このリポジトリ） | 詳細ドキュメント・履歴管理 | [idea-management](https://github.com/masaya-ueda1993/idea-management) |
| Claude | アイデア相談・設計 | [Claude Project]() |

## フォルダ構成
```
idea-management/
├── ideas/        # アイデアごとのメモ
└── projects/     # プロジェクトごとの設計書・ログ
```

## ステータス定義

### プロジェクト
`検討中` → `設計中` → `実装中` → `リリース済` → `保留`

### アイデア
`アイデア` → `検討中` → `プロジェクト昇格` → `保留`
