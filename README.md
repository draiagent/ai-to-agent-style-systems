# AS｜Agent Style Systems

**讓Agent依據可追溯規格延續品牌風格。** 從AS Collection 01九套設計系統開始，持續收錄新批次。

![版本](https://img.shields.io/badge/version-0.1.0-blue)

![AS Collection 01封面](collections/01/cards/01.png)

[風格展示頁](index.html) · [快速開始](docs/QUICKSTART.md) · [批次規則](docs/COLLECTION-POLICY.md) · [驗證紀錄](docs/VALIDATION.md)

## 為什麼建立AS

讓「高級、科技、親切」這類感受轉成色彩、字體、構圖、元件與限制，減少系列作品風格漂移。這是規格知識庫與提示詞工具包，不是已驗證所有平台的自動生成程式。

## Collection入口

| 系列 | 風格編號 | 狀態 |
|---|---|---|
| [AS Collection 01](collections/01/README.md) | AS-001～AS-009 | 來源規格v0.1；含OPEN問題 |
| AS Collection 02 | AS-010起接續 | 未建立，待實際素材 |

所有批次都在本Repo；修訂保留原編號，規則詳見[Collection政策](docs/COLLECTION-POLICY.md)。

## 九套風格總覽

| 風格 | 預覽 | 規格與指令 |
|---|---|---|
| **AS-001 朱漆直書**<br>Vermilion Script | <img src="collections/01/cards/02.png" width="180" alt="朱漆直書"> | [規格](collections/01/styles/AS-001/SPEC.md) · [指令](collections/01/styles/AS-001/PROMPT.md) |
| **AS-002 青金絲緞**<br>Satin Teal & Gold | <img src="collections/01/cards/03.png" width="180" alt="青金絲緞"> | [規格](collections/01/styles/AS-002/SPEC.md) · [指令](collections/01/styles/AS-002/PROMPT.md) |
| **AS-003 深海時刻**<br>Abyss Hour | <img src="collections/01/cards/04.png" width="180" alt="深海時刻"> | [規格](collections/01/styles/AS-003/SPEC.md) · [指令](collections/01/styles/AS-003/PROMPT.md) |
| **AS-004 益生寵愛・莓果貼紙**<br>Berry Sticker | <img src="collections/01/cards/05.png" width="180" alt="益生寵愛・莓果貼紙"> | [規格](collections/01/styles/AS-004/SPEC.md) · [指令](collections/01/styles/AS-004/PROMPT.md) |
| **AS-005 EASY CURE・黃綠雙環**<br>Twin Ring System | <img src="collections/01/cards/06.png" width="180" alt="EASY CURE・黃綠雙環"> | [規格](collections/01/styles/AS-005/SPEC.md) · [指令](collections/01/styles/AS-005/PROMPT.md) |
| **AS-006 翡翠禮匣**<br>Emerald Coffret | <img src="collections/01/cards/07.png" width="180" alt="翡翠禮匣"> | [規格](collections/01/styles/AS-006/SPEC.md) · [指令](collections/01/styles/AS-006/PROMPT.md) |
| **AS-007 墨白桐花**<br>Ink & Blossom | <img src="collections/01/cards/08.png" width="180" alt="墨白桐花"> | [規格](collections/01/styles/AS-007/SPEC.md) · [指令](collections/01/styles/AS-007/PROMPT.md) |
| **AS-008 潮汐實證**<br>Tidal Proof | <img src="collections/01/cards/09.png" width="180" alt="潮汐實證"> | [規格](collections/01/styles/AS-008/SPEC.md) · [指令](collections/01/styles/AS-008/PROMPT.md) |
| **AS-009 橙鞍工坊**<br>Orange Atelier | <img src="collections/01/cards/10.png" width="180" alt="橙鞍工坊"> | [規格](collections/01/styles/AS-009/SPEC.md) · [指令](collections/01/styles/AS-009/PROMPT.md) |

## 怎麼用

看風格 → 選一套 → 複製[共用指令](prompts/agent-task.txt)與該套附加指令 → 提供內容及素材 → 先做樣張 → 核對後展開系列。

**輸入：**內容重點、受眾、媒介尺寸、Logo與圖片、參考風格、署名、可編輯需求。
**輸出：**指定成品、採用規則、適配說明、未決事項與驗收紀錄。

閱讀無需安裝；生成時由使用者提供相應Agent與工具。完整填寫例見[AS-002課程圖卡](examples/as-002-course-card.md)。

## 規格與驗證邊界

E為原圖明訂，O為視覺觀察，P為適配提案，Q為未決問題。88條規則與63張來源PNG可互相追溯；13項未決問題保留OPEN。介紹圖卡是生成示例，不作精確字型或色彩面積的驗證憑據。
圖片、簡報、文件／文字、互動網頁、動畫、影片共六媒介已有[適配提案](docs/MEDIA-ADAPTATION.md)，尚未全面生成實測。適合設計溝通、教材及Agent任務；不適用直接宣稱正式品牌授權、精確工程Token或醫療成果。

## 檔案入口

- [完整文字規格](collections/01/SPECIFICATION.md)、[未決登錄](collections/01/OPEN-QUESTIONS.md)
- [10張圖卡](collections/01/cards/README.md)、[來源PNG雜湊清單](collections/01/sources/manifest.json)
- [社群文章](docs/SOCIAL-POST.md)、[驗收母版](docs/VALIDATION-TEMPLATE.md)
- [來源與權利聲明](docs/ATTRIBUTION.md)、[貢獻方式](CONTRIBUTING.md)
- [版本紀錄](CHANGELOG.md)、[發布準備](docs/PUBLISHING.md)

## 版本與後續

Repo版本 **0.1.0**，日期 **2026-10-09**；來源規格版本 **v0.1**。已建立公開 repo 與 tag v0.1.0；尚未建立 GitHub Release，未啟用 GitHub Pages。
後續依實際需求解決OPEN問題、補齊字型與元件資產、逐項驗證媒介，再新增Collection 02。這些不列為已完成功能。

## 授權與致謝

**本 repo 採保留所有權利（All rights reserved），見[LICENSE](LICENSE)，不是開源授權；法律權利人為 AI Coach 益力康陳董。** Logo、人物、商標與第三方字型另行處理。
展示組織方式參考[Vincentwei1021/mg-styles-15](https://github.com/Vincentwei1021/mg-styles-15)，未複製其程式與媒體素材。

AI Coach 益力康陳董 x CGM Coach 血糖教練 | 2026 AI to Agent | 2027 AI to AGI Agent
