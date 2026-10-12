# Feature communication and delivery checks

The owner checks every customer feature plan, issue, demo and acceptance record. The English-site revamp scope stays unchanged by bilingual documentation.

## Language layout

Show the complete English explanation first. Put the complete Chinese explanation in a separate expandable section below, using details/summary. Each language has its own lists, tables, captions and open decisions. Do not join translated sentences or bilingual table cells. Preserve English button names in Chinese explanations where needed to match the screen.

## Requirements and customer decisions

For a clear, feasible customer requirement, state what the system will provide, what materials are needed and how acceptance is checked. Routine layout or implementation choices belong to the project owner. Ask the customer only when an ambiguity changes behavior or scope. State the unclear point and why the answer matters; keep the already clear functions as commitments.

Apply `請客戶確認` only to feature issues with an unanswered customer decision. Give each question an identifier, state single or multiple choice, and provide unchecked options with a recommended option where appropriate. Use free text only for information that cannot be expressed as a choice. Customers copy the options into a comment and check them, or reply with the option identifiers; editing the issue body is not required. Materials requests and implementation acceptance checklists are separate from customer decision options.

After recording a customer's answer and updating the behavior and acceptance criteria, remove `請客戶確認`. Keep the feature open for implementation and acceptance. Do not label all unfinished or material-dependent features as needing customer decisions.

## Required screen evidence

Every feature needs at least one project-specific screenshot beside its explanation, with the entry/action identified. Design screenshots must match the original website’s design and be marked as mockups. If this cannot be achieved, attach no arbitrary image; record the missing evidence and leave the delivery check incomplete. Reference sites supplement direction and cannot replace project screens.

Interactive features require before/after or key states. Applicable features require desktop and mobile views. At demo and acceptance, motion, carousels and video require a recording or interactive demo in addition to screenshots. Use actual screenshots from the demonstrated version for demo and acceptance.

Captions record feature number, state and design or demonstrated version/date. Provide captions within each language section. Update images and both explanations together when screens change. Check public assets for private information.

## Delivery checklist

- [ ] Complete English and expandable Chinese sections have matching scope and status.
- [ ] Purpose, entry, action, result, materials and open decisions are stated in both sections.
- [ ] Clear requirements use delivery commitments and testable acceptance criteria; only consequential ambiguities ask for a customer decision.
- [ ] Every unanswered customer decision has `請客戶確認` and a numbered choice block; materials and acceptance checks are separate.
- [ ] Each feature has readable screenshots grounded in the original website design, identified areas and captions.
- [ ] Mockups, references and implemented screens are distinguished.
- [ ] Applicable interaction states and desktop/mobile views are supplied.
- [ ] Motion recordings or interactive demos are supplied for demo and acceptance.
- [ ] Images and explanations match the submitted version.
- [ ] Public assets contain no private information.
- [ ] The owner records results, evidence gaps and reasons for non-applicable checks.

Missing evidence blocks a ready-for-delivery or completion claim; an issue may still be published as awaiting evidence. Planning completeness does not mean implementation acceptance. Customer silence is not approval.

## Permanent source and change records

Assign a stable request feedback record number to each independent customer submission. Preserve the original file and assign document v1 if none is supplied. A revision to the same submission gets v2 under the same record; a separate submission gets a new record. Record registration date separately from any verified customer submission date.

Store all received originals under `docs/customer-feedback/<record>/v<revision>/<original filename>`. Preserve the received format, filename and file bytes, including its extension. Never convert, edit or overwrite an archived original. Save summaries, translations and previews as separate files linked to the original. A repeated filename in a later revision belongs in a new revision folder. The register identifies the source file, revision and related issues.

Each record maps document items to issues. Each issue names the source record, revision and affected item. Preserve source labels, dated batch labels and batch overviews permanently. Later batches get new records rather than rewriting earlier batch descriptions. Remove only temporary review-status labels after the corresponding reply is recorded.

`updated-review` means changed content awaits reading, not necessarily a decision. `請客戶確認` identifies an actual unanswered customer choice. `bilingual` means both language sections exist. `scope-change` identifies scope added to the original baseline; any remaining decisions are stated separately. Date-specific batch labels track all edited issues, while source labels track only issues related to the customer document. See [the source register](customer-feedback/README.md).

<details>
<summary>中文說明（點此展開）</summary>

# 功能溝通與交付檢核

負責人檢查每份客戶功能規劃、議題、demo 及驗收紀錄。雙語文件不改變英文版改版範圍。

## 語言排版

預設顯示完整英文，完整中文放在下方獨立可展開區塊，使用 details/summary。兩語各自有列表、表格、圖說及待確認事項，不將翻譯句子直接接在一起，也不混排在同一表格欄位。中文說明可保留必要的英文按鈕原名，以便核對畫面。

## 需求與客戶決定

客戶需求明確且可配合實作時，直接寫系統提供的功能、所需素材及可核對的驗收條件。一般版面及實作選擇由負責人處理。只有會影響行為或範圍的歧義才請客戶決定，寫明不清楚的地方及答案影響，已明確的功能仍列為交付內容。

只有存在未回答客戶決定的功能議題才加 `請客戶確認`。每題有固定編號，註明單選或複選，提供未勾選選項並在適用時標示建議選項。無法用選項表達的資料才請客戶填寫。客戶可複製選項到留言勾選，或直接回覆選項編號，不必編輯議題內文。素材要求、客戶選項及實作驗收檢核分開呈現。

記錄客戶答案並更新行為及驗收條件後，移除 `請客戶確認`，功能仍維持開放待實作及驗收。未完成或待素材不代表需要客戶決定。

## 必要畫面證據

每項功能說明旁至少附一張本專案截圖，標出入口或操作位置。設計截圖須符合原網站設計並標為示意。無法做到時不附任意圖片，記錄缺件並保留未通過檢核。參考網站只補充方向，不取代本專案畫面。

互動功能附操作前後或關鍵狀態，適用功能附桌機及手機畫面。動畫、輪播及影片在 demo 與驗收時另附錄影或可操作展示，並保留截圖。Demo 及驗收使用展示版本實際截圖。

圖說記錄功能編號、狀態、設計稿或展示版本／日期，分別放在各語言區塊。畫面變更時同步更新圖片及兩語說明，公開前檢查敏感資料。

## 交付檢核

- [ ] 完整英文及可展開中文的範圍與狀態一致。
- [ ] 兩語均說明用途、入口、操作、結果、素材及待確認事項。
- [ ] 明確需求列為交付承諾及可核對驗收，只有影響行為或範圍的歧義才請客戶決定。
- [ ] 未回答的客戶決定有 `請客戶確認` 及編號選項，素材與驗收檢核另列。
- [ ] 每項功能有符合原網站設計的清楚截圖、位置標示及圖說。
- [ ] 示意、參考畫面及實作畫面清楚區分。
- [ ] 適用的互動狀態及桌機／手機畫面完整。
- [ ] Demo 及驗收的動態錄影或可操作展示完整。
- [ ] 圖片與說明對應提交版本。
- [ ] 公開素材不含敏感資訊。
- [ ] 負責人記錄結果、缺件及不適用項目的原因。

缺少證據不得宣告可交付或完成，議題仍可標記待補證據後發布。規劃完整不等於實作驗收，客戶未回覆不等於同意。

## 永久來源及變更紀錄

每次獨立客戶回饋編固定需求回饋單號，保存原檔。客戶未提供版本時，由專案編文件 v1。同一份回饋修訂另存 v2，獨立新回饋另編單號。登錄日期與已確認的客戶提交日期分開記錄。

所有收到的原件集中在 `docs/customer-feedback/<單號>/v<版本>/<原檔名>`，依單號及版本分類。保留收到的格式、檔名、副檔名及檔案內容，不轉檔、不修改、不覆寫原件。摘要、翻譯及預覽另存檔案並連回原件，後續修訂的同名檔放在新版本資料夾。登錄表記錄原檔位置、版本及相關議題。

每張單建立文件項目與議題對照，議題記錄來源單號、文件版本及項目。來源標籤、日期批次標籤及批次總覽永久保留。後續批次另開紀錄，不覆寫原批次說明；記錄對應回覆後只移除暫時待閱讀標籤。

`updated-review` 為內容變更待閱讀，不代表一定要決定。`請客戶確認` 表示有未回答的客戶選項，`bilingual` 表示兩語區塊完整，`scope-change` 表示相對原基準新增的範圍，尚需決定的事項另列。日期批次標籤追蹤所有修改議題，來源標籤只標示與客戶文件相關的議題。見[來源登錄表](customer-feedback/README.md)。

</details>
