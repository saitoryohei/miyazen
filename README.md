# 宮古島 日本料理店 LP (Minimal Static Website)

宮古島に佇む、日本料理・寿司・手打ち蕎麦を提供する本格和食店のランディングページ（LP）です。
無駄なシステムを一切排除した「ピュアな静的HTML/CSS/JS」の構成で、軽量かつモダンなデザインを実現しています。

## 核心設計（Core Concept）

* **引き算の美学 (Minimalism):** 装飾を極限まで削ぎ落とし、余白とフォントの美しさで店の格を表現。
* **ネイチャー・ラグジュアリー:** 宮古島の静かな自然と、職人の実直な佇まい（さりげない店主写真の配置）の融合。
* **運用コスト・ゼロ:** 外部予約システム等を使わず、最新情報やゲリラランチの導線をすべて公式Instagramへ集約。

## ディレクトリ構造

```text
├── index.html          # ページの骨組み（セマンティックなHTML5）
├── style.css           # スタイリング、レスポンシブ（Flexbox/Grid）、モダンカラー
├── main.js             # Intersection Observerによる超軽量フェードイン演出
└── images/             # 各種ビジュアル（WebPフォーマット推奨）
    ├── logo.webp       # 店舗ロゴ
    ├── hero-bg.webp    # ファーストビュー背景（宮古島の空気感、または象徴的な一皿）
    ├── owner.webp      # 店主の佇まい（さりげなく配置用）
    ├── dish1.webp      # 料理写真 1
    ├── dish2.webp      # 料理写真 2
    └── dish3.webp      # 料理写真 3

技術スタック & 仕様
•	Markup: HTML5 (Semantic Tags)
•	Styling: CSS3 (Modern Flexbox & CSS Grid, Mobile-First Native Responsive)
•	Animation: Vanilla JavaScript (No jQuery / Native Intersection Observer API)
•	Font: Google Fonts (Noto Serif JP - 300 / 500)
•	Performance: 画像のWebP化による次世代フォーマット最適化、スマホ用固定コンバージョンフッター搭載
ローカル開発（Local Development）
	1.	このリポジトリをクローンします。
	2.	VS Codeで開き、拡張機能 Live Server 等を用いてローカル環境でプレビューしてください。
git clone <your-repository-url>

デプロイ方法 (Deployment)
本プロジェクトは完全に静的なファイルのみで構成されているため、GitHubと連携させるだけで以下のホスティングサービスへ一瞬でデプロイ（世界へ公開）可能です。
•	Vercel (推奨): GitHubリポジトリをインポートするだけで自動ビルド。main ブランチへの git push に連動して即時本番反映されます。
•	GitHub Pages: リポジトリの設定（Settings > Pages）からソースを main ブランチに指定するだけで公開可能です。
ライセンス
Copyright (c) 2026 Shonan AI Planning. All rights reserved.
