# 我們如何活著｜電影 × 人生地圖

這是 **GitHub Pages 簡易上傳版**。

這一版刻意把：
- CSS
- JavaScript
- 電影資料

全部直接包進 `index.html`。

所以 GitHub Repository 根目錄只需要 5 個網站檔案：

```text
index.html
cinema-atmosphere-bg.jpg
hero-cinema-illustration.jpg
moon-filmstrip-accent.jpg
filmstrip-accent.jpg
```

另外可保留 `README.md`。

## GitHub Pages 上傳方式

1. 新建一個 GitHub Repository，例如：
   `how-we-live`

2. 進 Repository 首頁，選：
   `Add file` → `Upload files`

3. 將本資料夾中的檔案全部拖進去。

4. 按：
   `Commit changes`

5. 到：
   `Settings` → `Pages`

6. Build and deployment 設定：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/(root)`

7. 按 Save。

完成後網址通常是：

```text
https://你的GitHub帳號.github.io/how-we-live/
```

## 為什麼這版比較不容易壞？

舊版需要：

```text
css/style.css
js/app.js
data/movies.json
assets/圖片
```

如果 GitHub 上傳時把資料夾攤平，網站就會找不到檔案。

這一版除了 4 張圖片之外，其他東西都集中在 `index.html`，
因此不會再發生 CSS / JS / JSON 路徑錯誤。

## 如果 GitHub Pages 更新後看起來還是舊版

瀏覽器可按：

- Windows：`Ctrl + F5`
- Mac：`Cmd + Shift + R`

進行強制重新整理。


## 電影森林插圖版

八大人生區域新增 8 張章節插圖，請與 `index.html` 一起放在 GitHub Repository 根目錄：

```text
zone-world.jpg
zone-culture.jpg
zone-people.jpg
zone-love.jpg
zone-self.jpg
zone-memory.jpg
zone-existence.jpg
zone-art.jpg
```


## 5.0 新增：思想星圖與我的電影筆記

- 🌲 電影森林：從人生面向找電影
- 🌌 思想星圖：從哲學問題找電影
- ✍️ 我的電影筆記：記錄「我的觀看」、問題、思想座標與完整感想

筆記使用瀏覽器 localStorage 儲存，不會自動同步到其他裝置；網站內可匯出／匯入 JSON 備份。
