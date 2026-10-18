# K-POP Idol Game 劇本工坊

依成員設計檔的口吻與「日常層規格」,用 Gemini 大量生產日常片段(長對話、撞見、練習中、訊息、成員之間、你不在場時等),審稿、試玩後收進內容庫,並以熱度圖追蹤覆蓋率。之後會整合進遊戲。

- 網頁版:推送到 main 後,由 GitHub Actions 發布到 GitHub Pages
- 安裝版:同一次流程打包 APK(KPOP-Scripts.apk)
- 簽章使用 KEYSTORE_B64 Secret(沿用歌曲企劃室那段金鑰文字)
- 雲端同步沿用同一個 Firebase 專案與帳號,資料存在 users/{uid}/scripts
