# 02_HTML_CSS

---

## 1. 概要

**静的なタスク一覧ページ** を題材に、HTML と CSS の基礎からレスポンシブデザインまで段階的に学びます。フォームや JavaScript を一切使わず、純粋にマークアップとスタイリングのみで「カード表示 → テーブル表示」へ切り替わる業務システム風 UI を作成することがゴールです。

---

## 2. 学習ゴール

| #   | カテゴリ                  | 到達目標                                                                     |
| --- | ------------------------- | ---------------------------------------------------------------------------- |
| 1   | セマンティックHTML        | `<header>`, `<nav>`, `<table>` などを意味に沿って正しく使える                |
| 2   | レイアウト & レスポンシブ | Flexbox と CSS Grid を用いてモバイル〜デスクトップに対応した UI を構築できる |

---

## 3. 前提条件

* VS Code などのテキストエディタ操作ができる
* Git の基本コマンド（clone / branch / commit / push）が分かる

---

## 4. 課題一覧

| #   | 説明                                     | 完了条件                                                                           |
| --- | ---------------------------------------- | ---------------------------------------------------------------------------------- |
| 1   | GitHub リポジトリ作成 & 初期セットアップ | 空のリポジトリを作成し、`index.html` と `assets/` フォルダを含む初回コミットがある |
| 2   | 基本 HTML 骨組み                         | `index.html` に `<header>`, `<main>`, `<footer>` を配置し、ブラウザで表示される    |
| 3   | CSS リセット & ベーススタイル            | `assets/css/base.css` をリンクし、リセット＋タイポグラフィが反映されている         |
| 4   | タスクリスト (モバイルカード) 実装       | 幅 768px 未満でカード形式のタスクリストが崩れず表示される                          |
| 5   | タスクリスト レスポンシブテーブル化      | 幅 768px 以上でタスクリストがテーブル表示に切り替わり、ヘッダが固定される          |
| 6   | GitHub Pages デプロイ                    | GitHub Pages でサイトが公開され、README に URL と操作手順を追記                    |

---

## 5. 環境構築

* 必要ツール: VS Code, Git, 任意のブラウザ (Chrome 推奨)
* 推奨拡張: Live Server, stylelint

---

## 6. 成果物

1. **タスク一覧ページのソースコード**
    1. `index.html`, `assets/css`, `assets/img` など一式
2. **ドキュメント類**
    1. README.md (セットアップ手順・公開 URL 記載), ワイヤーフレーム画像 (任意)

---

## 7. 推奨リソース

* [MDN Web Docs – HTML Tables](https://developer.mozilla.org/ja/docs/Web/HTML/Element/table){target="_blank"}
* [CSS-Tricks – A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/){target="_blank"}
* [CSS-Tricks – A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/){target="_blank"}
* [Deque University – ARIA Cheat Sheet](https://dequeuniversity.com/resources/aria/){target="_blank"}
