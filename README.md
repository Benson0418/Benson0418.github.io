## [網站](https://itousouta15.github.io)
## Language | 語言 | 言語

- [繁體中文](#zh-TW)
- [English](#english)
- [日本語](#Japanese)

<a name="zh-TW"></a>

# 繁體中文 🇹🇼

## 關於本站

這個部落格是我個人的學習筆記與技術分享空間，內容包含：

 ⚔️ 資安相關筆記與心得

 💻 C++、網頁前端等技術記錄

 🏫 學生生活與學習歷程

 👾 實作練習與 Side Project 紀錄


我希望透過這個部落格整理知識、分享經驗，並持續提升自己在開發與寫作方面的能力。


## 使用技術

- Hexo：靜態網站產生器，支援 Markdown 編寫文章

- hexo-theme-reimu：高自訂性主題，支援多種附加功能

- GitHub Pages：免費部署平台

- Node.js & npm：Hexo 建立與套件管理


## 部落格特色

- 支援 LaTeX 數學公式（@reimujs/hexo-renderer-markdown-it-plus）📈

- 支援 Mermaid 圖表繪製（hexo-filter-mermaid-diagrams）📊

- 支援 RSS 訂閱（hexo-generator-feed）💎

- 使用 Git 自動部署（hexo-deployer-git）📤

- 支援多語言配置（施工中）🌐

- 客製化字體與游標樣式 🖱️

- 乾淨簡約的日系動漫風格 🎆

- SEO 與 PWA 支援（可擴充）📠


## 本地啟動方式
```
npm install -g hexo-cli
git clone https://github.com/D-Sketon/reimu-template
cd reimu-template
npm install
hexo server
```
- 開啟瀏覽器，預設網址為 http://localhost:4000


## 自訂設定

Hexo 的主要設定檔案：

- _config.yml：網站基本設定，如網站名稱、描述、語言、連結等。


Reimu 主題的自訂檔案：

- _config.reimu.yml：控制主題外觀、功能、模組開啟、字體與語言設定等。


我在此部落格中已進行以下自訂：

- 更換預設字體

- 更換游標圖示

- 客製化文章頁尾與作者資訊

- 設定多欄式首頁佈局

- 隱藏部分模組（如 tag, category sidebar）



## 部署方式

我使用 GitHub Pages 進行自動部署：
```
hexo clean
hexo generate
hexo deploy
```
需先設定 _config.yml 中的 deploy 區段，例如：
```
deploy:
  type: git
  repo: https://github.com/itou_souta/itousouta15.github.io.git
  branch: gh-pages
```

## 文章分類

目前網站內容依主題分類為：

- 技術筆記：學習 C++、Python、HTML 等語言的筆記

- 資安筆記：漏洞分析、CTF、基本網路安全知識

- Side Projects：我做的小專案與網站實作紀錄

- 學習歷程：學生生活與學習相關內容



## 自我介紹

- 如果你想更認識我，可以點這裡看看我的自我介紹頁面：

[前往自我介紹](https://itousouta15.github.io/zh-TW/about/)



## 共筆邀請

我歡迎對 Hexo、寫作、資安或遊戲開發有興趣的朋友一起加入共筆：

如果你也想嘗試寫部落格或技術筆記，歡迎 PR 或聯絡我

可一起寫 CTF 解題紀錄、語言學習、技術實驗或其他有趣內容


請在 GitHub 發起 Issue 或透過 About 頁面聯絡方式與我聯繫！



## 授權條款

- 本部落格的原始碼基於 hexo-theme-reimu 主題進行修改與使用，主題遵循 MIT 授權。

- 部落格內所有文章、圖片與內容，如未特別註明，皆為原創，未經允許請勿任意轉載。


---
<a name="english"></a>

# English 🇬🇧🇺🇲

## About this Blog

This is my personal blog where I share:

⚔️ Notes on cybersecurity

💻 Programming (C++, frontend, etc.)

🏫 Student life and learning journey

👾 Side projects and hands-on experiments


This blog helps me organize knowledge and grow my skills in development and writing.

## Tech Stack

- Hexo (static site generator)

- hexo-theme-reimu (customizable theme)

- GitHub Pages (free hosting)

- Node.js & npm


## Features

LaTeX & Mermaid support 📈

RSS feed, Git deploy, PWA support 📠

Custom fonts and cursor 🌐

Clean, Japanese-style minimalist design 🎆


## Run Locally
```
npm install -g hexo-cli
git clone https://github.com/D-Sketon/reimu-template
cd reimu-template
npm install
hexo server
```
Custom Settings

Customizations include:

- Font & cursor replacement

- Multi-column layout

- Minimal sidebar elements

- Custom footer & author block


## Deployment
```
hexo clean
hexo generate
hexo deploy
```
- Deploy settings are located in _config.yml.

## Categories

Tech Notes｜Cybersecurity｜Projects｜Learning Records


## About Me

[Read my self-introduction](https://itousouta15.github.io/zh-TW/about/)

## Want to Contribute?

Feel free to join as a co-writer! Open an issue or reach out if you're into blogging, dev, or cybersecurity.

## License

Theme: MIT license.
All blog posts and images are original. Please do not repost without permission.


---

<a name="japanese"></a>

# 日本語 🇯🇵

## このブログについて

このブログは、私の学習記録・技術共有のための個人ブログです。

⚔️ セキュリティ関連のメモと感想

💻 C++やWebフロントエンドの技術記録

🏫 学生生活と学びの記録

👾 サイドプロジェクトや実験記録


知識を整理し、開発や文章力を伸ばすために活用しています。

## 使用技術

- Hexo（静的サイトジェネレーター）

- hexo-theme-reimu（カスタマイズ可能なテーマ）

- GitHub Pages（無料ホスティング）

- Node.js & npm


## 特徴

LaTeX や Mermaid の対応 📈

RSS、Gitデプロイ、多言語対応（作業中）🌐

日本風のシンプルなデザイン 🎆

フォントやカーソルのカスタム 📊


## ローカル起動
```
npm install -g hexo-cli
git clone https://github.com/D-Sketon/reimu-template
cd reimu-template
npm install
hexo server
```
## カスタマイズ内容

- フォント＆カーソル変更

- 複数カラムのトップページ

- sidebar の簡素化

- フッターと著者情報のカスタム


## デプロイ方法
```
hexo clean
hexo generate
hexo deployr
```
- _config.yml に deploy の設定が必要です。

## 記事カテゴリ

技術ノート｜セキュリティ｜プロジェクト｜学習記録


## 自己紹介

[自己紹介ページはこちら](https://itousouta15.github.io/zh-TW/about/)

## 共著者募集中

Hexo、文章、セキュリティなどに興味ある方、一緒にブログ書きませんか？
GitHub Issue または About ページから連絡してください！

## ライセンス

テーマは MIT ライセンスです。
すべての投稿・画像はオリジナルです。無断転載禁止。


---

