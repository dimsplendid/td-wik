---
slug: chip-condition-upload
wiki: optical-guide/chip-condition-upload
date created: 2022-04-22 23:16
---
# 樣品條件上傳
1. 下載 template。
2. 確認登錄的材料名。(若沒有該名稱會出錯)
3. 參考 `Example` 埴入資料至 `upload`，RDL SUB 按條件填即可。
4. `exp id` 填實驗單號。
5. platform 為驗証產品
6. 條件是實驗條件。
7. RDL SUB 按條件填即可。
8. ID 為片子 ID，此為全域唯一值，不會有兩片相同 ID 的片子。因此在沒有 ID 的 test cell (如 TN 九宫格)，需埴入 `{exp-id}_{condition}_{short-id}` 確保不會重復(重復會出錯)
9. LC, PI, Seal 需在登錄中，若沒有請先上傳。

![[1_chip_condition_upload.gif]]
5. Next:  [[RDL Cell Gap Upload]]
