# Claude Token Efficiency Template

JJ 的 Claude Code 跨專案 token 效率設定模板。

## 用途

複製 `CLAUDE.md` 和 `.claudeignore` 到任何專案根目錄，讓 Claude 在所有專案都遵守相同的溝通規則與 token 效率原則。

## 核心原則

1. **直接進內容** — 不說廢話、不問要不要記錄、不複述已完成動作
2. **工具呼叫不預告** — 執行完才報結果
3. **有變更即更新** — 環境變動立刻更新文件和記憶
4. **Session 開頭狀態回報** — 上次進度、未完成事項、今日注意

## 如何使用

```bash
# 在任何專案根目錄執行：
curl -sO https://raw.githubusercontent.com/gossipredm4/claude-token-efficiency/main/CLAUDE.md
curl -sO https://raw.githubusercontent.com/gossipredm4/claude-token-efficiency/main/.claudeignore
```

然後在 `CLAUDE.md` 底部補上該專案的環境設定和 Gotchas。

## 記憶系統

建議每個專案建立 `memory/` 目錄，用 `MEMORY.md` 做索引。詳見 `CLAUDE.md` 說明。
