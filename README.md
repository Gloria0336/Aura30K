# Aura30K

《銀河修仙世界》的設定、主持規則與戰役資料。由 AI 擔任 GM 的文字角色扮演遊戲。

本儲存庫是所有內容的正本。原有的 Google 文件已停止更新。

## 結構

```
settings/     世界設定，共十三份
rules/        AI 判定與系統建立規則
index/        檢索索引表
campaigns/
  roxia/      洛克西亞戰役
    save.md               存檔：主角已知的現況與劇情摘要
    backstage.md          後台紀錄：玩家角色不知道的事態（含劇透）
    domain_and_fleet.md   領地與艦隊
    roster_characters.md  人物名冊
    roster_locations.md   地點名冊
    generated_content.md  GM 生成、待設計者決定是否收編的內容
    logs/                 每場的完整敘事（GM 於收尾時輸出，見 RULE-6.8）
```

各檔的代碼、路徑與內容見 `index/retrieval_index.md` 第一部分。

## 段落編號

每個有標題的小節都有固定編號，寫在標題開頭的方括號內，格式為「文件代碼-節號」，例如 `REALM-6A`、`RULE-2.5`。

- 中文節號轉為數字；「六之一」記為 `6A`，「六之二」記為 `6B`。
- 標題本身帶有節號者沿用，例如「2-5」記為 `2.5`。
- 標題沒有節號者，依在上層小節中的順序記為 `S1`、`S2`，或接續上層編號。
- 固定名稱的小節使用代稱：`LOG`（版本紀錄）、`TAGS`（知識分層標記）、`SCOPE`（文件定位）、`APX`（附錄）。
- 編號一經發布不得更改或重複使用。新增小節時取新的編號，不重編既有小節。

## 給 GM 的使用順序

1. 讀 `rules/gm_rules.md`。
2. 讀 `campaigns/roxia/save.md` 與 `campaigns/roxia/backstage.md`。
3. 需要查設定時，先查 `index/retrieval_index.md`，再讀所指的小節。
4. 每場結束時更新存檔與後台紀錄；新生成的專有名詞登記到 `generated_content.md`。

## 知識分層

設定文件以【公開】【限定】【GM】【待定】標示每條資訊的可見範圍，定義見各檔的 `TAGS` 小節。標為【GM】的內容與 `backstage.md` 不得在敘事中直接揭露。

## 維護

- 修改任何文件時，一併更新 `index/retrieval_index.md`。
- 各檔的版號與「版本紀錄」停留在搬遷時的版本，之後的修改歷史由本儲存庫記錄。
