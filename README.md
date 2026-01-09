# yonglongsheng.

Demo 網頁：已新增 `index.html`（含完整展示用 HTML + JavaScript），並使用占位圖方便本地預覽。

快速預覽（任一方法）：

1. 使用 Python 內建的靜態伺服器（推薦）：

```bash
# 啟動伺服器並在瀏覽器開啟：
python3 -m http.server 8000
# 然後打開 http://localhost:8000/index.html
```

2. 或使用附帶的腳本（Linux / macOS）：

```bash
./start.sh
# 然後開啟 http://localhost:8000/index.html
```

說明：
- `index.html` 中目前使用外部占位圖 (`placehold.co`)，如要換成真實圖片，請將 `images/...` 的 URL 換成你的圖片路徑或上傳到 `images/` 資料夾並更新 `index.html`。
- 表單目前為前端示範（會顯示已送出提示），需要實際接收表單時可串接 Google Form 或後端 API（我可以協助設定）。

如果你要我把變更 commit 與 push 到遠端，或要我上傳真實圖片並替換預覽，告訴我下一步即可。
