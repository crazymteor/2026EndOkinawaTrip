# 2026 年末沖繩行程

用 Cloudflare Workers（靜態資源）部署，設定在 `wrangler.jsonc`，網站內容放在 `public/`。

| 網址 | 檔案 | 用途 |
|---|---|---|
| `/` | `public/index.html` | 給團員看的分享網頁（從編輯器「匯出分享網頁」後改名覆蓋） |
| `/edit/` | `public/edit/index.html` | 行程編輯器（自己用） |

- 推送到 main 後 Cloudflare 會自動重新部署。
- 不要把 Google Maps API 金鑰或匯出的行程檔（.json）放進 repo。
