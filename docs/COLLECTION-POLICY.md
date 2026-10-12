# Collection 與版本管理規則

確認日期：2026-10-08；寫入日期：2026-10-09。

## 固定規則

1. Repo 名稱固定為 `ai-to-agent-style-systems`。
2. 第一批為 **AS Collection 01**，存放於 `collections/01/`，風格編號 **AS-001～AS-009**。
3. 第二批為 **AS Collection 02**，存放於 `collections/02/`，從 **AS-010** 接續；另有獨立發布的 [ai-to-agent-style-systems-02](https://github.com/draiagent/ai-to-agent-style-systems-02)，見下方「獨立 Repo」。
4. 後續批次同樣在此 Repo 擴充；每批收錄數量依實際內容決定，不預設都是九套。
5. AS 編號全域唯一且永久保留。更名、修訂或停用不重編、不回收；新風格使用下一個未分配編號。
6. 新增批次與修訂版本分開管理。修正第一批色碼、文案或提示詞，更新其版本、規格與 CHANGELOG，保留 Collection 與風格編號。
7. README 提供各批次入口和全風格總覽；同步更新 `catalog.json` 與 `index.html`。
8. 不先建立空的第二批資料夾。取得實際素材後，才新增規格、來源、提示詞及介紹圖卡。

## 獨立 Repo

- [ai-to-agent-style-systems-02](https://github.com/draiagent/ai-to-agent-style-systems-02)（v0.1.0，2026-10-12）只收錄 Collection 02（AS-010～AS-018）；規格、來源圖、規則與未決問題 ID 及數值與本 Repo 的 `collections/02` 相同。
- 該 Repo 的文件章節為本 Repo 0.2.1 統一前的結構；本 Repo 仍收錄各批次，並作為系列入口（獨立 Repo 的 README 連回本 Repo）。
- 兩處內容各自維護，修訂需分別更新並在各自 CHANGELOG 說明。兩邊標示的下一個編號皆為 AS-019。

## 版本

Repo 初版為0.1.0；來源規格仍為v0.1，兩者層級不同。修訂需在 CHANGELOG 說明受影響的Collection與AS編號。
PATCH用於相容修正；MINOR用於新增批次或向後相容功能；破壞既有輸入、規則含義或目錄介面時，先說明遷移方式再決定版本。
不得移動已發布tag，或以新版覆蓋原始來源圖。

## 第二批操作紀錄

2026-10-12：新增 collections/02/，收錄 AS-010～AS-018，Repo 升為 0.2.0。第一批內容原樣保留；下一個可分配編號為 AS-019。

2026-10-12：發布獨立 Repo ai-to-agent-style-systems-02（v0.1.0），收錄同一批 AS-010～AS-018；本 Repo 升為 0.2.2，補上說明，不修改任何規格或來源圖。

AI Coach 益力康陳董 x CGM Coach 血糖教練 | 2026 AI to Agent | 2027 AI to AGI Agent
