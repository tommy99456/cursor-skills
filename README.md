# cursor-skills

个人 Cursor **项目技能**仓库。把本仓库克隆并在 Cursor 中打开后，Agent 会从 `.cursor/skills/` 加载这些技能。

A personal repo of Cursor **project skills**. Clone this folder and open it in Cursor; skills load from `.cursor/skills/`.

## 当前技能 / Current skills

- **cangjie-skill**：把书、长视频字幕、播客、课程或访谈蒸馏成一组可执行的 Agent skills（方法论 / 原则 / 框架抽取）。
- **cangjie-skill**: Distill a book, long-video transcript, podcast, course, or interview into executable agent skills (frameworks, principles, methodologies).
- **cw-tender-powerpoint**：做或改創威電子系統有限公司（Chong Wai / CW）的標書與銷售安防系統 PowerPoint。
- **cw-tender-powerpoint**: Make or edit 創威電子系統有限公司 (Chong Wai / CW) tender and sales security-system PowerPoint decks.

## 怎么用 / How to use

1. 克隆本仓库，用 Cursor 打开这个文件夹。
2. Clone this repo and open this folder in Cursor.
3. 项目技能会从 `.cursor/skills/` 自动加载；在对话里按技能说明调用即可（例如「把这本书蒸馏成 skill」）。
4. Skills load from `.cursor/skills/`. Invoke them in chat as described in each `SKILL.md`.

**cw-tender-powerpoint：** 在對話裡說要做或改創威電子系統有限公司（Chong Wai / CW）的標書或銷售安防系統 PowerPoint。  
**cw-tender-powerpoint:** In chat, ask to make or edit a CW (創威電子系統有限公司) tender or sales security-system PowerPoint.

**其他电脑：** 克隆同一仓库并打开即可。  
**Other computers:** clone this repo and open it in Cursor.

**Cloud Agents：** 在本仓库上工作时可以看到这些项目技能。  
**Cloud Agents:** they see project skills when working on this repo.

## 这不是账号级同步 / Not account-wide sync

本仓库只提供**项目级**技能。它不会把技能同步到你的 Cursor 账号，也不会安装到 `~/.cursor/skills/`。换电脑或开 Cloud Agent 时，需要打开/工作在这个仓库里，技能才会出现。

This is **not** account-wide sync. Skills here are project-scoped. They are not synced to your Cursor account and are not installed into `~/.cursor/skills/`. On another machine or in a Cloud Agent, the skills appear only when this repo is the workspace.

## 说明 / Notes

- 不要用 `curl | bash` 之类的方式安装本仓库。克隆并用 Cursor 打开即可。
- Do not install this repo with `curl | bash`. Clone it and open it in Cursor.
