# For HAMI 115

給高雄醫學大學醫務管理暨醫療資訊學系學生的 AI 與雲端入門素材。

本 repo 將兩個可獨立使用的 sample 放在一起：

```text
For HAMI 115/
├── student-agent-kit/     AI 學習工作台與課業模板
└── cloud-card-template/   Cloudflare Pages 靜態網站實作
```

## 內容

### `student-agent-kit/`

給大一新生使用的 AI 學習夥伴模板，涵蓋：

- 課程與筆記
- 作業拆解
- 分組專題與會議紀錄
- 校園活動
- 醫務管理／醫療資訊生涯探索
- 學習記憶與踩坑紀錄

入口：[student-agent-kit/README.md](student-agent-kit/README.md)

## 如何安裝學生版 Pro-Kit

`student-agent-kit` 是一個資料夾模板，不需要安裝套件；下載後複製成自己的學習工作台即可。

### 方法一：下載 ZIP

1. 開啟本 repo 的 GitHub 頁面，點選 **Code → Download ZIP**。
2. 解壓縮後，將 `student-agent-kit` 複製到自己的文件資料夾。
3. 將複製出來的資料夾改名，例如 `KMU-AI-Workspace`。
4. 之後都從 `KMU-AI-Workspace` 開啟 AI 工具，不要直接從 `For HAMI 115` 根目錄開始。

### 方法二：使用 Git

```bash
git clone https://github.com/lien6108/for-hami-115.git
cd for-hami-115
```

接著將 `student-agent-kit` 複製成自己的資料夾，例如 `KMU-AI-Workspace`，再從該資料夾開啟 Claude Code 或 Codex。

完整步驟與啟動提示詞請看：[student-agent-kit/README.md](student-agent-kit/README.md)。

### `cloud-card-template/`

演講現場使用的第一個 Cloudflare Pages 靜態網站。學生可以修改自己的卡片內容，再部署到 `pages.dev`。

入口：[cloud-card-template/README.md](cloud-card-template/README.md)

## 使用原則

- 這些素材是學習與實作起點，不是作業代寫工具。
- 不要放入病患可識別資料、實習機構機密、API 金鑰或密碼。
- 醫療資訊、引用與統計數字都要回到可靠來源查證。
- 依授課老師規定揭露 AI 使用方式。
