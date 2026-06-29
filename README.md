# HomeManager 官方網站（HomeManager_Home）

親子積分王 HomeManager 的官方形象網站與隱私政策頁，部署於 GitHub Pages。

- **GitHub Repo**：https://github.com/memlin00001/HomeManager_Home.git
- **本機目錄**：`D:\Repos\HomeManager\HomeKidsAssist\MobileApp\04_官方網站`
- **建立日期**：2026-06-29（由 landing_page.html / privacy_policy.html 自 `AppSource/www/` 移轉而來）

---

## 檔案結構

| 檔案 | 用途 | 備註 |
|------|------|------|
| `index.html` | 官方形象首頁（原 `landing_page.html`，已改名） | RWD + 深色模式，內含 Hero/痛點/功能/隱私/見證/CTA |
| `privacy_policy.html` | 隱私權政策頁 | 由首頁底部「隱私權政策」連結（相對連結 `privacy_policy.html`） |

兩檔皆為**單檔自帶內聯 CSS**，無外部相依資產，可直接部署。

---

## 部署到 GitHub Pages（首次）

```bash
cd D:\Repos\HomeManager\HomeKidsAssist\MobileApp\04_官方網站
git init
git add .
git commit -m "init: HomeManager official site (index + privacy_policy)"
git branch -M main
git remote add origin https://github.com/memlin00001/HomeManager_Home.git
git push -u origin main
```

接著在 GitHub repo → **Settings → Pages → Source 選 `main` / `(root)`** → 儲存。

**公開網址（部署後）**：

- 首頁：`https://memlin00001.github.io/HomeManager_Home/`
- 隱私政策：`https://memlin00001.github.io/HomeManager_Home/privacy_policy.html`

> 隱私政策公開 URL 是 Google Play / App Store 上架的硬門檻，部署後即可填入商店後台。

## 日後更新

```bash
cd D:\Repos\HomeManager\HomeKidsAssist\MobileApp\04_官方網站
git add .
git commit -m "update: <說明>"
git push origin main
```

---

## 維護

每輪排程（06:00 / 07:00 / 08:00）行銷線會檢查本網站，待辦與更新項目記錄於同目錄
[`網站維護檢查清單.md`](網站維護檢查清單.md)。
