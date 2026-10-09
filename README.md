# 麥當勞公會 mcdonalds-guild

楓之谷經典版「麥當勞」公會專屬網頁：公會簡介、成員介紹與招募宣傳。

網址（開啟 GitHub Pages 後）：https://huia7421-droid.github.io/mcdonalds-guild/

## 檔案
- `index.html`：整個網頁（純 HTML/CSS/JS，不需要伺服器，直接用瀏覽器開啟即可）
- `images/`：成員角色圖

## 新增成員
1. 把角色圖放進 `images/`
2. 打開 `index.html`，找到 `const members = [...]`，照格式多加一筆：
   ```js
   { name: "角色名", img: "images/檔名.png", ribbon: "右上角標籤",
     tags: ["職業", "其他標籤"], intro: "簡介", combo: "🍟 招牌：XXX" }
   ```

## 上線（GitHub Pages）
Repo 的 Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main`、資料夾選 `/ (root)`，按 Save，幾分鐘後網址就會生效。
