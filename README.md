# React Frontend (Vite + TypeScript)

このプロジェクトは [Vite](https://vitejs.dev/) を利用した React + TypeScript のフロントエンドアプリケーションです。  
開発環境は [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers) を用いて構築されています。

---

## 🚀 開発環境の起動方法

### 1. Dev Container を起動
VSCode を利用してリポジトリを開き、左下の緑のアイコンから **「Reopen in Container」** を選択してください。  
`.devcontainer/devcontainer.json` に基づいて Node.js 環境が立ち上がります。

### 2. 依存パッケージのインストール
```bash
cd frontend
npm install
```
### 3. 開発サーバーの起動
```bash
npm run dev
```
起動後、ブラウザで以下にアクセスしてください：
```arduino
http://localhost:5173
```
---
## 📂 ディレクトリ構成
```
.
├── .devcontainer/        # Dev Container 設定
├── frontend/             # フロントエンドアプリ
│   ├── public/           # 静的ファイル
│   ├── src/              # ソースコード
│   │   ├── App.tsx       # メインコンポーネント
│   │   ├── main.tsx      # エントリーポイント
│   │   └── assets/       # 画像やアイコン
│   ├── package.json      # npm スクリプト / 依存管理
│   ├── vite.config.ts    # Vite 設定
│   └── tsconfig.json     # TypeScript 設定
└── .github/              # GitHub 設定
```
## 🛠️ 使用技術
- React
- TypeScript
- Vite
- ESLint