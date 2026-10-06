# 忠鍵教學網（正式版 v2.1）

公司內部教學平台前端頁面，純靜態單頁 HTML，無需任何建置步驟。

## 檔案

- `index.html` — 唯一頁面（含模擬登入畫面、Google Drive 影片入口、資料夾結構說明）

## 本地預覽

直接用瀏覽器開啟 `index.html` 即可。

## 部署

### Vercel（建議）
1. 到 vercel.com → Add New → Project → Import 這個 GitHub 倉庫
2. Framework Preset 選 **Other** 或留空，Build Command 與 Output Directory 都留空
3. 不需要任何環境變數，直接 Deploy

### GitHub Pages
1. 倉庫 → Settings → Pages
2. Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/ (root)`
3. 儲存後會取得 `https://chyu3600.github.io/zhongjian-teaching/`

## 注意

- 影片目前指向 Google Drive 單一檔案 ID `11u0gjebAxf0SZcKHlAtitXSvFN1FTdBm`，
  共用設定為「受限制」，因此必須用 Drive 原生播放器開啟，內嵌播放會被擋。
- 登入畫面為模擬版（帳號密碼任意值都可進入），真正的存取控管由 Google Drive 權限負責。
