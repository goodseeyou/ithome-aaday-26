# agentic automation 落地

## trap 1 - AI super power permission
### red team
### blue team
1. 換掉憑證
2. 手動限縮權限

## trap 2 - 工具即是攻擊面
惡意輸入
indirect prompt injection
### blue team
model 之外設立授權關卡

## trap 3 - 記憶與資料治理
agent 記住的東西 要不要管理

agent owner + data owner 共同管理

## trap 4 - 觀測性
issue 行為不容易 reproduce (model 機率性)

### blue team
logging

## trap 5 - cost
agentic 無限嘗試沒有邊界的工作 -> cost 爆表


?如何完整乾淨的清掉一個 ai goal/task

暫時只能停掉整個 agent


# Framework

AI 自主決策 x ops 監控失效 -> 每次執行軌跡都不同
工具調用 x 應用安全失效 -> 讀進來的內容驅動行動
跨系統協作 x 資料治理失效 -> 身份與記憶

# analyze openclaw


