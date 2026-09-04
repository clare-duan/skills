# skills

AI skills by [clare-duan](https://github.com/clare-duan)。每个 skill 是一个文件夹，可单独下载使用。

## 收录列表

| Skill | 一句话说明 |
|---|---|
| [trip-planning](./trip-planning/) | 出行安排：安排一群人的吃住行游（旅游和接待通用）。先搞清"这群人是谁、这次图什么"，再决定"什么先钉死、什么留活口"，输出自带预案的行程。提炼自一次 8 天多城家庭出行的全程决策复盘。 |

## 怎么安装使用

### Claude Code 用户

1. 点本页右上角绿色 **Code** 按钮 → **Download ZIP**，解压；
2. 把 `trip-planning` 文件夹拷进你的个人 skill 目录 `~/.claude/skills/`（没有这个目录就新建一个）；
3. 新开一个会话，说"帮我排行程"或"帮我做接待安排"，skill 会自动触发。

### 其他 AI 工具用户（ChatGPT、豆包、Kimi 等）

skill 本体就是一份纯文本方法论，不挑工具：

1. 打开 `trip-planning/SKILL.md`，全文复制发给你的 AI，说"按这份方法论帮我排行程"；
2. 把 `trip-planning/references/persona-template.md` 也全文发给它（画像模板的内容 AI 手上没有，得你喂给它）；
3. 第一次用时，AI 会按模板引导你给同行人建一份"画像档案"——存在你自己的笔记里，下次直接复用。

## 说明

- 方法论里的平台、价格类信息是**时点状态**（各条已标注确认时间），使用前请自行复核。
- 这套方法论靠"行后回流"长大：欢迎在 Issues 里反馈你实际使用中踩的坑和补的问题。
