# My lab evidence / 我的實作紀錄

- Group code / 組別：待本人填寫（請用組別代碼，不寫姓名或學號）
- Tool / 工具：Codex
- Route / 路線：待本人確認（個人／雙人）
- Tasks completed / 完成題目：A、B、D
- Material / 素材：NDHU classroom tasks 東華課堂版
- For original-pack work: task number, author/source link and version / 原版實作：不適用
- My role and what I checked / 我的角色與實際檢查：我請 Codex 協助完成 A、B、D；我回報 A 的檢查項目通過、B 的六項測試通過，並實際確認 B 的窄螢幕按鈕排版通過。D 的退回文件由 Codex 撰寫；請本人閱讀確認內容。

## Scope and plan / 範圍與計畫

Allowed input and output folders / 可讀取與輸出的資料夾：

- A：`practice/01-club-files/input/` → `practice/01-club-files/output/`
- B：`practice/02-campus-picker/activities.json`、`practice/02-campus-picker/output/index.html`
- D：只讀 `practice/04-review/bad-plan.txt`，寫入 `practice/04-review/my-rejection.md`

What I asked for / 原始需求：依課堂任務整理社團檔案、製作課間活動挑選器並修正窄螢幕排版，以及審查一份刻意寫錯的計畫。

What I checked before execution / 動手前我檢查了什麼：查看各題素材與任務要求。D 題明確標示為討論材料，只閱讀、不執行。

## Tests actually performed / 我真的做過的測試

| Test / 測試 | Expected / 預期 | Observed / 實際 | Evidence / 證據 |
|---|---|---|---|
| A：比對來源檔與分類後的副本 | 12 個來源檔都有對應副本，內容未改變 | Codex 執行 SHA-256 比對，12 個副本均與來源相符；使用者回報檢查項目通過 | `practice/01-club-files/output/manifest.json`；A 提交紀錄 |
| B：六項功能測試 | 按課堂規格操作，六項情境結果正確 | 使用者回報六項均通過；各情境的逐項觀察沒有另外保存 | `practice/02-campus-picker/output/index.html`；使用者回報 |

## One revision / 一次修改

Before / 原來的情況：窄螢幕下按鈕排版尚未達到使用者希望的樣子；原始畫面沒有另外保存。

Request / 我提出的修改：使用者要求窄螢幕按鈕改為滿版寬度。

After and retest / 修改後與重測結果：已調整窄螢幕按鈕為滿版寬度；使用者實際查看後回報排版通過。

New requirement or defect? / 新需求還是原規格未做到？使用者提出的排版修正；目前紀錄不足以判斷屬於新需求或原規格缺漏。

## One rejection / 一次退回

Which action I reject and why / 退回哪個動作、為什麼：退回整個 Downloads 資料夾都整理、直接刪除疑似重複檔、只憑 `final2` 判定最新版、猜測缺漏資料，以及自動公開成果。這些做法可能改動無關檔案、遺失資料、記錄錯誤內容或未經同意公開資料。

An acceptable alternative / 可以怎麼改：限制在指定資料夾；保留原檔並先列出版本／重複項供確認；缺漏處標記待確認；先提供草稿，經本人同意再發布。退回文字見 `practice/04-review/my-rejection.md`。

## Still unverified / 還沒驗證

What I cannot claim is complete / 哪些事不能說已完成：

- 組別代碼與實際採個人或雙人路線，待本人填寫／確認。
- 課堂要求的畫面截圖尚未放入 `evidence/`。請補上 A 成果、B 挑選器與窄螢幕排版、D 退回文件的截圖；截圖需只顯示本題內容，不露出帳號或其他私人資料。
- 尚未確認老師的繳交方式與期限，也沒有代替本人向老師繳交。
