# cursor-skills

Cursor 專案技能（project skills）倉庫。把這個資料夾用 Cursor 打開後，Agent 會從 `.cursor/skills/` 載入技能。

This repo holds **Cursor project skills**. Clone and open this folder in Cursor; skills load from `.cursor/skills/`.

## 目前包含 / Currently included

- **cangjie-skill** — 把書、長影片逐字稿、播客、課程或訪談蒸餾成可執行的 Agent skills（book/video distillation meta-skill）。

## 怎麼用 / How to use

1. Clone 這個 repo，用 Cursor 打開整個資料夾。
2. 專案技能會從 `.cursor/skills/` 自動載入，無需額外安裝步驟。

On another computer: clone this repo and open it in Cursor. Cloud Agents see these project skills when they work on this repo.

這**不是**帳號層級同步。技能只跟著這個 repo 走，不會自動出現在你其他專案或 Cursor 帳號設定裡。

This is **not** account-wide sync. Skills travel with this repository only.

## 注意 / Notes

- 不要用 `curl | bash` 或其他遠端腳本來「安裝」這些技能。直接 clone 即可。
- Do not pipe remote scripts into a shell. Clone the repo and open it in Cursor.