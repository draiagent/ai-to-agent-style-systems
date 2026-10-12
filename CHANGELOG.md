# Changelog

## 0.2.0 — 2026-10-12

### Added
- Collection 02：AS-010～AS-018，63 張原圖、63 個逐頁規則群與 25 項 OPEN。
- 九套專用 Agent 指令、共用指令、10 張介紹圖卡與社群文章。
- 原始來源及介紹圖卡 SHA-256 清單。

### Changed
- 首頁、展示頁與 catalog 更新為兩批 18 套風格，下一編號 AS-019。
- 驗證腳本擴充至兩批，保留既有 UTF-8 相容修正。

### Fixed
- 第二批第 09 張收錄最後生成修正版，排除早期版本。
- scripts/validate.py：讀取文字檔時明確指定 UTF-8，修正在 Windows（預設 cp950）直接執行會 UnicodeDecodeError 的問題；檢查項目與判定邏輯不變。

### Preserved
- collections/01/ 所有檔案逐位元保持不變；既有授權保留所有權利。
- 原始規格仍 v0.1；未決事項沒有被標成已定稿。


## 0.1.0 — 2026-10-09

### Added
- AS Collection 01：AS-001～AS-009、88條規則、來源追溯與13項OPEN問題。
- 63張原始參考PNG、10張介紹圖卡、品牌展示素材。
- 九套附加指令、共用Agent任務、六媒介適配提案、使用案例與驗收母版。
- README風格總覽、靜態展示頁與可複製提示詞。
- Collection治理：第二批沿用同一Repo，AS-010起接續。
- 社群介紹文章、來源說明、驗證腳本及發布準備文件。

### Fixed
- 第04張介紹圖卡採用五色色票修正版。
- 第06張介紹圖卡採用亮色圖形／深色文字修正版。

### Known limitations
- 授權為保留所有權利（All rights reserved），法律權利人為 AI Coach 益力康陳董；已建立公開 repo 與 tag v0.1.0，未建立 GitHub Release。
- 來源衝突仍OPEN；精確字型、色彩面積和六媒介生成尚未全面驗證。

AI Coach 益力康陳董 x CGM Coach 血糖教練 | 2026 AI to Agent | 2027 AI to AGI Agent
