# 快速開始

這是規格與提示詞資料庫，閱讀不需要安裝軟體。需生成圖片、簡報等成果時，自備具相應能力的Agent與工具；不假定任何模型一定支援所有媒介。

1. 在[Collection 01](../collections/01/README.md)選一套風格。
2. 打開該套SPEC.md、PROMPT.md，再讀[未決事項](../collections/01/OPEN-QUESTIONS.md)及[證據標記](../collections/01/SPECIFICATION.md)。
3. 複製[共用任務指令](../prompts/agent-task.txt)，填入內容重點、尺寸、Logo、參考風格、圖片素材、署名、可編輯需求。
4. 將共用指令、該套規格與附加指令交給Agent；有來源圖片時一併提供。
5. 先產生一張樣張，檢查文字、版面、資產與未決項，再生成系列。
6. 依[驗收母版](VALIDATION-TEMPLATE.md)記錄通過、失敗、待確認與未驗證，不把靜態圖視為跨媒介全面通過。

完整範例見[AS-002課程圖卡](../examples/as-002-course-card.md)。

## 本地預覽展示頁

在Repo根目錄執行 `python3 -m http.server 8000`，瀏覽 `http://localhost:8000`。不需npm或API金鑰。也可直接開啟index.html；複製按鈕受瀏覽器權限影響時可手動選取提示詞。

## 檢查Repo

執行 `python3 scripts/validate.py`。檢查檔案、索引、來源雜湊、PNG結構與本地連結；不驗證圖片文字正確率、字型授權、模型生成成功率或六媒介功能。

AI Coach 益力康陳董 x CGM Coach 血糖教練 | 2026 AI to Agent | 2027 AI to AGI Agent
