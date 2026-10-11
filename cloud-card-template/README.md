# 我的第一個雲端網站

高醫醫管資系演講「什麼是地端與雲端」現場實作用的模板。

這個資料夾可以獨立複製成自己的網站專案，也可以直接從本 repo 下載後使用。

## 三步驟

1. 將 `cloud-card-template` 複製到自己的 GitHub repo，名字取英文（例如 `my-card`）
2. 打開 `public/index.html` → 修改名字、年級、想成為的人 → **Commit changes**
3. 到 Cloudflare：**Workers & Pages → Create application → Pages → Import an existing Git repository**
   - 選這個 repo → **Begin setup**
   - Framework preset：`None`
   - Build command：`exit 0`
   - Build output directory：`public`
   - **Save and Deploy**

完成後會拿到 `https://你的專案名.pages.dev`。之後在 GitHub 改檔案、Commit，網站約一分鐘內會自動更新。
