# 我們如何活著｜V6 資料驅動版

## 以後新增電影，主要只動一個檔案

```text
index.html
movies-data.js   ← 主要電影資料
背景與插圖.jpg
```

### 最快方式
1. 網站點 `➕ 新增電影`
2. 填電影資料
3. 按 `下載更新後 movies-data.js`
4. 回 GitHub repository
5. 用新的 `movies-data.js` 覆蓋舊檔
6. Commit changes
7. GitHub Pages 自動更新

網站會依 `tags` 與 `philosophyQuestions` 自動建立：
- 電影森林
- 思想星圖
- 搜尋
- 多重分類
- 哲學問題連線

所以新增電影時不需要再修改 `index.html`。
