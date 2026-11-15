# 导演 Skill 包 · Director Skills for AI Agents

给 AI 助手用的导演工作流 skill：脚本拆解、分镜逐镜表、AI 宠物短剧制作。作者是实拍导演 / 摄影师，这些规则不是从教程里抄的，是在真实项目和一个 AI 短剧账号的连载里一条一条磨出来的，踩过的坑都写在检查清单里了。

A pack of agent skills written by a working director and cinematographer. Each skill encodes rules that were earned on real shoots and on an AI short-drama serial, including the failure checks that came out of actual mistakes.

## 包含的 skill

| Skill | 做什么 |
|---|---|
| [script-breakdown-references](skills/script-breakdown-references/) | 把长文字脚本逐场拆开，每场配真实画面参考（注明来源）和影调方向 |
| [storyboard-shot-list](skills/storyboard-shot-list/) | 把脚本或梗概变成逐镜表：硬切、一镜一景别、表情与状态连续性写死，交付前逐项自查 |
| [ai-pet-video-serial](skills/ai-pet-video-serial/) | AI 宠物短剧连载制作：角色一致性、先试一条再批量、声音与画幅的交付检查 |

## 怎么用

每个 skill 是一个文件夹，里面有 `SKILL.md`（规则正文）和 `skill.yaml`（描述文件）。

- 用 Muse 的，把整个 skill 文件夹放进你的 custom-skills 目录即可。
- 用其他支持 Agent Skills 格式的工具的，按该工具的约定放置 `SKILL.md`。
- 也可以不装，直接把 `SKILL.md` 的内容贴给你的 AI 当工作规范用，效果一样。

规则里的数值和标准（比如镜长、头身比）是作者自己项目的参数，换成你的项目参数再用。

## 作者

贾泽和，导演 / 摄影师。项目经历和联系方式见主页：[github.com/jiazehe0818](https://github.com/jiazehe0818)

配套仓库：[video-breakdown-cases](https://github.com/jiazehe0818/video-breakdown-cases)（爆款视频逐镜拆解库，这套 skill 的很多规则来自那里的拆解）。

## 支持

觉得有用请点个 Star。欢迎扫码请作者喝杯咖啡：

<img src="https://raw.githubusercontent.com/jiazehe0818/video-breakdown-cases/main/sponsor-qr.jpg" alt="微信赞赏码" width="300">

## 许可

[MIT](LICENSE)。随便用，保留出处即可。
