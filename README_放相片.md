# 基慈小學 · 創科成就展網站 — 放相片指引

## 📁 圖片資料夾

```
keitsz_stem_showcase/
├── index.html
└── images/
    ├── highlights/     ← 12 張「亮點成就」卡的相片
    └── timeline/       ← 37 個「時間軸」活動的相片
```

## 🖼️ 放相片做法

**只需將相片 JPG 放到對應資料夾，並用正確檔名即可，網頁會自動顯示。**
如果暫時未有相片，該位會顯示漂亮的漸變色 + emoji 圖示佔位。

### 建議規格
- 格式：`.jpg`（也支援 `.png`，但要相應修改 `index.html`）
- 比例：**16:9（橫向）** 最靚，例如 1280×720 或 1920×1080
- 容量：每張建議 < 300KB（可用 [tinypng.com](https://tinypng.com) 壓縮）

---

## ✨ 亮點成就（12 張） · images/highlights/

| 檔名 | 對應活動 |
|---|---|
| `01-coding-galaxy.jpg` | Coding Galaxy 編程電競校際邀請賽（冠軍） |
| `02-mecha-league.jpg` | 機甲聯盟挑戰賽（黃大仙區冠軍） |
| `03-r4m-taiwan.jpg` | 香港 R4M / 機關王世界賽（晉級台灣） |
| `04-mit-node.jpg` | CoolThink@JC · MIT Node 專訪 |
| `05-wenchang.jpg` | 海南島文昌航天科普基地培訓班 |
| `06-ai-mainland.jpg` | 新時代築夢 AI 主題交流團 |
| `07-sensetime.jpg` | 商湯科技 SenseTime 參訪 |
| `08-hkfyg-ai.jpg` | 青協 AI 智能團 |
| `09-eduhk-vr.jpg` | 教大 VR 課程共同開發 |
| `10-lt-expo.jpg` | 學與教博覽 (L&T Expo) |
| `11-eduhk-codingfair.jpg` | 教大 Coding Fair |
| `12-astronaut.jpg` | 國慶 75 周年 · 航天員進校園 |

---

## 📅 時間軸（37 項） · images/timeline/

時間軸的相片檔名格式為：`編號-活動名稱.jpg`。
最簡單的做法：
1. 打開 `index.html`，在瀏覽器中檢視時間軸
2. 右鍵點擊任何一個相片位 → 「檢查」/「Inspect」
3. 複製 `<img src="images/timeline/XX-xxxxx.jpg">` 中的檔名
4. 將相應相片以該檔名放入 `images/timeline/` 資料夾

或者直接在 `index.html` 搜尋活動標題，就能找到對應的 `src="..."` 檔名。

### 懶人做法：批次命名建議
- 用 Finder 將相片排列好 → 一齊重新命名為 `01.jpg, 02.jpg, ...`
- 再打開 `index.html`，用「取代全部」將 `XX-xxxxx.jpg` 改成 `XX.jpg` 即可

---

## 🌐 上載到學校網站

1. 將整個 `keitsz_stem_showcase` 資料夾壓縮成 zip
2. 上載到學校 web server（FTP / cPanel）或
3. 直接打開 `index.html` 用瀏覽器預覽

### 推薦免費公開平台
- **GitHub Pages**：將資料夾 push 到 repo，`Settings → Pages` 一鍵發佈（免費、有 HTTPS）
- **Netlify**：把資料夾直接拖到 app.netlify.com（5 秒完成）
- **Cloudflare Pages**：同上，免費 + CDN

---

## 🎨 自訂建議
- 換校徽：在 hero 部份加 `<img src="images/logo.png">`
- 換主題色：修改 `:root` 內的 `--accent`, `--accent2`, `--accent3`
- 加影片：在卡片內改 `<video src="..." autoplay muted loop></video>`

如需進一步協助，聯絡 IT 組。
