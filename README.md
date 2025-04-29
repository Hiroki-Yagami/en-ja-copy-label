# コピーツール集 / Copy Tools Collection

[日本語](#コピーツール集) | [English](#copy-tools-collection)

# コピーツール集

## 概要

このプロジェクトは、ウェブサイト制作に必要な様々なテキストラベルを簡単にコピーできるツールセットです。英語と日本語の両方に対応しており、効率的なウェブサイト開発をサポートします。

## 主な機能

### 1. ナビゲーションラベルコピー

- メニュー項目やナビゲーションリンクのラベル
- 基本的なナビゲーション要素から高度なメニュー項目まで
- カテゴリー別に整理された豊富なラベル集

### 2. 会社概要項目コピー

- 会社概要ページの標準的な項目名
- 基本情報、沿革、経営理念など
- 企業プロフィールに必要な要素を網羅

### 3. ランディングページ項目コピー

- LP の各セクションに適したヘッドライン
- CTA ボタンのテキストバリエーション
- 効果的な LP 作成のための文言集

### 4. お問い合わせフォーム項目コピー

- フォーム要素のラベル
- エラーメッセージ
- 確認・完了画面のテキスト

## 技術スタック

- [Astro](https://astro.build/) - 静的サイトジェネレーター
- TypeScript - 型安全な開発
- CSS - モダンなスタイリング

## インストール方法

```bash
# リポジトリのクローン
git clone https://github.com/yourusername/copy-tools-collection.git

# プロジェクトディレクトリへ移動
cd copy-tools-collection

# 依存関係のインストール
npm install

# 開発サーバーの起動
npm run dev
```

## 使用方法

1. 開発サーバーを起動
2. ブラウザで `http://localhost:4321` にアクセス
3. 必要なツールを選択
4. コピーしたいラベルの「コピー」ボタンをクリック

## 特徴

- 🌐 完全なバイリンガル対応（日本語・英語）
- 📱 レスポンシブデザイン
- 🎨 モダンな UI/UX
- ⚡ 高速なパフォーマンス
- 🔍 カテゴリー別の整理された項目

---

# Copy Tools Collection

## Overview

This is a comprehensive toolset that enables easy copying of various text labels needed for website development. Supporting both English and Japanese, it helps streamline web development workflow.

## Main Features

### 1. Navigation Label Copy

- Menu items and navigation link labels
- From basic navigation elements to advanced menu items
- Rich collection of labels organized by category

### 2. Company Profile Item Copy

- Standard items for company profile pages
- Basic information, history, corporate philosophy, etc.
- Comprehensive coverage of essential corporate profile elements

### 3. Landing Page Item Copy

- Headlines suitable for each LP section
- CTA button text variations
- Collection of effective LP copy

### 4. Contact Form Item Copy

- Form element labels
- Error messages
- Confirmation and completion screen text

## Tech Stack

- [Astro](https://astro.build/) - Static Site Generator
- TypeScript - Type-safe development
- CSS - Modern styling

## Installation

```bash
# Clone repository
git clone https://github.com/yourusername/copy-tools-collection.git

# Move to project directory
cd copy-tools-collection

# Install dependencies
npm install

# Start development server
npm run dev
```

## Usage

1. Start the development server
2. Access `http://localhost:4321` in your browser
3. Select the desired tool
4. Click the "Copy" button for the label you want to copy

## Features

- 🌐 Full bilingual support (Japanese & English)
- 📱 Responsive design
- 🎨 Modern UI/UX
- ⚡ High performance
- 🔍 Items organized by category

---

## 開発者向け情報 / Developer Information

### プロジェクト構造 / Project Structure

```text
menu-card-list/
├── src/
│   ├── components/
│   │   ├── GlobalNavigation.astro
│   │   └── CopyButton.astro
│   └── pages/
│       ├── index.astro
│       ├── CopyButtonExample.astro
│       ├── CompanyProfileCopy.astro
│       ├── LandingPageLabels.astro
│       └── ContactLabels.astro
└── package.json
```

### コマンド / Commands

| コマンド / Command        | 説明 / Description                                  |
| :------------------------ | :-------------------------------------------------- |
| `npm install`             | 依存パッケージをインストール / Install dependencies |
| `npm run dev`             | 開発サーバーを起動 / Start development server       |
| `npm run build`           | 本番用ビルドを生成 / Build production site          |
| `npm run preview`         | ビルドをプレビュー / Preview built site             |
| `npm run astro ...`       | Astro CLI コマンドを実行 / Run Astro CLI commands   |
| `npm run astro -- --help` | Astro CLI のヘルプを表示 / Display Astro CLI help   |

### サポート情報 / Support Information

- 🇯🇵 詳しい情報は[Astro のドキュメント](https://docs.astro.build)をご覧いただくか、[Discord コミュニティ](https://astro.build/chat)にご参加ください。
- 🇬🇧 For more information, please check [Astro documentation](https://docs.astro.build) or join our [Discord community](https://astro.build/chat).
