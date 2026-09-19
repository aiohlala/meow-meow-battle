# 🐱 喵喵大戰：罐罐保衛戰 - 公開入口網 (Meow Meow Battle Portal)

本專案為《喵喵大戰：罐罐保衛戰》的官方公開入口網站與 GitHub Pages 線上遊戲託管站。

---

## 🌐 線上遊玩網址

👉 **GitHub Pages 入口網**：[https://aiohlala.github.io/meow-meow-battle/](https://aiohlala.github.io/meow-meow-battle/)  
👉 **全螢幕直連遊戲**：[https://aiohlala.github.io/meow-meow-battle/game.html](https://aiohlala.github.io/meow-meow-battle/game.html)

---

## 🚀 專案技術架構

- **靜態入口網頁** (`index.html`)：包含遊戲介紹、特色亮點、角色與武器指南，以及即時試玩內嵌視窗。
- **純前端遊戲本體** (`game.html`)：單檔案 HTML5 Canvas 2D 遊戲，整合 Firebase Firestore 多人同步與 Gemini API。
- **GitHub Actions 自動部署** (`.github/workflows/deploy.yml`)：每次推送至 `main` 分支自動構建發布至 GitHub Pages。
