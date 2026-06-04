# claude-code-notes

CLAUDE.md 給永久規則、memory 給學到的模式、session 給連續性、context 管理給效率、spec 給交接  

- CLAUDE.md — 永久規則，每場 session 載入，壓縮後存活。
- Auto memory — Claude 自學從經驗的筆記。
- Session — 命名、接續、fork。
- Context window — 用 /context 監控、用 /compact 壓縮、用 /clear 清。
- Spec — 你複雜工作的 handoff 文件。
- Checkpoint — Esc+Esc 倒帶任何改動。
- Subagent — 隔離 context 給調查。
- Skill — 按需載入知識不浪費 context。

[Claude2Code](https://claude2code.com/) 免費互動課


## 指令

你昨天做一個功能、今天要繼續。接續最快的方法是？
`claude --continue`  

### allow all permissions 
`claude --dangerously-skip-permissions` 
